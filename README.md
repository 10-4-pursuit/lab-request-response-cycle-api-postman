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

> https://pokeapi.co/api/v2/pokemon

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is...

> The API at https://pokeapi.co/api/v2/pokemon is part of the Pokemon API PokeAPI, which is a RESTful web service that provides a comprehensive set of data related to Pokemon. When you make a GET request to this endpoint, you receive data about Pokemon, including their names, abilities, forms, game indices, held items, moves, and more. The response is typically in JSON format, making it easy to parse and use in web applications.

- What is the URL of the documentation?

> http://PokeAPI Documentation

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> http://pokeapi.co/api/v2/pokemon

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "count": 1292,
    "next": "https://pokeapi.co/api/v2/pokemon?offset=20&limit=20",
    "previous": null,
    "results": [
        {
            "name": "bulbasaur",
            "url": "https://pokeapi.co/api/v2/pokemon/1/"
        },
        {
            "name": "ivysaur",
            "url": "https://pokeapi.co/api/v2/pokemon/2/"
        },
        {
            "name": "venusaur",
            "url": "https://pokeapi.co/api/v2/pokemon/3/"
        },
        {
            "name": "charmander",
            "url": "https://pokeapi.co/api/v2/pokemon/4/"
        },
        {
            "name": "charmeleon",
            "url": "https://pokeapi.co/api/v2/pokemon/5/"
        },
        {
            "name": "charizard",
            "url": "https://pokeapi.co/api/v2/pokemon/6/"
        },
        {
            "name": "squirtle",
            "url": "https://pokeapi.co/api/v2/pokemon/7/"
        },
        {
            "name": "wartortle",
            "url": "https://pokeapi.co/api/v2/pokemon/8/"
        },
        {
            "name": "blastoise",
            "url": "https://pokeapi.co/api/v2/pokemon/9/"
        },
        {
            "name": "caterpie",
            "url": "https://pokeapi.co/api/v2/pokemon/10/"
        },
        {
            "name": "metapod",
            "url": "https://pokeapi.co/api/v2/pokemon/11/"
        },
        {
            "name": "butterfree",
            "url": "https://pokeapi.co/api/v2/pokemon/12/"
        },
        {
            "name": "weedle",
            "url": "https://pokeapi.co/api/v2/pokemon/13/"
        },
        {
            "name": "kakuna",
            "url": "https://pokeapi.co/api/v2/pokemon/14/"
        },
        {
            "name": "beedrill",
            "url": "https://pokeapi.co/api/v2/pokemon/15/"
        },
        {
            "name": "pidgey",
            "url": "https://pokeapi.co/api/v2/pokemon/16/"
        },
        {
            "name": "pidgeotto",
            "url": "https://pokeapi.co/api/v2/pokemon/17/"
        },
        {
            "name": "pidgeot",
            "url": "https://pokeapi.co/api/v2/pokemon/18/"
        },
        {
            "name": "rattata",
            "url": "https://pokeapi.co/api/v2/pokemon/19/"
        },
        {
            "name": "raticate",
            "url": "https://pokeapi.co/api/v2/pokemon/20/"
        }
    ]
}


```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK meaning there was a successful response.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: 155

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes...
> Count: The total count of Pokemon available in the dataset.
> Next: A URL link to the next page of Pokemon data, allowing for paginated retrieval.
> Previous: A URL link to the previous page of Pokemon data (null if on the first page).
> Results: An array of Pokemon entries, where each entry includes:
> Name: The name of the Pokemon.
> URL: A URL link to retrieve more detailed information about the specific Pokemon.


- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ...

> Pokedex Display:

>Use the data to create a Pokedex-style application where users can browse and view information about different Pokemon.

> Team Builder/Game Companion:

>Create a Pokemon team builder or game companion app where users can assemble and manage their Pokemon teams for battles.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ...

> Very informative in the sence that if I ever was intrested in making a bootleg  version of something like a pokemon game I can do so with the help of the API, or I can at least use it as a reference point. I dont want to get sued.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...

> Maybe the part where we were asked to search for the content-type and length. I eventually figured out how to search for the infomation, but at this point in time I'm not to familiar with how to navigate postman and manipulate it to give me all the info I might need for a certain project. I also see myself attempting to use certain APIs on my own projects. Perhaps a gps API or a weather API. I am very interest in learning more about this, it seems like its bootstrap but for APIs.  

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...

> Yes, went I looked through the questions in the documentation it seemed like I would have an easier time with the answers using the pokeapi. Also it was one of the only apis I could get to work on postman. I also  subjectively found the pokeapi to be not as boring as the rest of the API options. I would maybe like to create a game or two at some point of my software engineering career. This I feel brings me a few steps closer to that.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...

> Yes, I did originally have an arts and design API that I was working with, but it ended up being not what I expected. Didn't know what the hell I was  looking at, at the time although now that I'm able to navigate postman a little better. I'm sure I would have an easier time understanding what it is I'm looking at, so I'll probaby check out the arts and design API again.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ...

> It describes the things that occur when a client sends a request to a server, and the server responds to that request. 

- In your own words, describe what an API is.

> An API is ...

>  An API defines the methods and data formats that applications can use to request and exchange information. They seem to serve as a bridge between different software applications.

- In your own words, describe the purpose of Postman.

> Postman is an application that ...

> It is a tools used for the process of designing, testing, and documenting APIs
