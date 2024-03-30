In this project, let's build a Simple Todos app by applying the concepts we have learned till now.

Refer to the image below:

![image](https://github.com/bukka5sandhya/React-Js-Simple-Todos/assets/133884532/8b7382de-4887-439e-a68c-7768b67c7eb3)

https://assets.ccbp.in/frontend/content/react-js/simple-todos-output.gif

Design Files

Click to view

Extra Small (Size < 576px) and Small (Size >= 576px)

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)

Set Up Instructions

Click to view

Download dependencies by running npm install

Start up the app using npm start

Completion Instructions

Functionality to be added

The app must have the following functionalities

Initially, the list of given todos should be displayed with a delete button for each todo

When Delete button of a todo is clicked, then the respective todo should be deleted

The SimpleTodos will consist of the initialTodosList. It consists of a list of todo objects with the following properties in each todo object

Key	Data Type

id	Number

title	String

Components Structure

![image](https://github.com/bukka5sandhya/React-Js-Simple-Todos/assets/133884532/2cd39ffe-b932-4fe5-b0bf-051e88fe6d0f)

Implementation Files

Use these files to complete the implementation:

src/components/SimpleTodo/index.js

src/components/SimpleTodo/index.css

src/components/TodoItem/index.js

src/components/TodoItem/index.css

Quick Tips

Click to view

You can use the cursor CSS property to specify the mouse cursor to be displayed when pointing over an element

  cursor: pointer;

![image](https://github.com/bukka5sandhya/React-Js-Simple-Todos/assets/133884532/48575d17-b7b2-41a8-b1d2-c47f56d56a8c)

You can use the below outline CSS property for buttons and input elements to remove the highlighting when the elements are clicked

  outline: none;

Resources

Colors

Hex: #ffc2a0

Hex: #ffffff

Hex: #ff8542

Hex: #000000

Hex: #ff0b37

Font-families

Roboto

Things to Keep in Mind

All components you implement should go in the src/components directory.

Don't change the component folder names as those are the files being imported into the tests.

Do not remove the pre-filled code

Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
