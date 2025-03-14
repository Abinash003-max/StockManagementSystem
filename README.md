# Stock Management System

## Introduction
The **Stock Management System** is a Java-based desktop application designed to streamline inventory tracking, vendor management, product handling, order processing, and financial transactions. Built using **Java Swing** for the user interface and **JDBC** for database connectivity, this system efficiently manages stock-related operations, ensuring accuracy and ease of use. The backend utilizes **MySQL** for data storage, making it a robust and scalable solution.

## Project Structure
The project consists of five core Java files:

### 1. MainFrame.java
**MainFrame.java** serves as the central hub of the Stock Management System. It provides a graphical user interface (GUI) that links different modules, allowing users to navigate through vendor management, product handling, order processing, and transaction management. The frame ensures a seamless and user-friendly experience.

### 2. Vendor.java
**Vendor.java** handles vendor-related operations, including:
- Adding new vendors
- Updating vendor details
- Deleting vendors
- Displaying a list of vendors
This module ensures proper vendor tracking and integration with the product supply chain.

### 3. Product.java
**Product.java** manages inventory by allowing users to:
- Add new products
- Update product details (name, price, stock quantity)
- Remove outdated products
- Display all available products
This module ensures the stock is well-organized and up to date.

### 4. Order.java
**Order.java** facilitates order management, including:
- Placing new orders
- Managing order details (order ID, vendor, quantity, status)
- Viewing order history
This module helps streamline the order fulfillment process.

### 5. Transaction.java
**Transaction.java** deals with financial transactions related to stock purchases. It includes:
- Calculating the total amount for an order
- Processing payments
- Storing transaction history
- Managing payment status
This module ensures secure and efficient financial tracking.

## Conclusion
The **Stock Management System** provides an efficient and user-friendly solution for managing inventory, vendors, orders, and transactions. Built with Java Swing and MySQL, it offers a structured and scalable approach to stock management. This project can be further enhanced with additional features such as automated reporting, user authentication, and cloud-based storage integration. The system is a great foundation for businesses looking to optimize their stock management processes.

