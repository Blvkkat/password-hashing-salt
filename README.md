# password-hashing-salt
This program securely hashes a user-provided password using bcrypt, a password hashing function with built-in salting
# Password Hasher 🔒  

## Description  
This program securely hashes user-provided passwords using the **bcrypt** hashing algorithm. It includes automatic **salting** to ensure that the same password never produces the same hash. The hashed password is displayed in hexadecimal format for easy readability.

## Features  
- Uses **bcrypt** for secure password hashing  
- Automatically **generates a salt** for each password  
- Converts the hashed password to **hexadecimal format**  
- Simple **command-line interface** for user input  

## Installation  

### Prerequisites  
- Python 3.x installed  
- `bcrypt` library installed  

### Install bcrypt  
If you haven't installed bcrypt, run:  
```sh
pip install bcrypt
