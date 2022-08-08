# **AirBnB clone - The console**
## Description
This is the first step towards building your first full web application: the AirBnB clone.
This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data.
## Console and Command Usage
The console is a Unix shell-like command line user interface provided by the python CmdModule It prints a prompt and waits for the user for input, for our project we used (hbnb)


| command | Example|
------ |--------
| Display commands help| (hbnb) help <command>|
| Create object (prints its id)| (hbnb) create <class>|
| Destroy object | (hbnb) destroy <class> <id> or (hbnb) <class>.destroy(<id>)|
| Show object | (hbnb) show <class> <id> or (hbnb) <class>.show(<id>)|
| Show "all" objects or instances class | (hbnb) all or (hbnb) all <class>|	
| Run console | ./console.py|
| Quit console | (hbnb) quit|

## Test
---
All the code is tested with the unittest module. The test for the classes are in the test_models folder.

## Authors
---
- Ivang Silas
- terry Sidi
