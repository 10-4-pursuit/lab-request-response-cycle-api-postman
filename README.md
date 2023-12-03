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
> NUMBERSAPI
> http://numbersapi.com

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to provide interesting facts about numbers. The number could be an integer, or the keyword random, for which they will try to return a random available fact, or a day of year in the form month/day (eg. 2/29, 1/09, 04/1). Someone might want to use it for educational purposes or entertainment.

- What is the URL of the documentation?

> http://numbersapi.com/#42. Under API REFERENCE.

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> http://numbersapi.com/8,9..17,1000

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
> {
    "8": "8 is the number of legs that arachnids have.",
    "9": "9 is the number of innings in a regulation, non-tied game of baseball.",
    "10": "10 is the highest score possible in Olympics gymnastics competitions.",
    "11": "11 is the number of incarnations of The Doctor in BBC sci-fi series Doctor Who.",
    "12": "12 is the number of basic hues in the color wheel (3 primary colors (red, yellow, blue), 3 secondary colors (orange, green & purple) and 6 tertiary colors).",
    "13": "13 is the number of Oscar nominations of actress Meryl Streep, who holds the record for the most Oscar nominated actress.",
    "14": "14 is the earliest age that the emancipation of minors can occur in the U.S.",
    "15": "15 is the number of times an average person laughs a day.",
    "16": "16 is the number of personality types in the Myers-Briggs classification system.",
    "17": "17 is the number of the raka'ahs that Muslims perform during Salah on a daily basis.",
    "1000": "1000 is the number of elephants it took to bring in the material to build the Taj Mahal from various parts of India."
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200. The request successfully reached the server, was formatted as expected, and that the server could respond. Everything went great!

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: text/html; charset=utf-8

> `Content-Length`: NA

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes interesting facts about the numbers 8 through 17 and an interresting fact about the number 1000.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that allow users to input a specific number, and then fetch and display facts related to that number. I could also integrate this API into an app that generates a number-of-the-day.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was clear and direct. It cited the use of the API, the different parameters one can use and how to use them. It also provided examples of what the responses should look like.

- What did you find challenging about the documentation? Cite specific examples.

> Part of the documentation uses certain coding jargon Im not familiar with, but it wasn't information I needed so I looked past it.

- Did the quality of the documentation impact your decision to use it?

> Yes because I understood the information and the documentation showed me how to apply it.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> I specifically chose this API because it seemed easy enough to work through it and it didnt let me down!

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is when a client makes a request to a server, the server gets the request, processes it and sends a response back to the client.

- In your own words, describe what an API is.

> An API is the middle man that takes your request to the database and brings back the results. An API allows software systems to communicate with one another and work collaboratively. 

- In your own words, describe the purpose of Postman.

> Postman is an application that allows you to easily test out your API calls, customize the requests and inspect responses. Postman also provides metadata for the response. 