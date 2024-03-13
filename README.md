# AirBnB_clone

## Description
The AirBnB_clone project is a command-line interface (CLI) application aimed at mimicking some functionalities of the Airbnb website. It allows users to create, manage, and interact with objects in a similar manner to Airbnb's web platform.

## Command Interpreter
The command interpreter serves as the backbone of the AirBnB_clone project. It interprets user commands and executes corresponding actions, enabling users to interact with the application seamlessly.

### How to Start It
To start the command interpreter, follow these steps:
1. Clone the repository to your local machine: `git clone https://github.com/Kirui-brian/AirBnB_clone.git`
2. Navigate to the project directory: `cd AirBnB_clone`
3. Run the command interpreter: `./console.py`

### How to Use It
Once the command interpreter is running, you can use various commands to interact with the application. Some of the available commands include:
- `create`: Create a new instance of a specified class
- `show`: Display details of a specific instance
- `destroy`: Delete a specified instance
- `all`: Display all instances or all instances of a specified class
- `update`: Update attributes of a specified instance

For a comprehensive list of available commands and their usage, you can use the `help` command within the interpreter.

### Examples
Here are some examples demonstrating the usage of the command interpreter:

1. Creating a new instance:
```(hbnb) create BaseModel```
2. Showing details of an instance:
````(hbnb) show BaseModel 1234-1234-1234```
3. Displaying all instances of a class:
```(hbnb) all BaseModel```
4. Updating attributes of an instance:
```(hbnb) update BaseModel 1234-1234-1234 name "New Name"```
