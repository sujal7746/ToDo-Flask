A simple web-based To-Do List application built with Flask, a lightweight Python web framework. This app allows users to add, delete, update, and toggle the completion status of tasks, with a clean and interactive interface. Tasks are stored in a SQLite database using Flask-SQLAlchemy.<br/>

**Features**<br />
Add Tasks: Enter a task and add it to your list.<br />
Delete Tasks: Remove tasks you no longer need.<br />
Update Tasks: Edit task titles and mark them as completed.<br />
Toggle Completion: Quickly mark tasks as done or undone.<br />
Persistent Storage: Tasks are saved in a SQLite database (todos.db).<br />
Simple Styling: Basic CSS for a user-friendly look.<br />


**Requirements**<br />
Python 3.x<br />
Flask (pip install flask)<br />
Flask-SQLAlchemy (pip install flask-sqlalchemy)<br />

**Setup Instructions**<br />
Follow these steps to get the project running on your machine.<br />
1. Clone or Download<br />
If using Git, clone the project:<br />
git clone https://github.com/sujal7746/ToDo-Flask <br />
cd Flask-ToDo-List<br />
Or download the project files and navigate to the todo_flask directory.<br />
2. Install Dependencies<br />
Ensure you have Python installed (python --version).<br />
Install the required packages:<br />
pip install flask flask-sqlalchemy<br />
3. Verify Project Files<br />
Ensure you have:<br />
app.py<br />
static/style.css<br />
templates/index.html<br />
templates/update.html<br />
4. Run the Application<br />
In your terminal, run:<br />
python app.py<br />
Open your browser and go to http://127.0.0.1:5000/.<br />

**Usage**<br />
Add a Task:<br />
Type a task in the input box and click "Add".<br />
Toggle Completion:<br />
Click "Done" to mark a task as complete (or "Undo" to revert).<br />
Edit a Task:<br />
Click "Edit" to update the task title or completion status.<br />
Delete a Task:<br />
Click "Delete" to remove a task from the list.<br />
Tasks persist in todos.db until deleted, even if you restart the app.<br />

**Code Overview**<br />
app.py:<br />
Sets up Flask and SQLAlchemy.<br />
Defines the Task model and routes for adding, deleting, updating, and toggling tasks.<br />
templates/index.html:<br />
Displays the task list and form to add tasks.<br />
templates/update.html:<br />
Form for editing a task’s title and completion status.<br />
static/style.css:<br />
Basic styling for buttons, list items, and completed tasks.<br />
Main Interface: Task list with add/delete options.<br />
Update Page: Editing a task.<br />


**Troubleshooting**<br />
Error: "No module named flask"<br />
Run pip install flask flask-sqlalchemy again.<br />
App Doesn’t Start:<br />
Ensure you’re in the todo_flask directory and running python app.py.<br />
Database Issues:<br />
Delete todos.db and restart the app to reset the database.<br />
