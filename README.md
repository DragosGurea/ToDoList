# ToDoList
This is a simple ToDoList application developed in Java. The application allows users to manage their tasks by adding new tasks, marking them as completed, and clearing finished tasks. The graphical user interface (GUI) is built using Java Swing.

## Features

- *Add tasks:* Users can add new tasks to the list by clicking the "Add Task" button.
- *Mark tasks as completed:* Users can mark tasks as completed by clicking the "Done" button next to each task. Completed tasks are visually indicated by a green background.
- *Clear finished tasks:* Users can remove completed tasks from the list by clicking the "Clear finished tasks" button.
- *Task numbering:* Each task is assigned a number based on its position in the list, and the numbering is updated automatically when tasks are added or removed.

## Files

The project consists of the following files:

- `AppFrame.java`: The main class that creates the application's frame and initializes the UI components.
- `ButtonPanel.java`: A panel class that contains the "Add Task" and "Clear finished tasks" buttons.
- `List.java`: A panel class that displays the list of tasks.
- `Task.java`: A panel class that represents an individual task item.
- `TitleBar.java`: A panel class that displays the title of the application.
- `ToDoList.java`: The entry point of the application.

## Getting Started

To run the ToDoList application, follow these steps:

1. Make sure you have Java installed on your system.
2. Compile all the Java source files in the project using the Java compiler.
3. Run the ToDoList class, which contains the main method.

## Usage

1. Upon launching the application, a window will appear showing the title "To Do List" at the top.
2. Below the title, there is a list of tasks displayed as individual items.
3. To add a new task, click the "Add Task" button at the bottom.
4. A new task item will appear in the list, and you can enter the task details.
5. To mark a task as completed, click the "Done" button next to the task. The task will turn green to indicate completion.
6. To remove completed tasks from the list, click the "Clear finished tasks" button.
7. The task numbering will be updated automatically after adding or removing tasks.

## Future Improvements

Here are some possible enhancements for the ToDoList application:

- Implement persistence: Add the ability to save tasks to a file or a database so that the tasks can be retained even after closing the application.
- Task prioritization: Allow users to assign priorities or due dates to tasks and implement sorting or filtering based on these criteria.
- Task editing: Enable users to edit task details, such as the task name or description, directly within the application.
- User authentication: Implement user accounts to enable multiple users to have their own separate task lists.
- Improved UI: Enhance the visual appearance of the application by using custom icons, themes, or animations.
