HTML Structure (index.html):
<!DOCTYPE html>: This declaration specifies that the document is an HTML5 document.

<html lang="en">: The root element of the HTML document, which contains all other HTML elements. The lang attribute indicates that the document is in English.

<head> Section:

<meta charset="UTF-8">: Specifies the character encoding of the document as UTF-8.
<meta http-equiv="X-UA-Compatible" content="IE=edge">: Sets the compatibility mode for Internet Explorer to the latest version.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Defines the viewport settings for responsive design.
<title>Task List 2021</title>: Sets the title of the web page displayed in the browser tab.
External Stylesheet:

<link rel="stylesheet" href="main (1).css" />: Links an external CSS stylesheet named "main (1).css" to style the web page.
<body> Element: The main content of the web page resides within the <body> element.

<header> Section: Contains the page header.

<h1>Task List 2021</h1>: Displays the main heading of the page.
Task Entry Form:

<form id="new-task-form">: A form element with the ID "new-task-form" that contains input fields for adding new tasks.
<input type="text" name="new-task-input" id="new-task-input" placeholder="What do you have planned?" />: Text input field where users can enter task descriptions.
<input type="submit" id="new-task-submit" value="Add task" />: Submit button for adding new tasks.
<main> Section: Contains the main content of the web page.

Task List Section:

<section class="task-list">: Defines a section for displaying a list of tasks.
<h2>Tasks</h2>: Subheading for the task list.
Task Container:

<div id="tasks">: A container where tasks will be displayed. Currently empty, but tasks will be dynamically added using JavaScript.
CSS Styles (main (1).css):
The provided CSS code defines the styles and layout of the HTML elements. It includes CSS variables for defining color schemes and styles for various elements like headers, input fields, buttons, and task items.

JavaScript Functionality (main (1).js):
The JavaScript code is responsible for adding functionality to the task list:

It waits for the page to load (window.addEventListener('load', ...) before executing.
It listens for form submission (form.addEventListener('submit', ...) to add new tasks dynamically.
When a task is added, it creates HTML elements for displaying the task description, an edit button, and a delete button.
Edit and delete functionality is also implemented, allowing users to edit task descriptions and delete tasks from the list.# To-do-list
