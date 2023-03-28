# What is JavaScript? #

> It was initialy called LiveScript but soon changed to JavaScript because of Java

## Engines ###

Nowadays javascript can run on anything that has a *JavaScript engine*

* [V8](https://v8.dev/)  - Chrome
* [SpiderMonkey](https://spidermonkey.dev/) - Firefox
* [Webkit](https://webkit.org/) - Safari
* Chakra and many others

## in-browser JS ###

Javascript does not provide low-level access to memory or the CPU, because it was created for the browser which do not require it. JavaScript's ablities in the browser are limited to protect the user's safety. The aim is to protect an evil webpage from accessing the private information or harming the user's data


### For instance in-browser JavaScript is able to ✅ ###

* Add new HTML to the page
* Change the existing content and styles
* React to users actions, run on mouse clicks, pointer movements, key presses etc.
* Send requests over the network to remote server, download and upload files
* Get and set cookies, ask questions and show messages to the visitor
* Remember the data on the client-side

### What it isn't ❌ ###

* On a webpage Javascript cannot read/write arbitrary files on the hard disk, copy them or execute programs. It has no direct access to OS functions 
  
  Modern browsers allow it to work with files, but the access is limited and only provided if the user does certain actions, like “dropping” a file into a browser window or selecting it via an `<input>` tag

* Diferent tabs/windows generally do not know about each other. Sometimes they do, for example when one window uses JavaScript to open the other one. 
  
  That's called the "Same Origin policy". To work with that, both pages must agree to share data

## What makes JS unique? ###

* Full integration with HTML/CSS
* Simple things are done simply
* Suported by all major browsers








