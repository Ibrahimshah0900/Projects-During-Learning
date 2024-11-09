
# User Management System

This is a simple User Management System that allows you to add, update, delete, and query users. User data, such as `username`, `email`, and `preferences`, is stored in a JSON file. This project is designed as a lightweight system focusing on managing structured data using JSON in Python.

## Project Features

- **Add User**: Adds a new user to the JSON file, ensuring unique usernames and emails.
- **Update User**: Updates an existing user’s information based on their username.
- **Delete User**: Removes a user from the JSON file by their username.
- **Query User**: Finds and displays user information based on either username or email.

## Technologies Used

- **Python**: For core functionality and JSON handling.
- **JSON**: Used as the data store for user information.

## Project Structure

- **Main Functions**:
  - `add_user`: Adds a new user with validation for unique username and email.
  - `update_user`: Updates user information such as preferences.
  - `delete_user`: Deletes a user after confirming existence.
  - `query_user`: Allows you to search for a user by username or email.

## Code Examples

Here’s how you can use the functions in this project:

```python
# Define the path to the JSON file
file_path = 'users.json'

# Add a new user
print(add_user(file_path, 'john_doe', 'john@example.com', {'theme': 'dark', 'notifications': True}))

# Query user information
print(query_user(file_path, 'john_doe'))

# Update user preferences
print(update_user(file_path, 'john_doe', {'theme': 'light'}))

# Delete a user
print(delete_user(file_path, 'john_doe'))
```

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/User-Management-System.git
   ```

2. **Install Requirements**:
   - This project requires no external dependencies, as it only uses Python’s built-in `json` and `re` libraries.

3. **Run the Code**:
   - Run the script in a Python environment (e.g., Jupyter Notebook or any Python IDE).

## Usage Tips

- Make sure the `users.json` file is in the same directory as your script, or adjust `file_path` accordingly.
- The script will automatically create `users.json` if it does not exist.
- You can add, update, delete, or query users by calling the respective functions.

