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

> https://www.dnd5eapi.co/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to generate information for DnD.

- What is the URL of the documentation?

> https://www.dnd5eapi.co/docs

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://www.dnd5eapi.co/api/spells/acid-splash

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```
{
    "higher_level": [],
    "index": "acid-splash",
    "name": "Acid Splash",
    "desc": [
        "You hurl a bubble of acid. Choose one creature within range, or choose two creatures within range that are within 5 feet of each other. A target must succeed on a dexterity saving throw or take 1d6 acid damage.",
        "This spell's damage increases by 1d6 when you reach 5th level (2d6), 11th level (3d6), and 17th level (4d6)."
    ],
    "range": "60 feet",
    "components": [
        "V",
        "S"
    ],
    "ritual": false,
    "duration": "Instantaneous",
    "concentration": false,
    "casting_time": "1 action",
    "level": 0,
    "damage": {
        "damage_type": {
            "index": "acid",
            "name": "Acid",
            "url": "/api/damage-types/acid"
        },
        "damage_at_character_level": {
            "1": "1d6",
            "5": "2d6",
            "11": "3d6",
            "17": "4d6"
        }
    },
    "dc": {
        "dc_type": {
            "index": "dex",
            "name": "DEX",
            "url": "/api/ability-scores/dex"
        },
        "dc_success": "none"
    },
    "school": {
        "index": "conjuration",
        "name": "Conjuration",
        "url": "/api/magic-schools/conjuration"
    },
    "classes": [
        {
            "index": "sorcerer",
            "name": "Sorcerer",
            "url": "/api/classes/sorcerer"
        },
        {
            "index": "wizard",
            "name": "Wizard",
            "url": "/api/classes/wizard"
        }
    ],
    "subclasses": [
        {
            "index": "lore",
            "name": "Lore",
            "url": "/api/subclasses/lore"
        }
    ],
    "url": "/api/spells/acid-splash"
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK. The 200 OK status code means that the request was successful.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: 25677

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes urls to each spells specific page.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that can keep track of someone's spells during a DnD campaign. The info can also be used to make an app that contains all the information so you can pull it up on devices instead of carrying the books.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation provided a curl command to access all the information in terminal.

- What did you find challenging about the documentation? Cite specific examples.

> The concept of schemas and GraphQL are new to me so the information was a bit intimidating at first glance.

- Did the quality of the documentation impact your decision to use it?

> Yes. The documentation did a good job defining everything and explaining the new concepts.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> I stuck with the one I selected and worked through it.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The client (like an app or a website) asks the server for specific information or to do something using an API. The server interprets the request, performs the necessary action, and gets the requested data (if applicable). The server sends the requested information or confirmation of the action back to the client. The client receives this response and acts accordingly, displaying data or continuing its operations.

- In your own words, describe what an API is.

> APIs define how this communication happens, including the rules and formats for requests and responses, enabling different software to work together.

- In your own words, describe the purpose of Postman.

> Postman is an application that allows you to manage multiple API requests and create new APIs more efficiently.
