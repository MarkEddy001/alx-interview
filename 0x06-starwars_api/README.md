# 0x06. Star Wars API

# `StarWars_API`
![](https://cdn.vox-cdn.com/thumbor/gHP2IAVuz8lgJHS9Y5UFtij5weI=/1400x0/filters:no_upscale()/cdn.vox-cdn.com/uploads/chorus_asset/file/7855689/Staw.png)

## Description

This project involves interacting with the Star Wars API to fetch and display information about Star Wars characters based on the movie ID provided as an argument. The goal is to retrieve, process, and display the characters in the specified movie using asynchronous programming in JavaScript.

## Concepts Needed

### HTTP Requests in JavaScript
- Understanding how to make HTTP requests to external services using the `request` module or alternatives like `fetch` in Node.js.
- [A Complete Guide to Making HTTP Requests in Node.js](https://nodejs.dev/learn/making-http-requests-with-nodejs)

### Working with APIs
- Understanding the basics of RESTful APIs and how to interact with them.
- Parsing JSON data returned by APIs.
- [Working with APIs in JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction)

### Asynchronous Programming
- Managing asynchronous operations with callbacks, promises, and async/await syntax.
- Handling API response data asynchronously.
- [Asynchronous Programming in JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous)

### Command Line Arguments in Node.js
- Using the `process.argv` array to access command-line arguments passed to a Node.js script.
- [How to Parse Command Line Arguments in Node.js](https://nodejs.dev/learn/nodejs-accept-arguments-from-the-command-line)

### Array Manipulation and Iteration
- Iterating over arrays and manipulating data structures to format and display character names.
- [JavaScript Array Methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted on Ubuntu 20.04 LTS using Node.js (version 10.14.x)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/node`
- A `README.md` file at the root of the project folder is mandatory
- Code should be semistandard compliant. Rules of Standard + semicolons on top. Also as reference: AirBnB style
- All files must be executable
- The length of files will be tested using `wc`
- You are not allowed to use `var`

## Setup

### Install Node 10
```sh
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
$ sudo apt-get install -y nodejs

