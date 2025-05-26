# celebal-oop-linkedlist-python




# 🎯 Celebal OOP Linked List in Python

Welcome to **Celebal OOP Linked List**, a simple yet powerful Python project that demonstrates how to implement a **singly linked list** using **Object-Oriented Programming (OOP)** principles.
This project was developed as **Assignment 2** during my internship/training with **Celebal Technologies**.



## 📌 Project Overview

This project focuses on the fundamental data structure called the **Singly Linked List** and is built entirely using **Python classes and objects**. It showcases how core operations like insertion, deletion (by position), and traversal (display) can be achieved through custom class design.



## 🧠 What You Will Learn

* How to design a custom **Node** and **LinkedList** class.
* How to apply **OOP principles** such as **encapsulation** and **modularity** in Python.
* How to handle edge cases like:

  * Deleting from an empty list
  * Invalid positions
  * Emptying the list fully
* How to implement **clear console logging** using `[INFO]` and `[ERROR]` messages.

---

## 🗂️ File Structure

```
celebal_oop_linkedlist/
│
├── celebal_oop_linkedlist.py     # Main Python script implementing the linked list
├── README.md                     # This documentation file
```

---

## 🧾 Features

* ✅ Append nodes to the end of the list
* ✅ Delete nodes by **1-based position**
* ✅ Display the current state of the list
* ✅ Handle edge cases and errors gracefully
* ✅ Informative console output for clarity



## 📦 How to Run

1. Clone this repository:

```bash
git clone https://github.com/<your-username>/celebal_oop_linkedlist.git
cd celebal_oop_linkedlist
```

2. Run the script using Python:

```bash
python celebal_oop_linkedlist.py
```

> ✅ Make sure Python 3 is installed in your system.



## 📸 Sample Output

```
[INFO] 10 added as the head of the list.
[INFO] 20 appended to the end of the list.
[INFO] 30 appended to the end of the list.
[INFO] 40 appended to the end of the list.

Linked List: 10 -> 20 -> 30 -> 40 -> None

[INFO] Node at position 2 with value 20 deleted.
Linked List: 10 -> 30 -> 40 -> None

[ERROR] Position out of bounds.
[ERROR] Position must be a positive integer.

[INFO] Node at position 1 with value 10 deleted.
[INFO] Node at position 1 with value 30 deleted.
[INFO] Node at position 1 with value 40 deleted.

[INFO] The list is currently empty.
[ERROR] Cannot delete from an empty list.
```

---

## 🧪 Key Functions Explained

 `append(data)`: Adds a node to the end of the list
 `display()`: Prints the current contents of the list
 `delete_by_position(position)`: Deletes the node at a given position with proper error handling


## 🏢 About Celebal Technologies

This project is a part of my Object-Oriented Programming assignment under the mentorship of **Celebal Technologies**, one of the leading organizations in AI, Big Data, and enterprise solutions.



## 🤝 Contribution

This is an academic project. However, contributions are welcome if you'd like to add more features like:

* Reverse the list
* Search for an element
* Add node at specific position
* Create a doubly linked list version

Feel free to fork the repository and submit a pull request!




## 🙋‍♀️ Author

Shalini Kumari
💻 B.Tech (Data Science & Agriculture)
📧 [shalinis19137@gmail.com](mailto:shalinis19137@gmail.com)
🌐 GitHub: [@your-username](https://github.com/your-username)




