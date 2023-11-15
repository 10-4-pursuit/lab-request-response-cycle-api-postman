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

> http://www.dnd5eapi.co

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to generate informtion on about DnD for players.

- What is the URL of the documentation?

> http://www.dnd5eapi.co/docs

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> http://www.dnd5eapi.co/api/subraces/hill-dwarf

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "index": "hill-dwarf",
    "name": "Hill Dwarf",
    "race": {
        "index": "dwarf",
        "name": "Dwarf",
        "url": "/api/races/dwarf"
    },
    "desc": "As a hill dwarf, you have keen senses, deep intuition, and remarkable resilience.",
    "ability_bonuses": [
        {
            "ability_score": {
                "index": "wis",
                "name": "WIS",
                "url": "/api/ability-scores/wis"
            },
            "bonus": 1
        }
    ],
    "starting_proficiencies": [],
    "languages": [],
    "racial_traits": [
        {
            "index": "dwarven-toughness",
            "name": "Dwarven Toughness",
            "url": "/api/traits/dwarven-toughness"
        }
    ],
    "url": "/api/subraces/hill-dwarf"
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK
> `Everything went great! Meaning that the request successfully reached the server, was formatted as expected, and that the server could respond.`

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: 496

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes descriptions about the given subrace of Hill Dwarf, with descriptions about the subrace along with links to the broader dwarven race, ability scores and starting proficiencies. 

- Identify at least two ways to use the data within a web application.

> 1. I could imagine integrating this API into an app that allows players to better build their DnD characters with a more colorful background flavoring in order to provide more story building opportunities especially in an online game of DnD.
> 2. To inform the DM/GM (Dungeon Master/Game Master) with information about said subrace to add into their world building process for the campaign setting the party will be playing. 

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was inciteful with the information it did offer about this particular dwarven subrace of the Hill Dwarf that I believe it could lead to a player having a relatively good experience playing as this subrace for their character. And if the player wanted to play as a different subrace or they were not satisfied with a specific subrace which came up, they could us the index to choose a different subrace that is available for a player's character. 

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation challenging in only one aspect and that's that it did not offer more in the way of information that could've built upon the subrace information provided for this subrace choice for player characters. 

- Did the quality of the documentation impact your decision to use it?

> Yes because of the documentations straight forward information and the ease to readness of it I decide to use this particular API. 

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I ended up sticking with the API I chose since the documentations was pretty straight forward and the information it provided I feel would allow for a player to better play as the subrace of their choicd in this case a Hill Dwarf. 

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is the interaction between a client; usually a user or another software application and a server which hosts the API when making and processing said API request. 

- In your own words, describe what an API is.

> An API is a set of rules and protocols which allow different software applications to communicate with one another. It can be said to be the methods and data formats that applications can use to request and exchange information or perform certain tasks. 

- In your own words, describe the purpose of Postman.

> Postman is an application that allows users to simplify API development and testing. It is used by said users to ensure the reliability and functionality of APIs and foster collaboration and documention of API interations. 
