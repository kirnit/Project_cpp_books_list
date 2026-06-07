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

///

Система управления книгами на основе односвязного списка
Обзор

Данный проект представляет собой реализацию системы управления коллекцией книг на языке C++ с использованием односвязного списка и отдельной структуры головного элемента.

Программа позволяет создавать и редактировать список книг, выполнять поиск записей по различным критериям, а также сохранять и загружать данные из бинарных файлов.

Проект разработан для изучения динамических структур данных, работы с указателями и файлового ввода-вывода.

Возможности
Информация о книге

Каждая запись содержит следующие поля:

Название книги
Автор
Год издания
Издательство
Количество страниц
Операции со списком
Добавление книги в начало списка
Добавление книги в конец списка
Добавление книги после указанного элемента
Удаление книги из списка
Поиск

Поиск книг осуществляется по следующим критериям:

Название
Автор
Год издания
Работа с файлами
Сохранение всего списка в бинарный файл
Загрузка списка из бинарного файла
Добавление только отсутствующих записей из бинарного файла
Структура данных

В программе используются две отдельные структуры.

Головной элемент списка

Содержит:

Указатель на первый элемент списка
Текущее количество элементов
Узел списка

Содержит:

Данные о книге
Указатель на следующий элемент списка
Используемые технологии
C++
Динамическое выделение памяти
Односвязные списки
Работа с бинарными файлами
Полученные навыки

В ходе выполнения проекта были реализованы и изучены:

Создание собственных структур данных
Работа с динамической памятью
Поиск элементов в связных списках
Сериализация и десериализация данных
Работа с указателями и структурами
Запуск программы

Для компиляции можно использовать любой современный компилятор C++:

g++ main.cpp -o BookManagement
./BookManagement
Автор

Учебный проект, разработанный для изучения структур данных, динамической памяти и работы с бинарными файлами на языке C++.
