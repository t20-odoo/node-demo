# NodeJS - The Complete Guide (MVC, REST APIs, GraphQL, Deno)

_Master Node JS & Deno.js, build REST APIs with Node.js, GraphQL APIs, add Authentication, use MongoDB, SQL & much more!_

## Section 1: Introduction

#### 1. Introduction

#### 2. What is Node.js?

_What is a Node.js_ <https://nodejs.org/en>

Node.js® is a free, open-source, cross-platform JavaScript runtime environment that lets developers create servers, web apps, command line tools and scripts.

#### 4. Installing Node.js and Creating our First App

`node -v`: Displays the currently installed version of Node.js.

#### 9. Working with the REPL vs Using Files

**REPL (Read-Eval-Print Loop)**: An interactive shell for running and testing Node.js code line by line.

---

## Section 2: Optional: JavaScript - A Quick Refresher

#### 11. Module Introduction

#### 12. JavaScript in a Nutshell

#### 13. Refreshing the Core Syntax

#### 14. let & const

#### 15. Understanding Arrow Functions

#### 16. Working with Objects, Properties & Methods

#### 17. Arrays & Array Methods

#### 18. Arrays, Objects & Reference Types

#### 19. Understanding Spread & Rest Operators

#### 20. Destructuring

#### 21. Async Code & Promises

#### 22. Template Literals

#### 23. Wrap Up

#### 24. Useful Resources & Links

<https://academind.com/learn/javascript>

---

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

---

## Section 3: Understanding the Basics

#### 25. Module Introduction

#### 26. How The Web Works

_How the web works_

- _HTTP_: Hyper Text Transfer Protocol, A protocol for transferring data which is understood by browser and server
- _HTTPS_: Hyper Text Transfer Protocol Secure, HTTP + Data encryption (During transmission)

#### 27. Creating a Node Server

_Core modules_

- **http:** A Node.js module used to create HTTP servers and handle HTTP requests and responses.
- **https:** A Node.js module like http, but supports secure communication using SSL/TLS.
- **fs:** The Node.js File System module that enables interaction with the file system, such as reading and writing files.
- **path:** A Node.js module for working with file and directory paths in a platform-independent way.
- **os:** A Node.js module that provides information about the operating system, such as memory, CPU, and platform details.

#### 28. The Node Lifecycle & Event Loop

- The Node.js event loop is a single-threaded mechanism that handles asynchronous operations by offloading tasks and executing their callbacks in phases to ensure non-blocking I/O.
- Keeps on running as long as there are event listeners registered

#### 29. Controlling the Node.js Process

#### 30. Understanding Requests

#### 31. Sending Responses

#### 32. Request & Response Headers

#### 33. Routing Requests

#### 34. Redirecting Requests

#### 35. Parsing Request Bodies

#### 36. Understanding Event Driven Code Execution ?????
