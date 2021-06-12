---
title: 'Creating a AWS App Runner Service'
chapter: true
weight: 5
---

## Deploying a simple website to AWS App Runner using Github

For our first example, we are going to create a simple Node.js web server which will serve a simple webpage. The runtime we select to run our web server will be Node.js 12. Our web server will have the following components:

- `index.js` - a Node.js web server
- `package.json` - describes the library dependencies, will be used in the build step

We will build our application to install the library dependencies our web server needs - in this case, the [Express](http://expressjs.com/) library. In order to build our application, we are going to tell AWS App Runner to run “npm build” - this will install the express library as specified our in `package.json` file.

Proceed to the next section to get started creating a new repository on Github which we'll run using AWS App Runner.
