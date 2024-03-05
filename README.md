# AirBnB Clone

## Description

This is the first step towards building our first full web application: the AirBnB clone. This project is very important because we will use what we build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

## Command Interpreter

The command interpreter is designed to manage the objects of our AirBnB project:

### How to start it

You can start the command interpreter by running this command in your terminal:

```bash
./console.py
```

### How to start it
Once you’ve started it, you can use the command interpreter to manage your objects. Here are some commands you can use:

```bash
create <class>
```
: Creates a new instance of <class>, saves it (to the JSON file) and prints the id.
```bash
show <class> <id>
```
: Prints the string representation of an instance based on the class name and id.
```bash
destroy <class> <id>
```
: Deletes an instance based on the class name and id.
```bash
all <class> or all
```
: Prints all string representation of all instances based or not on the class name.
```bash
update <class> <id> <attribute name> "<attribute value>"
```
: Updates an instance based on the class name and id by adding or updating attribute.

### Examples
Here’s an example of how you can use the command interpreter:

```bash
$ ./console.py
(hbnb) create BaseModel
1234-1234-1234
(hbnb) show BaseModel 1234-1234-1234
[BaseModel] (1234-1234-1234) {'id': '1234-1234-1234', 'created_at': '2024-03-05T21:53:16', 'updated_at': '2024-03-05T21:53:16'}
(hbnb) quit
$
```
