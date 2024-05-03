# Custom my_echo Command

This project implements a custom 'my_echo' command, which mimics the basic functionality of the 'echo' command in Unix-like systems. The 'my_echo' command takes a message as input and prints it to the console.

## Usage
To use the my_echo command, follow these steps:

- Activate the virtual environment:
pipenv shell
- Run the my_echo command:
pipenv run my_echo "Your message here"
Replace Your message here with the message you want to echo.

## Directory Structure
bin/: Contains the 'my_echo' script, which is the executable for the custom 'my_echo' command.

lib/: Contains the 'echo_lib.py' file, which defines the 'echo' function used by the 'my_echo' script.

README.md: This file, providing an overview of the project and usage instructions.

## Implementation Details
The 'my_echo' script imports the 'echo' function from 'echo_lib.py' to print messages passed to it as arguments.

## Author

Nehema Kinya.



