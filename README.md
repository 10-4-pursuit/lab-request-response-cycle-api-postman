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

> https://pokeapi.co/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is... All the Pokémon data you'll ever need in one place,
easily accessible through a modern RESTful API.

- What is the URL of the documentation?

> https://pokeapi.co/docs/v2

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://pokeapi.co/api/v2/ability/7/

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "abilities": [
        {
            "ability": {
                "name": "limber",
                "url": "https://pokeapi.co/api/v2/ability/7/"
            },
            "is_hidden": false,
            "slot": 1
        },
        {
            "ability": {
                "name": "imposter",
                "url": "https://pokeapi.co/api/v2/ability/150/"
            },
            "is_hidden": true,
            "slot": 3
        }
    ],
    "base_experience": 101,
    "forms": [
        {
            "name": "ditto",
            "url": "https://pokeapi.co/api/v2/pokemon-form/132/"
        }
    ],
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: N/A from what I see.

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes... 

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ...

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ... Very straight forward. I understood the reading.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ... The reading was clear.

- Did the quality of the documentation impact your decision to use it?

> Yes/No because... Yes & No this is one of my first go arounds with APIS and dont really have anything to compare it to yet.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ... No I stuck with mine the entire lab.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ... It describes the things that occur when a client sends a request to a server, and the server responds to that request.

- In your own words, describe what an API is.

> An API is ... An API defines the methods and data formats that applications can use to request and exchange information. They seem to serve as a bridge between different software applications.

- In your own words, describe the purpose of Postman.

> Postman is an application that ... It is a tools used for the process of designing, testing, and documenting APIs
public-apis/public-apis
