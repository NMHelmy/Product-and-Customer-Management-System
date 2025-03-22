# Product-and-Customer-Management-System
- Using text files not database
## Overview
This C++ program is a simple Product and Customer Management System that allows users to manage products and customer details. The system provides functionalities such as adding new products, searching for products, categorizing products, adding and editing customer details, recording purchases, handling product returns, checking restock levels, and generating restock summaries.

---

## Features
### Product Management
* Add a New Product: Add a new product with details such as name, price, and amount.
* Search for a Product: Search for a product by name and display its details.
* Display Products by Category: Display products based on their category (Large-appliances, Small-appliances, Kitchen-appliances, Gadgets).

### Customer Management
* Add a New Customer: Add a new customer with details such as first name, last name, phone number, address, email, and payment method.
* Edit an Existing Customer: Edit the details of an existing customer.

### Purchase and Return Management
* Record a Purchase: Record a purchase of a product by a customer and update the product's stock.
* Record a Return: Record the return of a product by a customer and update the product's stock.

### Restock Management
* Check Restock: Check if a specific product needs to be restocked.
* Restock Summary: Generate a summary of all products that need to be restocked.

---

## Technologies Used

* C++
* File handling using fstream
* Object-Oriented Programming (OOP) principles

---

## How to Use
1. Compile the Program: Compile the C++ program using a C++ compiler (e.g., g++).
```
g++ -o product_management product_management.cpp
```
2. Run the Program: Execute the compiled program.
```
./product_management
```
3. Follow the Prompts: The program will display a menu of options. Follow the prompts to perform various operations such as adding products, searching for products, adding customers, etc.

---

## Code Structure
* Product Class: Handles product-related operations such as adding new products, searching for products, and categorizing products.
* Customer Class: Inherits from the Product class and handles customer-related operations such as adding new customers and editing customer details.
* Main Function: Provides a menu-driven interface for users to interact with the system.

---

## Files Used
* Product Names.txt: Stores the details of all products.
* Customer details.txt: Stores the details of all customers.
* other customer.txt: Temporary file used during the editing of customer details.

---

## Notes
Ensure that the Product Names.txt and Customer details.txt files exist in the same directory as the executable.

---

## Future Improvements
Improve file handling efficiency.
<br>Implement a GUI for a better user experience.
<br>The program uses simple file handling for data storage. For more robust data management, consider using a database system instead of using text files.
