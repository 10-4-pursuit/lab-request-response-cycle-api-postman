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

> https://boardgamegeek.com/xmlapi/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to gather data on boardgames. This data provides information like the creator behind a boardgame, user ratings, and current marketplace price. This is a great resource for boardgame enthuasiasts.

- What is the URL of the documentation?

> https://api.geekdo.com/xmlapi2

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://boardgamegeek.com/xmlapi/search?search=mythology

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```   
<boardgame objectid="6707">
			<name primary="true">Age of Mythology: The Boardgame</name>			
							<yearpublished>2003</yearpublished>
					</boardgame>
			<boardgame objectid="14008">
			<name primary="true">Age of Mythology: The Boardgame – 5-6 Player Expansion</name>			
							<yearpublished>2003</yearpublished>
					</boardgame>

```

- What status code did you get back from your request? Why did you receive this status code?

> I the status code I received was a 200. This means that the request-response cycle was a success. 

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: text/xml; charset="UTF-8"

> `Content-Length`:

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes...

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ...

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ...

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ...

- In your own words, describe what an API is.

> An API is ...

- In your own words, describe the purpose of Postman.

> Postman is an application that ...
