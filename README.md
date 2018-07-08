# 21 Savage
This project is a full-stack webpage that allow users to leave a message, like for thumbs up or down, and even delete the comment.

## How It's Made:

**Tech used:** HTML, CSS, JavaScript, Node-JS, MongoDB, Express

This project runs with an index.ejs file, a server.js file and client side files. The object of this project was to get the thumbs up and thumbs down button work. Using a global var at the top to find all thumbs down icon on the DOM and adding an event listener for when the thumbs down icon is clicked. When the the thumbs down icon is clicked, we set 3 const variables, name, msg and the the icon being clicked so that we can pass the JSON object to our server.js and find in our collections that name and msg corresponding to the same thumbs down being clicked and updating the database to add a +1 count to it and then rendering it back to the DOM to display the update.

## Lessons Learned:

I learned how to navigate through the HTMLcollections to properly target the correct element tag on the DOM, so that I can alter its data with Javascript.

## Installation

1. Clone repo
2. run `npm install`

## Usage

1. run `node server.js`
2. Navigate to `localhost:3000`

