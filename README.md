# Social Network API

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)

## Description
This API uses MongoDB which is a NoSQL database. The purpose of this is for the website to be able to handle large amounts of unstructured data.

To view a demonstration, please click [here](https://app.castify.com/view/b37c051b-6f25-4829-b858-86f46079b524)

### Installation
Run `npm install` first to install dependancies. Next run `npm start` to begin.

### Usage
After running `npm start`, The server will start and the mongoose models will be synced to the MongoDB database. Then, open Postman to API GET routes for users and thoughts to see the data, in JSON format, for each these routes. Then test API POST, PUT, and DELETE routes to create, update, and delete users and thoughts in your database. Lastly, when testing API POST and DELETE routes in Postman, you are able to create and delete reactions to thoughts and add and remove friends to a user's friend list.

## Questions
If you have any questions please contact me at [gkaramanis@knights.ucf.edu](mailto:gkaramanis@knights.ucf.edu)
