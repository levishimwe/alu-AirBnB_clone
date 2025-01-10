<h1 align="center">🏠 alu-AirBnB</h1>
<p align="center">An AirBnB clone.</p>

---

## 📖 Description

AirBnB is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB. This is the first step towards building a full web application: an AirBnB clone. This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data.

---

## 💻 Usage

1. First, clone this repository:
   ```bash
   git clone https://github.com/yourusername/repository-name.git
   cd repository-name


Locate the console.py file and run it as follows:
./console.py

When the command is executed, the following prompt should appear:

(airbnb)


This prompt indicates you are in the AirBnB Console. Below is a list of commands available within the console program:

🛠️ Commands
create: Creates an instance based on a given class.
destroy: Destroys an object based on class and UUID.
show: Displays an object based on class and UUID.
all: Displays all objects the program has access to or all objects of a given class.
update: Updates existing attributes of an object based on class name and UUID.
quit: Exits the program (EOF also works).
🌀 Alternative Syntax
Advanced syntax can be used for the following commands:

all: Shows all objects or all objects of a given class.
count: Returns the number of object instances by class.
show: Displays an object based on class and UUID.
destroy: Destroys an object based on class and UUID.
update: Updates an object's attributes by class name and UUID.


🎨 Examples
✨ Primary Command Syntax
Example 0: Create an object
Usage: create <class_name>

(airbnb) create BaseModel
(airbnb) create BaseModel
3aa5babc-efb6-4041-bfe9-3cc9727588f8
(airbnb)  

Example 1: Show an object
Usage: show <class_name> <_id>

(airbnb) show BaseModel 3aa5babc-efb6-4041-bfe9-3cc9727588f8
[BaseModel] (3aa5babc-efb6-4041-bfe9-3cc9727588f8) {'id': '3aa5babc-efb6-4041-bfe9-3cc9727588f8', 'created_at': datetime.datetime(2020, 2, 18, 14, 21, 12, 96959), 'updated_at': datetime.datetime(2020, 2, 18, 14, 21, 12, 96971)}
(airbnb)  

Example 2: Destroy an object
Usage: destroy <class_name> <_id>

(airbnb) destroy BaseModel 3aa5babc-efb6-4041-bfe9-3cc9727588f8
(airbnb) show BaseModel 3aa5babc-efb6-4041-bfe9-3cc9727588f8
** no instance found **
(airbnb)   

###### Example 3: Update User (by dictionary)
Usage: <class_name>.update(<_id>, <dictionary>)
```
(hbnb) User.update("98bea5de-9cb0-4d78-8a9d-c4de03521c30", {'name': 'Fred the Frog', 'age': 9})
(hbnb)
(hbnb) User.all()
(hbnb) ["[User] (98bea5de-9cb0-4d78-8a9d-c4de03521c30) {'updated_at': datetime.datetime(2020, 2, 19, 21, 47, 29, 134362), 'name': 'Fred the Frog', 'age': 9, 'id': '98bea5de-9cb0-4d78-8a9d-c4de03521c30', 'created_at': datetime.datetime(2020, 2, 19, 21, 47, 29, 134343)}"]
```
<br>

## Authors :black_nib:
* **Levis Ishimwe** <[levishimwe](https://github.com/levishimwe)> <i.levis@alustudent.com>
* **Akachi David Nwanze** <[S1rDavid9](https://github.com/S1rDavid9)> <d.akachi@alustudent.com>
