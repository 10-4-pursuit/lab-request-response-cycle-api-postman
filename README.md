# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API with no auth and no CORS from the following list. It _should not_ be one that you've already seen or worked on in class.
   - [Public APIs](https://github.com/public-apis/public-apis)
1. Choose an API not covered in your readings, class, or other assignments. The API should be new to you.
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.
1. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

## Instructions

Do your best to answer the questions with specific details. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL.

> NASA Image and Video Library https://images-api.nasa.gov/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to make NASA data and images available to app developers. Those interested in NASA, astronauts, space exploration, planets, rockets, shuttles, etc could learn from the information provided and share it through an app.

- What is the URL of the documentation?

> https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://images-api.nasa.gov/search?q=Saturn

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
"collection": {
        "version": "1.0",
        "href": "http://images-api.nasa.gov/search?q=Saturn",
        "items": [
            {
                "href": "https://images-assets.nasa.gov/image/PIA01973/collection.json",
                "data": [
                    {
                        "center": "JPL",
                        "title": "Saturn Atmosphere",
                        "nasa_id": "PIA01973",
                        "date_created": "1999-06-16T10:03:17Z",
                        "keywords": [
                            "Saturn",
                            "Voyager"
                        ],
                        "media_type": "image",
                        "description_508": "Saturn Atmosphere",
                        "secondary_creator": "NASA/JPL",
                        "description": "Saturn Atmosphere"
                    }
                ],
                "links": [
                    {
                        "href": "https://images-assets.nasa.gov/image/PIA01973/PIA01973~thumb.jpg",
                        "rel": "preview",
                        "render": "image"
                    }
                ]
            },

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK because my request was successful.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json

> `Content-Length`: 55344

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes many pictures of Saturn, the specific URL for each picture, the title and the date it was created. There is other data that could help someone find paticular pictures like the center that created them or the keywords to search with.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that showed the beauty of Saturn with a picture gallery, used pictures to show how Saturn changes during a year or illustrated the weather on Saturn.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was helpful because it gave an example of what to put into the URL of a request. This is the example in the documentation "https://images-api.nasa.gov/search
?q=apollo%2011
&description=moon%20landing
&media_type=image" |
python -m json.tool

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation challenging because it showed different ways to make the search request (/search, /search?q={q}, https://images-api.nasa.gov/search
--data-urlencode "q=apollo 11). I needed a bit of trial and error to figure out the exact syntax for my request.

- Did the quality of the documentation impact your decision to use it?

> Yes because it helped me figure out how to make a successful request after having problems.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No, this was my first choice. I thought I would have to switch because my initial requests didn't work. I went back to it, tried a few more times and I finally received some information.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is the interactions between users, clients, servers and databases that enable us to use the internet.

- In your own words, describe what an API is.

> An API is a collection of data that allows other applications to use the data.

- In your own words, describe the purpose of Postman.

> Postman is an application that makes working with APIs easier by allowing us to test requests.
