# Password Hashing with Salt

A simple Python program that generates a random salt and hashes a user-entered password using the PBKDF2-HMAC algorithm with SHA-256. This project demonstrates a basic approach to password storage and verification, highlighting the importance of salting and hashing passwords.

## Features

* Generates a random 16-byte salt for each password to prevent rainbow table attacks
* Hashes passwords using PBKDF2-HMAC with SHA-256 and 100,000 iterations to slow down the hashing process
* Allows users to enter multiple passwords without restarting the program
* Prints out the salt and hashed password for each input
* Includes a simple loop feature to continue entering passwords until the user chooses to exit

## Requirements

* Python 3.6 or later
* `hashlib` and `secrets` libraries (included in Python standard library)

## Installation

1. Clone the repository: `git clone https://github.com/your-username/password-hashing.git`
2. Navigate to the project directory: `cd password-hashing`
3. No additional installation required, as this project uses only standard Python libraries

## Usage

1. Run the program: `python password_hashing.py`
2. Enter a password when prompted (or type 'quit' to exit)
3. The program will generate a random salt and hash the password using PBKDF2-HMAC with SHA-256
4. The salt and hashed password will be printed out for each input

## Example Output
