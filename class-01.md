# NPM 

## Why would you want to run JavaScript code outside of a browser?

>Running javascript inside a browser means you are interacting with Web HTML and CSS which is displayed on a user's screen, on the other hand, running javascript without outside the browser means you are using a node js technology to execute your javascript code 

## What is the difference between a module and a package?

>A module is a single JavaScript file that has some reasonable functionality in the other hand  A package is a directory with one or more modules inside of it and a package

## What does the node package manager do?

>Package managers are charged with the task of finding, installing, maintaining or uninstalling software packages upon the user's command.

## Provide code snippets showing 3 different ways to export a function from a node module

`let arthemtic=module.exports={}`//object

`exports.SimpleMessage = 'Hello world'`//string

`module.exports = function (msg) { `//function

`console.log(msg);`

`};`

ecosystem: is a collection of software packages, libraries, and other resources 

Node.js: an open-source JavaScript runtime environment that executes JavaScript code outside of a web browser:its a software application used to acsses information from the word wide web

V8 Engine:open-source JavaScript engine developed that is used in browsers that is built using c++

module:A set of functions you want to include in your application

package:is any file or directory in the node modules directory that can be loaded by the Node. js 

node package manager (npm):its an open source platform that you can install finshed code and use it in your application 

server:its a place where  which can serve content to users

environment:sets of  tools that you use to building your application

interpreter: JavaScript is an interpreted language because every time a program runs, an interpreted language is translated or interpreted  line by line

compiler: is a software that converts a high-level code scripted by developers to a low-level binary code in machine language.
