# Linked-list-Doubly
# Doubly Linked List in Java

This project provides a basic implementation of a **Doubly Linked List (DLL)** in Java. It supports insertion at the beginning and displays the list in a readable format.

## Features

- Insert at the beginning
- Display the list with both forward and backward connections

## Code Structure

### `Node` Class
A helper class that represents a node in the doubly linked list. Each node contains:
- An integer `data`
- A reference to the previous node (`prev`)
- A reference to the next node (`next`)

### `DLL` Class
Maintains the `head` of the list and includes methods to manipulate and view the list.

#### Methods:
- `InsertAtBeginning(int data)` – Inserts a node at the beginning of the list
- `display()` – Displays the list in the format: `null <-> data <-> ... <-> null`

## Sample Output
When the `main` method runs:

- Nodes 70, 60, 50, and 40 are inserted at the beginning.
- The display method outputs the linked list.

