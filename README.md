# Store Inventory Management System

A C++ application designed to manage store inventory, track sales, and organize product information. The project uses the Standard Template Library (STL) to implement efficient data management and provide essential inventory control functionalities.

## Features

- **Product Management:** Add, remove, and search for products in the inventory.
- **Sales Tracking:** Register sales and maintain a history of transactions.
- **Category Management:** Organize products by category and identify unique categories.
- **Inventory Statistics:** Calculate the number of products and total inventory value for each category.
- **Data Organization:** Use STL containers to efficiently store and manage inventory information.

## Data Structures

The project uses several STL containers to handle different aspects of inventory management:

| Data Structure | Purpose |
|---|---|
| `vector<Produto>` | Stores and manages the product inventory. |
| `set<string>` | Maintains a collection of unique product categories. |
| `map<string, int>` | Tracks the number of products in each category. |
| `map<string, double>` | Stores the total inventory value for each category. |
| `list<string>` | Maintains the sales history. |

## Technologies

- **Language:** C++
- **Standard Library:** STL
- **Compiler:** GCC (g++)

## Getting Started

### Prerequisites

Make sure you have a C++ compiler installed, such as GCC.

### Compilation

Clone the repository:

```bash
git clone https://github.com/nandamfmf/Sistema-loja.git
cd Sistema-loja
```

Compile the project:

```bash
g++ -o store main.cpp inventario.cpp
```

### Execution

Run the compiled program:

```bash
./store
```

## Project Structure

```text
Sistema-loja/
├── main.cpp
├── inventario.cpp
├── inventario.h
└── README.md
```

## Learning Objectives

This project was developed to practice and apply fundamental C++ concepts, including:

- Standard Template Library (STL)
- Data structures and their applications
- Object-oriented programming
- Inventory and transaction management
- Modular programming and code organization

---

Developed as a C++ project to explore practical applications of data structures and inventory management.
