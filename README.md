# Polling-System-API

## How to use it in your local system

1. First install mongodb community server on your device by going into the mongodb websites and then download mongodb community server
2. Once you download the mongoDb community server then just open your terminal and run the command as `npm install`
3. After running the command , it will download all the libralries needed to run this project.
4. For using This project , You need the postMan and Mongodb Compass getting the documents saved in you database.
5. just Download the MongoDb Compass and PostMan from the browser.

## How to use PostMan

1. Open PostMan
2. Enter The Url into the postMan with the required Method and data to pass with the request
3. Then just Note The Change in your database.

### URL That I Have Created

1. http://localhost:8000/questions/create To create the questions
2. http://localhost:8000/questions/:id/options/create To create the options of a particular questions
3. http://localhost:8000/options/:id/add_vote To add a vote for a Particular Option
4. http://localhost:8000/questions/:id To get the details about the particular question
5. http://localhost:8000/questions/:id/delete To delete a Particular Question
6. http://localhost:8000/options/:id/delete To delete a particular option

## _Note_

1. A question can’t be deleted if one of it’s options has votes
2. An option can’t be deleted if it has even one vote given to it

## Owner

Faheem Ahmad
