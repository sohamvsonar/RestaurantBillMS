# Restaurant Bill and Inventory Management System

## Overview

The Restaurant Bill and Inventory Management System is a Python-based application for managing bills and inventory in a restaurant setting.
The system allows users to add, update, and view items, generate bills, and maintain inventory records.

## Features

- Add and update items in the inventory
- Generate bills with detailed item information
- View and manage the list of bills
- User authentication for admin access

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/sohamsonar427/RestaurentBillMS.git

2. **Install Dependencies:**
``` pip install pymysql

## Usage
1. Setup The SQL server:
You can use any workbench or database server, here I have used the MySQL server and Workbench v8.1.
Once installed Setup up the database server and setup a password for the host login, and run the SQL script on the server and connect it with the python file.
If you want to make any changes in backend you can directly change or alter the database file or run scripts on the server.

2. Setting up the Python file:
First in the python file here ' conn = pymysql.connect(host="localhost", user="root", passwd="", db="billservice") '
Enter the password in the passwd field that you used to set up the database server using the host login. (Remember there are lot of code lines where 
authentication is required so make sure you have entered the password everywhere)

3. Running the application:
After the database server setup and Python file setup run the file.
```
python main.py

4. Login:
Use the admin credentials to log in.(from the sql file)
Default username: admin
password - 123456
You can remove or add many as admins in the sql script.

5. Add or Update Items:
Navigate to the "Add Item" or "Update Item" section to manage inventory.

6. Generate Bills:
Add items to the list and click "Generate Bills" to create a bill.
You can save the generated bills anywhere in the computer.
A text file will be created.

7. View Bills:
Navigate to the "Show Bills" section to view all generated bills.

## Screenshot
![](https://github.com/sohamsonar427/RestaurentBillMS/blob/main/SS.jpg)
## Technologies Used
* Python
* Tkinter (GUI)
* MySQL (Database)

## License
This project is licensed under the MIT License.
