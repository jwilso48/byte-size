# Byte-Size Track

Virtually everything in this tutorial will be based off of material from the Mozilla Development Network (MDN). Mozilla is the organization that originally created JavaScript, as well as the Firefox browser, and the MDN is an essential guide for everything web dev and JavaScript.

Some things to keep in mind:

- Don't work for the technology, make it work for you. Envision what you want from an application, break down that idea into smaller ideas, then search how to implement and connect those ideas.
- Concepts in programming usually have real-world analogs: language, syntax, object, document, etc. Think about these concepts through the lens of their real-world counterparts to understand them at a high level.
		- Also a lot of the logical concepts come from formal logic and math (e.g., conditionals, sums/loops, etc.)
		- This is kind of good to understand but mostly it's just neat

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

## Back-end overview

- Source: [A first splash into JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash)

### Resources

- MDN:
	- [What is JavaScript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
	- [A first splash into JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash)
	- [What went wrong? Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)
- Etc.:
		- [Span and div: Wikipedia](https://en.wikipedia.org/wiki/Span_and_div)

## Creating a web app: back-end

- Express
- Calling an API

## Creating a web app: front-end

- 
