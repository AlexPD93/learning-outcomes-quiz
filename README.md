# FAC learning outcomes quiz

## Git 

### Why do we use Git?

Not sure

### What’s the difference between Git and GitHub?

Not sure

### What happens when you clone a repository?

It makes that repository on your local machine. 

### What happens when we do git pull origin main?

It pulls everything from the main on Github onto your local machine

### How do we create a new branch on our local machine?

git checkout -b branch-name.

### How do we control which changes will be included in the next commit?

When using git add, you only add the files you want to be included in the commit.

### When might git add . be inappropriate?

When you have only worked on one file but you are including all files in a commit. 

### How do we make sure our local changes don’t conflict with main?

We create a new branch to work on.

What does
git push origin [branch-name]
do?

It pushes that branch on Github. You can then create a PR on Github so other people can review what you have done. 

### Why do we make pull requests instead of just changing main directly?

So we can review what the other person has changed and flag anything we think might not be good. 

### Why should you review your teammates’ pull requests?

To check for any mistakes, things you think won't work e.t.c.

## HTML 

### Why is accessibility important?

Because it ensures everyone is able to use what you create.

### How can you quickly find simple accessibility problems?

With lighthouse and using the a11y checklist. 

### What is semantic HTML?

Semantic HTML is tags that clearly define what they are i.e 'header.'

### Why is it important to use the “correct” semantic element?

Because certain elements will have particular attributes that are important.

### What is the form element used for?

It is used to create a form. It is essentially the parent element. 

## Css 

### How would you use CSS variables to make a reusable colour palette?

You would create them in the :root element and give each colour a name. Later you will access them with 'var(colour name).'

### How would you use flexbox to make elements sit on a single line?

Flex direction: row

### How would you use grid to make a layout that automatically adds columns as the screen gets wider?

Not sure.

### Why is it important to create a responsive design?

So what you are creating looks good on all sizes of screen.

### How would you structure your CSS to make it “mobile-first”?

Add a media query with min-width.

## Javascript

### Why should we avoid using var to define variables?

It is outdated and unclear on whether it is a variable that will be redefined later.

### How might you make a long, complex chunk of code easier to read?

* Add comments.

* Try to refactor the code. 

* Think if there are multiple things being done. If so try to split the code into more than one function. 

### What is a “callback”?

A function passed into another function as an argument.

## Array methods 

### How would you use array.map() to create a new array with transformed values?

arr.map(num => num + 1)

### How would you use array.filter() to create a new array with certain values removed?

arr.filter(word => word.length > 2)

### How would you use array.find() to get a single value from an array?

arr.find(num => num > 5)

## Promises and fetch 

### What is a promise?

?

### How do promises help manage asynchronous code?

?

### What does a promise’s .then method return?

A promise that allows method chaining.

### How could you chain promises together to avoid “callback hell”?

Nested .then.

### How would you handle a fetch request that failed to get a response from the server?

?

### How would you handle a fetch request that received a 404 response from the server?

Create an error message. 

## HTTP 

### What is an HTTP request?

### What kind of request is sent when you click a link in your browser?

### What kind of request is sent when you submit a form in your browser?
### What is an HTTP response?
### What does the status code of an HTTP response tell us?
### What are some common status codes?
### What are HTTP methods for?
### What kind of request should have a GET method?
### What kind of request should have a POST method?
### What kind of request should have a PUT method?
### What kind of request should have a DELETE method?
### What is the “body” of an HTTP request for?
### What is the “body” of an HTTP response for?

## DOM 
### How would you get a reference to a DOM element in your JS?
### How would you get references to multiple DOM elements at once in your JS?
### How would you update properties of a DOM element?
### What’s the difference between a “property” and an “attribute”?
### What are some different ways to add content inside a DOM element?
### When might the <template> element be useful?
### What are the different ways to add event handlers to elements?
### Why is addEventListener the safest way to add an event handler?
### How can you access submitted form values in your JS?

## Testing 

### Why are tests useful?

They allow you to check if everything is working as it should in your code. 

### What is the difference between unit and integration tests?

### What kind of code is easier to test?

### Why should your tests be isolated from each other?

So they don't have to rely on one another. If they did there is a higher chance something will go wrong. 

### What is Test Driven Development (TDD)?

When you write tests first then the code. 

### When might TDD be a useful process to follow?

## Debugging 

### What process would you take to find out why your code isn’t working?

* Check console.log

### What tools do JS/dev tools have to help debug your code?

### At what point should you ask for someone else’s help?

When you have used all tools/processes you can think of and are still stuck. 
