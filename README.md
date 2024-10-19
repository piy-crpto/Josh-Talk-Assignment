The Task Management App is a powerful and user-friendly application built with React JS designed to help users effectively manage their tasks.

Summary
The Task Dashboard is a React application designed for managing tasks with varying priority levels: High, Medium, and Low. Users can easily add, edit, delete, and prioritize tasks, with all data stored in local storage to ensure persistence across sessions.

Key Features
Task Input: Users can enter a task description and select its priority level.
Edit Tasks: Modify existing tasks and their priority through user-friendly prompts.
Delete Tasks: Remove tasks with a confirmation alert to prevent accidental deletions.


Priority Management: Tasks are categorized into High, Medium, and Low priorities, allowing users to focus on urgent tasks.
Managing Priority Levels
Tasks are assigned priority levels via a dropdown menu during the task creation process. Each task is stored with its corresponding priority, enabling users to filter and view tasks based on urgency. The application utilizes the getTasksByPriority function to organize tasks into their respective sections for easier management.
