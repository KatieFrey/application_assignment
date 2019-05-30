# Assignment

## How To Run The Application

1.) Fork the repository and clone it to your local machine. Within your terminal, choose a directory to clone your assignment repository and enter 'git clone https://github.com/{username}/application_assignment.git'. Enter into your project (cd application_assignment) and open into your text editor.

2.) Install your dependencies. Inside your terminal (make sure you're in the same directory) use 'npm install' to install npm packages already listed as dependencies in your package.json and 'npm install random-movie-quotes' to install the movie quotes packages. Add node_modules into your .gitignore file if it doesn't exist already.

3.) To debug the application, first update the server in 'index.js' to require 'random-movie-quotes' and assign it as a constant 'quotes' as its named in the 'get' api route.

ie: const quotes = require("random-movie-quotes");

4.) Change the script in package.json to be able run node on my server.

ie:
"scripts": {
"dev": "node index.js"
}

5.) Finally open up your server by running 'npm run dev' on the terminal, open your browser and type in the url 'localhost:3000' as the port in my server is assigned to 3000.

## Objectives

By the end of this project you will:

- clone a Github project.
- install a npm package.
- debug a piece of code.

## Introduction

Our intern Dan is working on this killer Movie Quotes App that returns a random movie quote. Right now all it does is render a blank screen in the web browser. Fork the repository found here and help Dan fix it.

## Specifications

The finished project:

- loads a new fact when you refresh the page.
- runs with no errors.
- has the readme updated with how to run this web server.

![working app](app.gif)

## Submission Requirements

Please include the url to your forked repository with the fixed webserver in your application to Inclusion's program.

## References

- [Random Movie Quotes NPM Docummentation](https://www.npmjs.com/package/random-movie-quotes)
- [How to contribute to a github project](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/)
