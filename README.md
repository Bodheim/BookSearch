# Book Search Engine

## Table of Contents

[Description](#description)  
 [Installation](#installation)  
 [Deployed](#deployed)  
 [Usage](#usage)  
 [Contributing](#contributing)  
 [Questions](#questions)  
 [License](#license)

## Description

My assignment is emblematic of the fact that most modern websites are driven by two things: data and user demands. This shouldn't come as a surprise, as the ability to personalize user data is the cornerstone of real-world web development today. And as user demands evolve, applications need to be more performant.

This week, I was given starter code with a fully functioning Google Books API search engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server. The app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API. It's already set up to allow users to save book searches to the back end.

To complete the build, I needed to do the following:

1. Set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.

2. Modify the existing authentication middleware so that it works in the context of a GraphQL API.

3. Create an Apollo Provider so that requests can communicate with an Apollo Server.

4. Deploy your application to Heroku with a MongoDB database using MongoDB Atlas. Use the [Deploy with Heroku and MongoDB Atlas](https://coding-boot-camp.github.io/full-stack/mongodb/deploy-with-heroku-and-mongodb-atlas) walkthrough for instructions.

## Deployed

I completed this assignment and the deployed link is below:  
https://floating-castle-98205.herokuapp.com/saved

## Installation

Run

> npm i & npm install @apollo/client

to pull in dependencies.

## Usage

Run

> npm run build and git push heroku master

to run the program.

## Contributing

Contact abby.castelow@gmail.com to a get a pull request.

## Questions

Contact abby.castelow@gmail.com for any questions.  
 Github username: Bodheim  
 Link to my github profile: https://github.com/Bodheim

## License

MIT

https://opensource.org/licenses/MIT  
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
