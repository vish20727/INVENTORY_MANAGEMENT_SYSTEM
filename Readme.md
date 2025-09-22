
Student Information :

Name : Vishesh Vinshan Saraswat
Roll No. : 2401360027
University: K.R. Mangalam University
Course: Btech CSE (UX/UI)
Subject : Data Structure And Algorothms LAB
Course Code: ENCS253



# Grocery Store Inventory System

##  Project Overview
This project is a **menu-driven C++ program** that simulates an **Inventory Management System** for a grocery store.  
It uses **array-based data structures** to store item details and implements operations such as insertion, deletion, search, display, row/column ordering, and sparse representation.

This project is part of **Lab Assignment 1 (Data Structures - Arrays & Complexity Analysis)**.

---

## Features
1. **Insert Item** – Add a new item record (ID, Name, Quantity, Price).  
2. **Delete Item** – Remove an item using its unique ID.  
3. **Search Item** – Search for an item by ID or Name.  
4. **Display All Items** – Show all items in the inventory.  
5. **Row-Major & Column-Major Ordering** – Manage Price and Quantity tables.  
6. **Sparse Representation** – Display items with stock less than or equal to a user-defined threshold.  

---


=== sample run code ===

====== Grocery Store Inventory System ======
1. Insert Item
2. Delete Item
3. Search Item (by ID or Name)
4. Display All Items
5. Manage Price & Quantity (Row/Column Order)
6. Optimize Sparse Storage (Low Stock)
7. Exit
Enter choice: 1
Enter Item ID: 101
Enter Item Name: Apple
Enter Quantity: 3
Enter Price: 50
Item inserted successfully

Enter choice: 6
Enter threshold quantity for rarely restocked items: 5

--- Sparse Representation (ID, Name, Qty, Price) ---
101 | Apple | 3 | 50
