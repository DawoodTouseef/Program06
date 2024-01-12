 # To-Do List Application

This is a simple to-do list application built using AngularJS. It allows users to add, edit, and delete tasks.

## Prerequisites

To run this application, you will need:

* Node.js and npm installed
* AngularJS installed

## Installation

To install the dependencies, run the following command in the project directory:

```
npm install
```

## Running the Application

To run the application, run the following command in the project directory:

```
ng serve
```

This will start the AngularJS development server and open the application in your default browser.

## Code Overview

The application consists of the following files:

* `index.html`: This is the main HTML file of the application. It includes the AngularJS library and the script file.
* `script.js`: This is the JavaScript file of the application. It contains the AngularJS controller and the functions that handle the tasks.
* `style.css`: This is the CSS file of the application. It contains the styles for the application.

## AngularJS Controller

The AngularJS controller is defined in the `myController` function. It contains the following properties and methods:

* `tasks`: This is an array of objects that represent the tasks. Each task object has a `name` property that represents the name of the task.
* `newTaskName`: This is a string that represents the name of the new task.
* `editingTask`: This is a boolean that represents whether a task is being edited.
* `editedTaskName`: This is a string that represents the name of the task being edited.

The controller also contains the following methods:

* `addTask()`: This method adds a new task to the `tasks` array.
* `editTask(task)`: This method sets the `editingTask` property to `true` and the `editedTaskName` property to the name of the task being edited.
* `saveTask()`: This method saves the changes to the task being edited and sets the `editingTask` property to `false`.
* `cancelEdit()`: This method cancels the changes to the task being edited and sets the `editingTask` property to `false`.

## HTML Template

The HTML template is defined in the `index.html` file. It contains the following elements:

* A header with the title "To-Do List".
* A list
