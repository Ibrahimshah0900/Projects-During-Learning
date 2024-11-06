
# To-Do List Application with User Registration

A simple command-line To-Do List application built using Python. This application allows users to register, add tasks, mark tasks as complete, delete tasks, and view their tasks. Task data is stored in a JSON file (`tasks.json`), and user details are saved in a separate JSON file (`user.json`).

## Features

- **User Registration**: Register or load an existing user when starting the app.
- **Task Management**: Add, view, complete, and delete tasks.
- **Task Persistence**: All tasks are stored in `tasks.json`, which persists between app sessions.
- **User Persistence**: User details (name and email) are saved in `user.json`.

## Prerequisites

To run this project, you need:

- Python 3.x

## Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/to-do-list-app.git
   cd to-do-list-app
   ```

2. Ensure you have Python installed by running:
   ```bash
   python --version
   ```

3. Optionally, create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. You're now ready to run the application!

## Usage

1. Run the application by executing:
   ```bash
   python todo.py
   ```

2. The app will ask you to register or load an existing user. If it's your first time, you will be prompted to enter your name and email.

3. Once registered or loaded, you can interact with the application through a simple command-line menu:
 
   To-Do List Application
   1. Add task
   2. View tasks
   3. Complete task
   4. Delete task
   5. Quit
   

4. Choose one of the following options:
   - **1**: Add a new task.
   - **2**: View all tasks.
   - **3**: Mark a task as completed.
   - **4**: Delete a task.
   - **5**: Quit the application.

### Example Workflow:
- **Add a task**: Enter the task description when prompted.
- **View tasks**: The app will display the list of tasks, showing whether they are "Done" or "Not Done."
- **Complete a task**: Select a task by its number to mark it as complete.
- **Delete a task**: Select a task by its number to remove it from the list entirely.

## File Structure


todo.py              # Main Python script for the to-do list app
tasks.json           # JSON file to store tasks
user.json            # JSON file to store user details (name and email)
README.md            # This readme file
```

## Code Overview

- **`todo.py`**: Contains the core logic of the application including user registration, task management, and command-line interface.
- **`tasks.json`**: Stores tasks data, including task descriptions and their status (done or not done).
- **`user.json`**: Stores user details like name and email.

## How It Works

1. **User Registration**:
   When the application starts, the user is asked to enter their name and email to create a new user. If a user already exists, their details are loaded from the `user.json` file.

2. **Task Management**:
   - Tasks are stored in `tasks.json`.
   - Users can add, view, mark tasks as completed, or delete tasks.

3. **Task Deletion**:
   - When a task is deleted, it is completely removed from the `tasks.json` file.

## Contributions

Feel free to fork the repository and make changes. If you want to contribute, submit a pull request! Ideas for improvement:
- Add a due date to tasks.
- Add priority levels (e.g., High, Medium, Low).
- Improve error handling for invalid inputs.






