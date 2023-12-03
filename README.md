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

> http://www.purgomalum.com

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to filter and remove content of profanity, obscenity and other unwanted text.

- What is the URL of the documentation?

> http://www.purgomalum.com

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> http://www.purgomalum.com/profanitylist.html

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json

Home|Profanity List
Profanity List
This is the current profanity list. If you would like any new words added to this list, please contact me. Note: You can include up to 10 additional words to the profanity list in your request by using the "add" parameter.

arse
arsehole
ass
asses
assface
assfaces
asshole
assholes
bastard
bastards
beaner
bellend
bint
bitch
bitches
bitchy
blowjob
blump
blumpkin
bollocks
bollox
boner
bukkake
bullshit
bunghole
buttcheeks
butthole
buttpirate
buttplug
carpetmuncher
chinc
chink
choad
chode
circlejerk
clit
clunge
cock
cocksucker
cocksuckers
cocksucking
coochie
coochy
coon
cooter
cornhole
cum
cunnie
cunt
cunts
dago
dic
dick
dickhead
dickheads
dik
dike
dildo
doochbag
doosh
douche
douchebag
dumbass
dumbasses
dyke
fag
fagget
faggit
faggot
faggots
fagtard
fanny
feck
felch
feltch
figging
fingerbang
frotting
fuc
fuck
fucked
fuckedup
fucker
fuckers
fucking
fuckoff
fucks
fuckup
fudgepacker
fuk
fukker
fukkers
fuq
gangbang
gash
goddamn
goddamnit
gokkun
gooch
gook
guido
heeb
honkey
hooker
jackass
jackasses
jackoff
jap
jerkoff
jigaboo
jiggerboo
jizz
junglebunny
kike
knobbing
kooch
kootch
kraut
kyke
lesbo
lezzie
milf
minge
motherfucker
motherfuckers
motherfucking
muff
muffdiver
muffdiving
munging
munter
ngga
niga
nigga
nigger
niggers
niglet
nigr
paki
panooch
pecker
peckerhead
pillock
piss
pissed
pollock
poon
poonani
poonany
poontang
porchmonkey
prick
punani
punanny
punany
pussie
pussies
pussy
puta
puto
quim
raghead
ruski
schlong
scrote
shag
shit
shite
shithead
shitheads
shits
shittier
shittiest
shitting
shitty
skank
skeet
slag
slanteye
slut
smartass
smartasses
smeg
snatch
spic
spick
splooge
spooge
teabagging
tit
tities
tits
titties
titty
tosser
towelhead
twat
vibrator
wank
wanker
wetback
whore
wiseass
wiseasses
wop
© PurgoMalum.com | Home

```

- What status code did you get back from your request? Why did you receive this status code?

> 200 OK. I received this status code because the request successfully reached the server, was formatted as expected, and that the server could respond.

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: text/html

> `Content-Length`: 1493

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes was a list of profane words.

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that highlight the words in the list and suggest decent substitutions. Another use case would be not allow these words to be implimented or allowed in an application aim to be used by adolescences.  

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was helpful because it gives a current list of available parameters which can be used in the request query string and it provides examples of PurgoMalum implementations.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation challenging because it didn't explain what the API function could do in layman-readable format.

- Did the quality of the documentation impact your decision to use it?

> Yes because it provided me with enough information on how to obtain the data.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No I ended up sticking with the one I selected and worked my way through it.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is a fundamental concept in web communication that outlines the interaction between a client and a server.

- In your own words, describe what an API is.

> An API is  a bridge that allows different software applications to communicate and interact with each other.

- In your own words, describe the purpose of Postman.

> Postman is an application that is designed to streamline and facilitate the process of working with APIs during the development and testing phases. 
