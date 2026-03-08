# Modular-Shopping-Cart (JS)

A modular **Shopping Cart system built with modern JavaScript (ES Modules)**.
This project demonstrates how a real-world cart system can be structured using clean architecture, reusable modules, and modern JavaScript features.

The goal of this project is to practice **advanced JavaScript concepts** while keeping the code organized and scalable.

## Features

* Product management using **JavaScript classes**
* Cart management with **add/remove operations**
* Price calculation using **array methods**
* Deep cloning using `structuredClone`
* Product grouping using **Map**
* Unique category detection using **Set**
* Product sorting by price
* Dynamic module loading using **dynamic import**
* JSON summary generation using **template literals**

---

## JavaScript Concepts Used

This project demonstrates modern JavaScript practices including:

* ES Modules (`import` / `export`)
* Dynamic imports
* Classes and constructors
* Static methods
* Object destructuring
* Spread operator
* Rest parameters
* Map and Set data structures
* Template literals
* `structuredClone()` for deep copying
* JSDoc typed-style annotations

---

## Example Output

When running the project, the system generates a JSON summary of the cart:

```json
{
  "total": 1200,
  "itemsCount": 2,
  "uniqueCategories": ["electronics","fashion"],
  "items": [
    {
      "id": "1",
      "name": "Laptop",
      "price": 1000,
      "category": "electronics"
    },
    {
      "id": "3",
      "name": "Shoes",
      "price": 200,
      "category": "fashion"
    }
  ]
}
```

---

## How to Run the Project

Run the application:

```
node main.js
```

---

## Purpose of the Project

This project was built as a learning exercise to practice **modular JavaScript design and modern language features** .
