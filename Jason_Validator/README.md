# JSON Data Validator

This Python tool validates a JSON file against a predefined schema to ensure its structure is correct.

## Technologies Used:
- Python
- json
- jsonschema

## How to Run:
1. Clone the repository.
2. Install the required dependencies:
   ```bash
   pip install jsonschema
   ```
3. Place a JSON file (e.g., `user_profile.json`) in the project directory.
4. Run the script:
   ```bash
   python validate_json.py
   ```

## Example JSON Data:
Here’s an example of a valid JSON file:
```json
{
    "name": "John Doe",
    "email": "johndoe@example.com",
    "age": 30
}
