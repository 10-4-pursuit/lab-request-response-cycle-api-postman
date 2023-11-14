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

> https://date.nager.at/api/v3/publicholidays/2023/CA

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to search public holidays from a given year and country.

- What is the URL of the documentation?

> https://date.nager.at/swagger/index.html

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://date.nager.at/api/v3/publicholidays/2023/CA

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
[
    {
        "date": "2023-01-01",
        "localName": "New Year's Day",
        "name": "New Year's Day",
        "countryCode": "CA",
        "fixed": true,
        "global": true,
        "counties": null,
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-02-20",
        "localName": "Louis Riel Day",
        "name": "Louis Riel Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-MB"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-02-20",
        "localName": "Islander Day",
        "name": "Islander Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-PE"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-02-20",
        "localName": "Heritage Day",
        "name": "Heritage Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-NS"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-02-20",
        "localName": "Family Day",
        "name": "Family Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-AB",
            "CA-BC",
            "CA-NB",
            "CA-ON",
            "CA-SK"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-03-17",
        "localName": "Saint Patrick's Day",
        "name": "Saint Patrick's Day",
        "countryCode": "CA",
        "fixed": true,
        "global": false,
        "counties": [
            "CA-NL"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-04-07",
        "localName": "Good Friday",
        "name": "Good Friday",
        "countryCode": "CA",
        "fixed": false,
        "global": true,
        "counties": null,
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-04-10",
        "localName": "Easter Monday",
        "name": "Easter Monday",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-AB",
            "CA-PE"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-04-23",
        "localName": "Saint George's Day",
        "name": "Saint George's Day",
        "countryCode": "CA",
        "fixed": true,
        "global": false,
        "counties": [
            "CA-NL"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-05-22",
        "localName": "National Patriots' Day",
        "name": "National Patriots' Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-QC"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-05-22",
        "localName": "Victoria Day",
        "name": "Victoria Day",
        "countryCode": "CA",
        "fixed": false,
        "global": true,
        "counties": null,
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-06-21",
        "localName": "National Aboriginal Day",
        "name": "National Aboriginal Day",
        "countryCode": "CA",
        "fixed": true,
        "global": false,
        "counties": [
            "CA-NT"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-06-24",
        "localName": "Discovery Day",
        "name": "Discovery Day",
        "countryCode": "CA",
        "fixed": true,
        "global": false,
        "counties": [
            "CA-NL"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-06-24",
        "localName": "Fête nationale du Québec",
        "name": "National Holiday",
        "countryCode": "CA",
        "fixed": true,
        "global": false,
        "counties": [
            "CA-QC"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-07-01",
        "localName": "Canada Day",
        "name": "Canada Day",
        "countryCode": "CA",
        "fixed": false,
        "global": true,
        "counties": null,
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-07-12",
        "localName": "Orangemen's Day",
        "name": "Orangemen's Day",
        "countryCode": "CA",
        "fixed": true,
        "global": false,
        "counties": [
            "CA-NL"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-08-07",
        "localName": "Civic Holiday",
        "name": "Civic Holiday",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-BC",
            "CA-MB",
            "CA-NL",
            "CA-NT",
            "CA-NU",
            "CA-ON"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-08-07",
        "localName": "Heritage Day",
        "name": "Heritage Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-AB",
            "CA-YT"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-08-07",
        "localName": "New Brunswick Day",
        "name": "New Brunswick Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-NB"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-08-07",
        "localName": "Natal Day",
        "name": "Natal Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-NS"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-08-07",
        "localName": "Saskatchewan Day",
        "name": "Saskatchewan Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-SK"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-08-21",
        "localName": "Gold Cup Parade Day",
        "name": "Gold Cup Parade Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-PE"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-08-21",
        "localName": "Discovery Day",
        "name": "Discovery Day",
        "countryCode": "CA",
        "fixed": false,
        "global": false,
        "counties": [
            "CA-YT"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-09-04",
        "localName": "Labour Day",
        "name": "Labour Day",
        "countryCode": "CA",
        "fixed": false,
        "global": true,
        "counties": null,
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-09-30",
        "localName": "National Day for Truth and Reconciliation",
        "name": "National Day for Truth and Reconciliation",
        "countryCode": "CA",
        "fixed": true,
        "global": true,
        "counties": null,
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-10-09",
        "localName": "Thanksgiving",
        "name": "Thanksgiving",
        "countryCode": "CA",
        "fixed": false,
        "global": true,
        "counties": null,
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-11-11",
        "localName": "Armistice Day",
        "name": "Armistice Day",
        "countryCode": "CA",
        "fixed": true,
        "global": false,
        "counties": [
            "CA-NL"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-11-11",
        "localName": "Remembrance Day",
        "name": "Remembrance Day",
        "countryCode": "CA",
        "fixed": true,
        "global": false,
        "counties": [
            "CA-AB",
            "CA-BC",
            "CA-NB",
            "CA-NT",
            "CA-NS",
            "CA-NU",
            "CA-PE",
            "CA-SK",
            "CA-YT"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-12-25",
        "localName": "Christmas Day",
        "name": "Christmas Day",
        "countryCode": "CA",
        "fixed": true,
        "global": true,
        "counties": null,
        "launchYear": null,
        "types": [
            "Public"
        ]
    },
    {
        "date": "2023-12-26",
        "localName": "Boxing Day",
        "name": "St. Stephen's Day",
        "countryCode": "CA",
        "fixed": true,
        "global": false,
        "counties": [
            "CA-AB",
            "CA-NB",
            "CA-NS",
            "CA-ON",
            "CA-PE"
        ],
        "launchYear": null,
        "types": [
            "Public"
        ]
    }
]

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`:application/json; charset=utf-8

> `Content-Length`: none listed

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes...the actual date of the holiday, the name of the holiday (locally and nationally), the country code, if it is fixed and global and the counties the holiday is recognized, the launch of the holiday start and if it is public

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ...lists holidays in particular regions for either noting dates that items don't ship or dates the reps are not available

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ...a little hard to understand to be honest.  the way it was set up was clear but then when i input information i was getting errors

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ...confusing.  there is a place where they let you input parameters like postman in their site but it brings up an error code when listed in postman

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...yes.  i don't know that i would use it simply because i didn't like the lack of clarity of the documention 

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ...i stuck with this one after going through several others due to errors (400s)

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ...I make a request  (through my computer) and i get a response after my reqeust is made that gets returned from the server.

- In your own words, describe what an API is.

> An API is ...data that i can access when i make a request.  this data i can use in my code and it will generate/populate information that is useful to me based on specific examples/data i need.

- In your own words, describe the purpose of Postman.

> Postman is an application that ... allows me to see details on an api such as the data, if the connection is working, checking the data and pulling from it. 
