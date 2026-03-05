# Password Management (Python)

## Description

Password Management is a simple command-line application written in Python that helps users store and manage their passwords securely. The program encrypts passwords before saving them into a file so that sensitive information is protected.

This project uses the **cryptography** library and the **Fernet encryption algorithm** to encrypt and decrypt passwords. Users can add new credentials and view stored passwords through a simple terminal interface.

This project is useful for learning basic Python concepts such as:

* File handling
* Encryption and decryption
* User input handling
* Data storage
* Command-line applications

---

## Features

* Add new username and password
* Encrypt passwords before saving
* View stored passwords
* Simple command-line interface
* Secure password storage using Fernet encryption

---

## Technologies Used

* Python
* cryptography (Fernet)

---

## Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/password-management.git
```

2. Navigate to the project folder:

```
cd password-management
```

3. Install the required library:

```
pip install cryptography
```

---

## First Run (Important)

Before running the program for the first time, you must create the encryption key file.

Uncomment the following lines in the code:

```
# write_key()
```

Then run the program once to generate the **mykey.key** file.

---

## How to Run

Run the Python file:

```
python password_manager.py
```

---

## Usage

When the program runs, it will ask you to choose a mode:

```
Enter the mode (v: view, a: add, q: quit)
```

Options:

* **a** → Add a new username and password
* **v** → View saved passwords
* **q** → Quit the program

Example:

```
Enter the mode (v: view, a: add, q: quit): a
Enter new username: gmail
Enter new password: mypassword123
Added
```

---

## File Structure

```
password_manager.py
mykey.key
passwords.text
```

* **password_manager.py** → main program
* **mykey.key** → encryption key file
* **passwords.text** → encrypted stored passwords

---

## Learning Purpose

This project was created for practicing Python programming and understanding how password encryption works.

-------
this project able to password management webs site database etc 

## Author

Jaweid Moraadi
