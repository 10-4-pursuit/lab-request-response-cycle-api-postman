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

> https://github.com/metmuseum/openaccess

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is...

- What is the URL of the documentation?

> https://metmuseum.github.io/

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://metmuseum.github.io/#search

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "objectID": 1,
    "isHighlight": false,
    "accessionNumber": "1979.486.1",
    "accessionYear": "1979",
    "isPublicDomain": false,
    "primaryImage": "",
    "primaryImageSmall": "",
    "additionalImages": [],
    "constituents": [
        {
            "constituentID": 164292,
            "role": "Maker",
            "name": "James Barton Longacre",
            "constituentULAN_URL": "http://vocab.getty.edu/page/ulan/500011409",
            "constituentWikidata_URL": "https://www.wikidata.org/wiki/Q3806459",
            "gender": ""
        }
    ],
    "department": "The American Wing",
    "objectName": "Coin",
    "title": "One-dollar Liberty Head Coin",
    "culture": "",
    "period": "",
    "dynasty": "",
    "reign": "",
    "portfolio": "",
    "artistRole": "Maker",
    "artistPrefix": "",
    "artistDisplayName": "James Barton Longacre",
    "artistDisplayBio": "American, Delaware County, Pennsylvania 1794–1869 Philadelphia, Pennsylvania",
    "artistSuffix": "",
    "artistAlphaSort": "Longacre, James Barton",
    "artistNationality": "American",
    "artistBeginDate": "1794",
    "artistEndDate": "1869",
    "artistGender": "",
    "artistWikidata_URL": "https://www.wikidata.org/wiki/Q3806459",
    "artistULAN_URL": "http://vocab.getty.edu/page/ulan/500011409",
    "objectDate": "1853",
    "objectBeginDate": 1853,
    "objectEndDate": 1853,
    "medium": "Gold",
    "dimensions": "Dimensions unavailable",
    "measurements": null,
    "creditLine": "Gift of Heinz L. Stoppelmann, 1979",
    "geographyType": "",
    "city": "",
    "state": "",
    "county": "",
    "country": "",
    "region": "",
    "subregion": "",
    "locale": "",
    "locus": "",
    "excavation": "",
    "river": "",
    "classification": "",
    "rightsAndReproduction": "",
    "linkResource": "",
    "metadataDate": "2021-04-06T04:41:04.967Z",
    "repository": "Metropolitan Museum of Art, New York, NY",
    "objectURL": "https://www.metmuseum.org/art/collection/search/1",
    "tags": null,
    "objectWikidata_URL": "",
    "isTimelineWork": false,
    "GalleryNumber": ""
}
```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=UTF-8

> `Content-Length`: n/a

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes... details about an artwork with objectID 1, such as its accession number, accession year, public domain status, and a URL to the primary image of the artwork.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that ... displays detailed information about a specific artwork.
> I could imagine integrating this API into an app that ... creates galleries or showcases of artworks from the Metropolitan Museum of Art.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was ... comprehensive and well-structured. It provided clear examples of endpoints, parameters, and responses. The inclusion of sample requests and responses for each endpoint was particularly helpful.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation ... to not be so challenging compared to others I've encountered. It was easy to nvigate maybe because it is a public API which might be more organized.

- Did the quality of the documentation impact your decision to use it?

> **Yes**/No because... since it was so easy to navigate, API's like this one could be a clear reason to give it use.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> **Yes**/No I ended up ... with THE MET API, but I first RAPPI API which is under the shopping public API's. I chose THE MET API because of its clear documentation and also because it was all in one page.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle ... is a communication process between clients and servers. It begins with a client sending a request to a server, the server processing the request, and then sending back an appropriate response. This cycle forms the basis of how web applications and APIs interact.

- In your own words, describe what an API is.

> An API is ... a set of rules and tools that allows different software applications to communicate with each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that ... simplifies the process of working with APIs by offering features like request history, environment variables, and automated testing capabilities.
