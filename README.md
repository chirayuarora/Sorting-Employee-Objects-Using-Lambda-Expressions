# Sorting Employee Objects Using Lambda Expressions

## 📘 Objective
A Java program that demonstrates sorting of `Employee` objects using **lambda expressions** to simplify comparator logic.

---

## ⚙️ Features
- Creates a list of Employee objects with name, age, and salary.
- Sorts employees:
  - ✅ By **Name** (Alphabetically)
  - ✅ By **Age** (Ascending)
  - ✅ By **Salary** (Descending)
- Uses **lambda expressions** for concise and readable comparators.
- Demonstrates **functional programming** in Java.

---

## 🧠 Concepts Covered
- **Lambda Expressions:** Simplify comparator creation for sorting.
- **List.sort() / Collections.sort():** Sort lists with custom logic.
- **Comparator with Lambdas:** Replaces anonymous inner classes.
- **forEach with Method Reference:** Streamlined display using `System.out::println`.

---

## 🧩 Example Output
Original List:
Name: Alice, Age: 28, Salary: 45000.0
Name: Bob, Age: 32, Salary: 50000.0
Name: Charlie, Age: 25, Salary: 40000.0
Name: David, Age: 30, Salary: 55000.0

Sorted by Name:
Name: Alice, Age: 28, Salary: 45000.0
Name: Bob, Age: 32, Salary: 50000.0
Name: Charlie, Age: 25, Salary: 40000.0
Name: David, Age: 30, Salary: 55000.0

Sorted by Age:
Name: Charlie, Age: 25, Salary: 40000.0
Name: Alice, Age: 28, Salary: 45000.0
Name: David, Age: 30, Salary: 55000.0
Name: Bob, Age: 32, Salary: 50000.0

Sorted by Salary (Descending):
Name: David, Age: 30, Salary: 55000.0
Name: Bob, Age: 32, Salary: 50000.0
Name: Alice, Age: 28, Salary: 45000.0
Name: Charlie, Age: 25, Salary: 40000.0

---

## 🖥️ How to Run
1. Save the file as `EmployeeSorting.java`.
2. Compile the program:
   ```bash
   javac EmployeeSorting.java

Run it:
java EmployeeSorting

📄 Author
Chirayu Arora

🏷️ Tags
Java Lambda Expressions Sorting Comparator Collections Functional Programming
