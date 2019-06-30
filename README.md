ReactDOM has a function called render, which takes two arguments: the React element to be rendered to the screen (hey, we have that already!), and the HTML element it will be rendered inside.
Then, in our ReactDOM.render function, we’ll pass in the React element, and then use document.getElementById to grab our new div.
To do:
* yarn add webpack@3.5.4
* node_modules/.bin/webpack src/index.js public/bundle.js