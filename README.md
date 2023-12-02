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

> Cat Facts
> https://meowfacts.herokuapp.com/

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is...
>A simple api that returns a random fact about cats on a GET request

.

- What is the URL of the documentation?

> https://meowfacts.herokuapp.com 

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://cat-fact.herokuapp.com
- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "data": [
        "Neutering a cat extends its life span by two or three years.",
        "Owning a cat can reduce the risk of stroke and heart attack by a third.",
        "Cats sleep 16 to 18 hours per day. When cats are asleep, they are still alert to incoming stimuli. If you poke the tail of a sleeping cat, it will respond accordingly.",
        "The first cat show was in 1871 at the Crystal Palace in London.",
        "Many cats cannot properly digest cows milk. Milk and milk products give them diarrhea.",
        "In 1987 cats overtook dogs as the number one pet in America.",
        "The Maine Coone is the only native American long haired breed.",
        "A happy cat holds her tail high and steady.",
        "Purring not always means happiness. Purring could mean a cat is in terrible pain such as during childbirth. Kitten will purr to their mother to let her know they are getting enough milk while nursing. Purring is a process of inhaling and exhaling, usually performed while the mouth is closed. But don't worry, if your cat is purring while your gently petting her and holding her close to you - that is a happy cat!",
        "The average cat food meal is the equivalent to about five mice."
    ]
}


```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK meaning there was a successful response.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: 1166

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> Its basically puts the object data (Cat Facts) in an array of different facts about cats. Very informative facts about your cat.


- Identify at least two ways to use the data within a web application.

> You can use it for like a daily cat facts calendar.
> A random cat facts generator. I would personally be intrested in making a cute random cat fact generator or a daily cat facts calender for the few people I know that love thier cats.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ...

> As a proud cat owner I liked that it gives a good amount of very informative cats facts. Some of which I was not aware of.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...

> Nothing particularly challenging, I guess maybe the finding the correct prompts you need to pull the APIs information.

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...

> Yes, because I have a cat and it just seemed subjectively informative. I don't know how anyone else would feel about the information. I know more dog people than cat people.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...

> Yes, I did originally had an arts and design API that I was working with, but it ended up being not what I expected. Didn't know what the hell I was  looking at, at the time although now that I'm able to navigate postman a little better. I'm sure I would have an easier time understanding what it is I'm looking at, so I'll probaby check out the arts and design API again.

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
