Task Tracker CLI
A simple command-line application to track and manage tasks using Node.js.  
You can add, update, delete, and mark tasks as done or in progress — all from your terminal.

Features
Add new tasks
Update existing tasks
Delete tasks
Mark tasks as "todo", "in-progress", or "done"
List all tasks
Filter tasks by status (todo, in-progress, done)
Saves all tasks in a local `tasks.json` file

Usage Examples
Add a Task
node task.js add "Buy groceries"

Update a Task
node task.js update 1 "Buy groceries and cook dinner"
# Output: Task 1 updated successfully.

List all tasks
node task.js list   

List by Status
node task.js list todo
node task.js list in-progress
node task.js list done

GitHub Repository:https://github.com/Aarif195/task-tracker-cli

