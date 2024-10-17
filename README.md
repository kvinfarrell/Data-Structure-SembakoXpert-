# SembakoXpert

SembakoXpert is an application designed to efficiently manage and track supplier data and sales reports for grocery stores. The program leverages hash table data structures to provide quick access to supplier and sales information, addressing the challenges faced by store owners in managing supplier data effectively.

## Background

In the grocery store business, managing supplier information is crucial for operations. Store owners often encounter challenges such as:

- **Large Volume of Data:** Grocery stores typically deal with numerous suppliers providing various products. Manually managing this data can be time-consuming and prone to errors, highlighting the need for a system that stores and accesses supplier data efficiently.

- **Data Grouping and Sorting:** Supplier data needs to be grouped and sorted by specific criteria, such as supplier name or product type. The high number of suppliers and products makes manual sorting cumbersome, necessitating an automated system for easier information retrieval.

- **Supplier Reports:** Store owners require reports on supplier transactions for analysis and decision-making. Generating these reports manually can be inefficient and time-consuming.

With these challenges in mind, we developed SembakoXpert to provide a simple and effective solution for managing supplier and sales data in grocery stores. The application allows users to quickly search, group, sort, and print supplier reports based on specific criteria using hash table structures.

## Features

SembakoXpert includes the following features:

- **Sales Data Entry:** Users can enter sales transaction data, including transaction date, buyer name, product type, product name, quantity, price, and total payment. This data is saved in a `sales.txt` file for processing and reporting.

- **Sales Report Printing (Sort by Transaction Date):** This feature allows users to print sales reports sorted by transaction date in ascending order.

- **Sales Report Printing (Sort by Quantity Sold):** Users can print sales reports sorted by the quantity sold in descending order.

- **Search Sales Report:** Users can search for sales reports using a hash key. The program prompts for the hash key, retrieves the corresponding sales data, and displays it on the screen.

- **Update Sales Report:** Users can modify existing sales data. They must enter the hash key for the data they wish to update and select the specific fields to change, such as date, buyer name, product type, product name, quantity, or price. The updated data is saved back to `sales.txt`.

- **Exit:** This feature terminates the program and exits the application.
