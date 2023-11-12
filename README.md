# Simple User Registration and Login System

This is a basic Python program for user registration and login. Users can either create a new account with a randomly generated password or log in with an existing username and password. Passwords are encrypted using a substitution cipher for added security.

## Usage

1. Run the script in a Python environment.

2. Choose one of the following options:
   - **New User (N):** Create a new user account.
   - **Login (L):** Log in to an existing account.
   - **Exit (Q):** Exit the program.

## New User (N)

If you choose to create a new user:
- Enter a unique username.
- Decide whether to generate a random password (y/n).
  - If yes, a password will be generated and displayed.
  - If no, enter your desired password.
- Your account will be created, and the password will be encrypted using a substitution cipher.

## Login (L)

If you choose to log in:
- Enter your username and password.
- If the username and password match an existing account, you will be welcomed.
- If there's an error (e.g., incorrect username or password), an appropriate message will be displayed.

## Exit (Q)

Choose this option to exit the program.

## Notes

- The program uses a substitution cipher for password encryption.
- Each user's information is stored in a dictionary, but currently, the code allows only one user due to dictionary overwriting. Consider updating the code to support multiple users.

