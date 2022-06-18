# Questions And Answers

## Question No 1

### Explain the use of JavaScript ( or What you can do using a JavaScript)

JavaScript is a light-weight object-oriented programming language that is used by several websites for scripting the webpages. It is an interpreted, full-fledged programming language. JavaScript enables dynamic interactivity on websites when it is applied to an HTML document.

JavaScript helps the users to build modern web applications to interact directly without reloading the page every time. JavaScript is commonly used to dynamically modify HTML
and CSS to update a user interface by the DOM API. It is mainly used in web applications.

I can do alot of stuff with JavaScript.

1. Web Applications
2. Web Development
3. Mobile Applications
4. Server Applications
5. Web Servers

## Question No 2

### What is the difference between client-side and server-side?

Client-side means that the processing takes place on the user’s computer. It requires browsers to run the scripts on the client machine without involving any processing on the server.

Server-side means that the processing takes place on a web server.

This processing is important to execute the tasks required by the user on the web. Since the client-side script is executed on the client’s computer, it is visible to the client. On the other hand, the server-side script is executed in the server; hence, it is not visible to the users.

## Question No 3

### What is Nodejs?

Node.js is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.

## Question No 4

### Explain Scope in JavaScript?

Scope in JavaScript refers to the current context of code, which determines the accessibility of variables to JavaScript. The two types of scope are local and global:

Global variables are those declared outside of a block
Local variables are those declared inside of a block

```// Initialize a global variable
var species = "human";
 
function transform() {
  // Initialize a local, function-scoped variable
  var species = "werewolf";
  console.log(species);
}

// Log the global and local variable
console.log(species);
transform();
console.log(species); 
```

## Question No 5

### JavaScript is asynchronous or synchronous

JavaScript is a synchronous, blocking, single-threaded language. That just means that only one operation can be in progress at a time.

## Question No 6

### JavaScript is a synchronous, blocking, single-threaded language. That just means that only one operation can be in progress at a time

JavaScript is a synchronous, blocking, single-threaded language. That just means that only one operation can be in progress at a time.

Javascript is a single threaded language. This means it has one call stack and one memory heap.

JavaScript is a single-threaded, non-blocking, asynchronous, concurrent programming language with lots of flexibility. Hold on a second – did it say single-threaded and asynchronous at the same time? If you understand what single-threaded means, you’ll likely mostly associate it with synchronous operations.

## Question No 7

### Explain DOM in your own word

The Document Object Model (DOM) is a programming API for HTML and XML documents. It defines the logical structure of documents and the way a document is accessed and manipulated. In the DOM specification, the term "document" is used in the broad sense - increasingly, XML is being used as a way of representing many different kinds of information that may be stored in diverse systems, and much of this would traditionally be seen as data rather than as documents. Nevertheless, XML presents this data as documents, and the DOM may be used to manage this data.

With the Document Object Model, programmers can create and build documents, navigate their structure, and add, modify, or delete elements and content. Anything found in an HTML or XML document can be accessed, changed, deleted, or added using the Document Object Model, with a few exceptions - in particular, the DOM interfaces for the internal subset and external subset have not yet been specified
