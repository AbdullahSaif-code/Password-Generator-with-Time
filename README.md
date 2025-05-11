# Password Generator with Time

A command-line password manager that generates, encrypts, stores, retrieves, deletes, and exports passwords with time of generation. Passwords are securely encrypted and saved in a CSV file.

## Features

- Generate strong passwords with customizable options (length, case, special characters)
- Encrypt and store passwords with timestamp and label
- Retrieve and decrypt passwords by label
- Delete passwords by label
- List all saved passwords
- Export all passwords to a backup CSV
- Open the CSV file directly

## Usage

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Run the main application:
   ```
   python Main.py
   ```

## File Structure

- `App.py`: Handles user input for password generation options
- `C_P_G.py`: Custom password generator with special characters
- `S_P_G.py`: Simple password generator
- `FileHandler.py`: Handles encryption, saving, retrieving, deleting, and exporting passwords
- `Main.py`: Main menu and application logic
- `encryption.key`: Stores the encryption key
- `passwords.csv`: Stores encrypted passwords

## License

This project is licensed under the terms of the [CC0 1.0 Universal License](../LICENSE).