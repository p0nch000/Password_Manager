# Password_Manager
The program is a Python password manager using Fernet encryption. It creates/loads a master key, manages a secure password file, adds/retrieves passwords for sites. Securely handles user input and clears sensitive data from memory. Simple command-line interface with basic menu options.

# How to use

To use the password manager program, follow these steps:

Install Required Library:
Before running the program, ensure you have the cryptography library installed. If you don't have it installed already, open your terminal or command prompt and run the following command:
pip install cryptography

Download the Code:
Download the Python script containing the password manager code and save it as a .py file, e.g., password_manager.py.

Run the Program:
Open your terminal or command prompt and navigate to the directory where you saved the password_manager.py file.

Execute the Program:
Type the following command and press Enter to run the program:
python password_manager.py

Using the Password Manager:
Once the program is running, it will display a menu with various options. You can interact with the password manager using the listed options:

(1) Create a new key: To generate a new master key for encryption.
(2) Load an existing key: To load an existing master key from a file.
(3) Create new password file: To create a new password file and populate it with initial passwords.
(4) Load existing password file: To load an existing password file.
(5) Add a new password: To add a new site and its corresponding password to the password file.
(6) Get a password: To retrieve a password for a specific site.
Enter the respective option number and follow the prompts to perform the desired operation.

IMPORTANT: Make sure to handle your master key securely and avoid sharing it with others, as it is critical for the security of your passwords. Additionally, never save the master key in plaintext or share it via unencrypted channels. Keep backups of your password file in secure locations.
