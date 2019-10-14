# Byte-Size Track

Virtually everything in this tutorial will be based off of material from the Mozilla Development Network (MDN). Mozilla is the organization that originally created JavaScript, as well as the Firefox browser, and the MDN is an essential guide for everything web dev and JavaScript.

Some things to keep in mind:

- Don't work for the technology, make it work for you. Envision what you want from an application, break down that idea into smaller ideas, then search how to implement and connect those ideas.
- Concepts in programming usually have real-world analogs: language, syntax, object, document, etc. Think about these concepts through the lens of their real-world counterparts to understand them at a high level.
	- Also a lot of the logical concepts come from formal logic and math (e.g., conditionals, sums/loops, etc.)
	- This is kind of good to understand but mostly it's just neat
- Modern web development has a bunch of abstractions that build on older concepts. It helps to understand those older concepts to understand how and why what we're using works the way it does.

## Intro to JavaScript

Follow along using the JSFiddle [here](https://jsfiddle.net/5pb3xvn8/).

### Front-end overview

#### HTML

- "Hypertext Markup Language"
- HTML is the markup language that lets us define the outline of this web document
- Think of it as outlining an essay or letter
- `<head>` tag contains the header: the webpage title, any data about the document itself, etc.
	- Essay metaphor: MLA header, date, title, etc.
- `<body>` tag contains the body of the page
		- Essay metaphor: the body of your essay
- Other tags:
	- `<h1>`: header
	- `<p>`: paragraph
	- `<div>`: "division" of document; outlines snippet we want to refer to later
	- `<label>`: label for text box
	- `<input>`: text box
- `class` attribute: unique name that lets us refer to an element later

#### CSS

- "Cascading Style Sheets"
- CSS is the markup language that lets us describe how we want the components of that outline to appear
- Refer to types of elements (e.g., `html`, `body`) by their name
- Refer to classes with a `.` followed by the class name (e.g.,  `.lastResult`, `.form`)
- There's a bunch of properties to choose from, more than anyone can keep in their head
	- Look up elements and concepts on MDN or CSS Tricks
- Can be written in an HTML file using the `<style>` tag or in its own file and referenced

### Back-end overview

- Source: [A first splash into JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash)

### Quirks of JavaScript

- Source: https://www.telerik.com/blogs/seven-javascript-quirks-i-wish-id-known-about
- Equality: double-equals vs. triple-equals
	- Double-equals: compares the values
	- Triple-equals: compares the values AND the types
	- A byproduct of JS's notorious [type coercion](https://www.freecodecamp.org/news/js-type-coercion-explained-27ba3d9a2839/)
- Anonymous function (`function` keyword) vs. arrow function
	- Anonymous function has a `this` object, arrow function does not
	- A bit advanced for now, but keep this in mind
	- If one isn't working, use the other one and hope it works
- Server-side JS vs. "browser-side" JS
	- "Browser-side": runs in-browser using `<script>` tag; "older" method of writing JS
	- Server-side JS: runs on the server, not the browser; uses Node engine
		- Sometimes (imo, often) confusing conceptially
		- Basically magic

### Project time!

- Source: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Silly_story_generator
	- [Source code](https://jsfiddle.net/wmb3217r/)
	- [Raw text](https://raw.githubusercontent.com/mdn/learning-area/master/javascript/introduction-to-js-1/assessment-start/raw-text.txt)

### Resources

- MDN:
	- Various guides (e.g., variables, operators, arrays): [JavaScript First Steps](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps)
	- [What is JavaScript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
	- [What went wrong? Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)
- Etc.:
	- [Span and div: Wikipedia](https://en.wikipedia.org/wiki/Span_and_div)

## Creating a web app: back-end

### High-level concepts

- How to talk to a web app:
	- Two parties: client (server) and server
	- User is the one making the requests, server is the one sending the responses
	- HTTP is the medium used to send messages between the two
- How a web app works:
	- MVC: model, view, controller
	- Model:
	- View:
	- Controller:
- Resources:
	- [Client-server model: Wikipedia](https://en.wikipedia.org/wiki/Client%E2%80%93server_model)
	- [MVC architecture: Wikipedia](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)

### Express: Creating a server



### HTTP: Talking to people



## Creating a web app: front-end

- 
