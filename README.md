# AirBnB clone - The console

Welcome to our console for the AirBnB clone! This is a command interpreter to manage the objects of the project. You can create new objects, retrieve objects from various sources, perform operations on objects, update object attributes, and even destroy objects.

## How to use it

You can use the AirBnB clone console in two ways: interactive mode and non-interactive mode. In the interactive mode, run the script and input commands directly after the prompt. This mode allows real-time interactions. In the non-interactive mode, automate tasks by echoing commands into the script from external sources, like scripts or batch files, making it suitable for scripting and automation. Both methods offer flexibility to manage objects based on your needs.

## How do you open the interpreter

To open the interpreter, you must run the code in interactive mode. To run it you type in the terminal ./console.py and it will be in interactive mode.

holbertonschool-AirBnB_clone$ ./console.py

(hbnb) help

Documented commands (type help <topic>):

EOF all create destroy help quit show update

(hbnb) help show
Prints the string representation of an instance
based on the class name and id.

(hbnb) help all
Prints all string representation of all instances based
or not on the class name.

(hbnb) all
[]

(hbnb) all BaseModel
[]

(hbnb) create Basemodel
** class doesn't exist **

(hbnb) create BaseModel
876b98f1-58a6-4876-9b19-93bfdc67f0f8

(hbnb) all BaseModel
["[BaseModel] (876b98f1-58a6-4876-9b19-93bfdc67f0f8) ({'id': '876b98f1-58a6-4876-9b19-93bfdc67f0f8', 'created_at': datetime.datetime(2023, 11, 1, 15, 43, 51, 289859), 'updated_at': datetime.datetime(2023, 11, 1, 15, 43, 51, 289890)})"]

(hbnb)EOF
guillep2018@guillep2018-ThinkPad-X1-Carbon-Gen-9:~/Desktop/coding-fridays/holbertonschool-AirBnB_clone$

## What can you do?

There are several command you can run with this interpreter and they are as follows.

-help = lists all available commands with "help" or detailed help with "help cmd"
-EOF = EOF command to exit the program
-all = prints all string representations of all instances based on the class name
-create = creates a new instance of BaseModel, saves it to the JSON file and prints the ID
-destroy = deletes an instance based on the class name and id (saves the change into the JSON file)
-quit = quit command to exit the program
-show = prints the string representation of an instance based on the class name and id
-update = updates an instance based on the class name and id by adding or updating attribute (saves the change into the JSON file)

## Examples

## 🛠️ Contributors

- Carlos Carrasquillo \<collectornifty@gmail.com\> \<carlfrank\>
- Guillermo Pereyo \<gpereyo@gmail.com\> \<Guillep2018\>

May the code be with you! 🌌👾
Happy coding! 🚀👨‍💻👩‍💻
