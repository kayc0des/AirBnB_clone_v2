# Project 0x02. AirBnB clone - MySQL :computer:

## :page_facing_up: In this project we created version 2 of the Airbnb Clone where we will connect with the databases to continue with the advancement of it.

### 📋 Requirements
***
#### Python Scripts

* Allowed editors: `vi`, `vim`, `emacs`.
* Files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5).
* Files must be executable.
* The length of your files will be tested using `wc`.

#### Python Unit Tests

* All your test files should be inside a folder `tests`.
* You have to use the unittest module.
* All your test files should be python files (extension: `.py`).
* All your test files and folders should start by `test_`.
* Your file organization in the tests folder should be the same as your project: ex: for `models/base_model.py`, unit tests must be in: `tests/test_models/test_base_model.py`.

#### SQL Scripts

* Files will be executed on Ubuntu 20.04 LTS using `MySQL 8.0`.
* Files will be executed with `SQLAlchemy` version `1.4.x`.
* All SQL keywords should be in uppercase (`SELECT`, `WHERE`…).
* The length of your files will be tested using `wc`.

### 🎨 Style
***
* Code should use the PEP 8 style (version 2.7.*).

#### Comments for your SQL file:

```SQL
$ cat my_script.sql
-- first 3 students in the Batch ID=3
-- because Batch 3 is the best!
SELECT id, name FROM students WHERE batch_id = 3 ORDER BY created_at DESC LIMIT 3;
$
```

<center> <h1>HBNB - The Console</h1> </center>

This repository contains the initial stage of a student project to build a clone of the AirBnB website. This stage implements a backend interface, or console, to manage program data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

---

<center><h3>Repository Contents by Project Task</h3> </center>

|
<center> <h2>General Use</h2> </center>

1. First clone this repository.

3. Once the repository is cloned locate the "console.py" file and run it as follows:
```
/AirBnB_clone$ ./console.py
```
4. When this command is run the following prompt should appear:
```
(hbnb)
```
5. This prompt designates you are in the "HBnB" console. There are a variety of commands available within the console program.

##### Commands
    * create - Creates an instance based on given class

    * destroy - Destroys an object based on class and UUID

    * show - Shows an object based on class and UUID

    * all - Shows all objects the program has access to, or all objects of a given class

    * update - Updates existing attributes an object based on class name and UUID

    * quit - Exits the program (EOF will as well)


##### Alternative Syntax
Users are able to issue a number of console command using an alternative syntax:

	Usage: <class_name>.<command>([<id>[name_arg value_arg]|[kwargs]])
Advanced syntax is implemented for the following commands: 

    * all - Shows all objects the program has access to, or all objects of a given class

	* count - Return number of object instances by class

    * show - Shows an object based on class and UUID

	* destroy - Destroys an object based on class and UUID

    * update - Updates existing attributes an object based on class name and UUID

<br>

i added a gitbash file to automate the boring staff 
