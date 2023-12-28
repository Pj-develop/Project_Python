Abstract
Company Management System (CMS) is designed to automate the existing manual system with computerized equipment and software for billing management, employee database management, and payroll management.
It provides an advanced and organized way to manage user data, employees, billing, sales, and purchase for better performance and services for clients.
Introduction
CMS is developed to overcome the problems faced in the manual system and designed for the specific needs of the company to carry out its operations smoothly and effectively.
It is user-friendly and provides error messages for invalid data, addressing human resource challenges and managerial requirements.
Purpose
The purpose is to describe the functionality and specifications of the offline application for managing employees, payroll, sales, purchase, stock, and inventory.
It aims to automate processes, save time, and provide easy access to information for effective management.
Modules
The Admin module allows adding new employees, creating invoices, updating inventory, managing pay grades, setting attendance, and generating wage sheets.
It also includes a KBC game module for user engagement.
Pros and Cons
Pros include cost-effectiveness, time-saving, security, ease of use, and automated calculations.
Cons are the lack of automatic data fetching from the internet, absence of output in PDF format, and limited cross-platform support.
Feasibility of Software (CMS)
The software meets the scope, is technically feasible, financially feasible, and within the state of the art.
It uses modern techniques, is user-friendly, and reduces labor and extra costs, making it financially feasible.
Flow Chart
The system requirements include Python language, CSV database, Windows 10 OS, Intel core i5 processor, 4GB RAM, and 1TB hard disk, along with specific Python modules.
Sample Source Code
An example of user interface and KBC game source code is provided, demonstrating the log-in process and game functionality.
Employee Data Entry
The program prompts the user to input various details of an employee including employee code, name, father's name, designation, gender, date of birth, date of joining, UAN, IP, mobile number, bank account number, IFSC code, department, location, location category, and wage according to current rates.
The input data is then stored in a CSV file using the pandas library in Python.
Payroll Data Entry
The program prompts the user to enter various wage components including per day wages for unskilled, semi-skilled, skilled, and highly skilled staff in different categories (A, B, C), bonus percentage, gratuity/retirement compensation percentage, leave with wage percentage, Labour Welfare Fund percentage, Employee Provident Fund percentage, and Employee State Insurance percentage.
The input data is then stored in a CSV file using the pandas library in Python.
Salary Data Entry
The program prompts the user to input the salary year and month and then reads data from 'Masters.csv' and 'Mastersw.csv'.
It then processes the salary details and stores the information including employee code, name, father's name, UAN, ESI number, designation, attendance in different shifts, overtime, bonus, gratuity/retirement compensation, leave with wages, other allowances, holiday amount, total, employee provident fund, employee state insurance, Labour Welfare Fund, total deduction, net salary, wage month, and year in a CSV file named 'WAGEDATA.csv'.
Main Functions
The blog consists of various functions such as Date_operations, Sdf_show, Show_Rates, Show_EMP, Salary_show
It includes options for adding employee details, showing employee details, fixing structural rates, showing current DA and HRA rates, wagesheet entry, showing wagesheet, exporting wagesheet to a CSV file, and exiting
Software Modules
The blog mentions the module names as Main, read, purchase, and write
It includes a while loop to continue generating invoices for new purchases
Purchase Function
The function accepts a list of products, interacts with the user for the purchase details, and calculates the purchase amount with discounts
It writes a unique invoice with the purchase details and discounted amount
Functionality
The purchase function checks the availability of products, handles exceptions for user input validation, and calculates the total purchase amount with or without a discount
It generates a unique invoice name with the customer's details and saves the invoice in a .txt file format
Code Segments
The blog includes code segments related to date manipulation, CSV file operations, and user input handling
It contains functions for reading, purchasing, overwriting, and closing files
File Operations
The code has file operations such as opening files for overwriting, reading CSV files, and writing invoice details to a unique .txt file
It creates unique invoice names based on the current date and time along with the customer's name
User Interaction
The code prompts the user for input, validates the input, and handles exceptions for unexpected input
It displays product details, asks for the party name, and interacts with the user for recording sold products
Discount Calculation
The code calculates the total purchase amount, applies discounts based on the purchase criteria, and determines the final payable amount
It prompts the user to enter an expected discount percentage and calculates the discounted amount if applicable
Products available in the Store
The available products along with their prices and quantities are displayed.
The output shows a list of available products, their prices, and quantities.
Remaining Stock Products
The function 'over_write' updates the quantity of products after a purchase and prints the remaining stock products.
It updates the quantity of products after a purchase and displays the remaining stock products.
Future Scope of Work
The future scope includes options to print records in portable formats and adding various features like payment gateways, backup mechanisms, and cloud databases.
Plans to implement cross-platform functionality, separate dashboards, and modifying the KBC game.
Conclusion
The project is designed for use by a single admin in a small-scale organization with limited employees.
It allows the admin to manage employee data, pay structure, predefined pay grades, and view required records instantly.
Bibliography
The bibliography includes websites and books as references for the project.
