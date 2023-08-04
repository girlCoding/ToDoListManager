# ToDoListManager
The ToDoListManager API will allow users to manage their to-do lists. Users can add tasks, mark tasks as completed, and retrieve the list of tasks.

Features:

Add Task: Allows users to add a new task to their to-do list.
Mark Task as Completed: Lets users mark a task as completed.
Get All Tasks: Returns a list of all tasks, including their details (task name, description, status, etc.).
Filter Tasks: Provides the ability to filter tasks based on their status (completed or not completed).
Remove Task: Allows users to remove a task from their list.
Classes and Methods:

Task class:

Properties: taskId, taskName, description, isCompleted
Getters and setters for each property
ToDoListManager class:

ArrayList<Task> tasks: Maintain a list of tasks.
addTask(Task task): Add a new task to the list.
markTaskAsCompleted(int taskId): Mark a task as completed based on its ID.
getAllTasks(): Retrieve a list of all tasks.
getCompletedTasks(): Retrieve a list of completed tasks.
getPendingTasks(): Retrieve a list of pending (not completed) tasks.
removeTask(int taskId): Remove a task from the list based on its ID.
