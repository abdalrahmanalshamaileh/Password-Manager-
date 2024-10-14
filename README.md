# Password Manager

A simple **Password Manager** created using Python and the Tkinter library. It allows users to generate secure passwords, save them, and copy the password to the clipboard for easy use. The passwords, along with the website and email/username, are stored in a text file.

## Features
- **Password Generation**: Generate a random password consisting of letters, numbers, and symbols.
- **Clipboard Integration**: Automatically copy the generated password to the clipboard.
- **Data Storage**: Save website, email/username, and password entries to a text file.
- **Form Validation**: Checks that all fields are filled before saving the data.

## Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/password-manager.git
    ```
2. **Install dependencies**: This project only requires Python, as the libraries used (Tkinter, random, pyperclip) come pre-installed with Python.
   
3. **Ensure the logo is available**: Place a `logo.png` file in the project directory. You can use any image of your choice as a logo, or simply remove the logo-related code if you don't need it.

4. **Run the project**:
    ```bash
    python main.py
    ```

## How to Use
1. **Generate Password**: Click the "Generate Password" button to create a secure, random password.
2. **Fill Details**: Enter the website, email/username, and the generated password will be added automatically to the password field.
3. **Save Entry**: Click the "Add" button to save the details to a file named `data.txt`.
4. **Clipboard**: The generated password is automatically copied to the clipboard for quick access.

## File Structure
- `main.py`: The main script that runs the password manager.
- `logo.png`: The image displayed in the app window (optional).
- `data.txt`: The file where all website, email, and password entries are stored.

## Example Entry in `data.txt`

maybe you can make Future Enhancements:
- Add functionality to retrieve and search for stored passwords.
- Encrypt the password data file for better security.
- Create a more advanced UI with password strength indicators.
