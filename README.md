# Book Management System Using a Singly Linked List

## Overview

This project is a C++ implementation of a book management system based on a singly linked list with a dedicated head structure.

The application allows users to create and manage a collection of books, perform searches, modify the list, and save or load data using binary files.

The project was developed as an exercise in dynamic memory management, linked list operations, and file handling.

## Features

### Book Information

Each book record contains:

* Title
* Author
* Publication Year
* Publisher
* Number of Pages

### Linked List Operations

* Insert a book at the beginning of the list
* Insert a book at the end of the list
* Insert a book after a specified element
* Delete a book from the list

### Search Functionality

Search books by:

* Title
* Author
* Publication Year

### File Operations

* Save the entire list to a binary file
* Load the list from a binary file
* Import only non-existing books from a binary file

## Data Structure

The program uses two separate structures:

### Head Structure

Stores:

* Pointer to the first list element
* Current number of elements in the list

### Book Node Structure

Stores:

* Book information
* Pointer to the next node

## Technologies

* C++
* Dynamic Memory Allocation
* Singly Linked Lists
* Binary File Processing

## Learning Objectives

This project demonstrates:

* Implementation of custom linked data structures
* Dynamic memory management
* Searching algorithms
* Binary serialization and deserialization
* Working with pointers and structures

## Usage

Compile the program using any C++ compiler:

```bash
g++ main.cpp -o BookManagement
./BookManagement
```

## Author

Educational project developed for studying data structures and file processing in C++.
