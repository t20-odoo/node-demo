# node-demo

## Introduction

_What is a Node.js_ <https://nodejs.org/en>

Node.js® is a free, open-source, cross-platform JavaScript runtime environment that lets developers create servers, web apps, command line tools and scripts.

`node -v`: Displays the currently installed version of Node.js.

**REPL (Read-Eval-Print Loop)**: An interactive shell for running and testing Node.js code line by line.

## JavaScript - A Quick Refresher

**Callback:** A callback is a function passed as an argument to another function

**Synchronous:** executes code line by line, blocking further execution until the current task completes.

**Asynchronous:** allows code to run without blocking, enabling tasks like API calls or timers to complete in the background.

**Promises:** A Promise is an Object that links Producing code and Consuming code

- _Producing code_ is code that can take some time
- _Consuming code_ is code that must wait for the result

**Async/Await:** async and await make promises easier to write

- _async_ makes a function return a Promise
- _await_ makes a function wait for a Promise

<https://academind.com/tutorials>

<https://academind.com/tutorials/reference-vs-primitive-values>

<https://academind.com/tutorials/this-keyword-function-references>

<https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/constructor>

## Node.js Basics

_How the web works_

- _HTTP_: Hyper Text Transfer Protocol, A protocol for transferring data which is understood by browser and server
- _HTTPS_: Hyper Text Transfer Protocol Secure, HTTP + Data encryption (During transmission)

_Core modules_

- **http:** A Node.js module used to create HTTP servers and handle HTTP requests and responses.
- **https:** A Node.js module like http, but supports secure communication using SSL/TLS.
- **fs:** The Node.js File System module that enables interaction with the file system, such as reading and writing files.
- **path:** A Node.js module for working with file and directory paths in a platform-independent way.
- **os:** A Node.js module that provides information about the operating system, such as memory, CPU, and platform details.

**Event Loop:**

- The Node.js event loop is a single-threaded mechanism that handles asynchronous operations by offloading tasks and executing their callbacks in phases to ensure non-blocking I/O.
- Keeps on running as long as there are event listeners registered

_Creating a node server_ ?????

36. Understanding Event Driven Code Execution ?
