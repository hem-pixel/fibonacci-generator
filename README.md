# 🔢 Fibonacci Generator

A simple and beginner-friendly **Fibonacci Series Generator** built using Python.
This project generates the Fibonacci sequence based on the number of terms provided by the user.

## 📌 About the Project

The **Fibonacci sequence** is a series of numbers where each number is the sum of the two preceding numbers.

Example:

```text
0, 1, 1, 2, 3, 5, 8, 13, 21, 34...
```

This project takes the number of terms as input and generates the corresponding Fibonacci sequence.

## ✨ Features

* 🔢 Generate Fibonacci numbers easily
* ⌨️ User-friendly input
* 🐍 Built completely with Python
* ⚡ Fast and lightweight
* 🎓 Beginner-friendly project
* 🚫 No external libraries required

## 🛠️ Technologies Used

* **Python 3.x**

## 📂 Project Structure

```text
Fibonacci-Generator/
│
├── fibonacci.py
├── README.md
└── LICENSE
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Fibonacci-Generator.git
```

### 2. Navigate to the Project Folder

```bash
cd Fibonacci-Generator
```

### 3. Run the Python Program

```bash
python fibonacci.py
```

## 💻 Example

### Input

```text
Enter the number of terms: 10
```

### Output

```text
Fibonacci Series:
0 1 1 2 3 5 8 13 21 34
```

## 🧠 How It Works

The program starts with two initial values:

```text
a = 0
b = 1
```

For every new term:

```text
next = a + b
```

Then the values are updated:

```text
a = b
b = next
```

This process continues until the required number of Fibonacci terms is generated.

## 📚 Concepts Used

This project demonstrates basic Python concepts such as:

* Variables
* User Input
* Loops
* Conditional Statements
* Arithmetic Operators
* Sequence Generation

## 🎯 Learning Objective

The main objective of this project is to understand how loops, variables, and mathematical logic can be used to generate a sequence programmatically.

## 🔮 Future Improvements

Possible future enhancements:

* Add a GUI interface
* Add recursive Fibonacci generation
* Add input validation
* Generate Fibonacci numbers up to a maximum value
* Add performance comparison between iterative and recursive approaches
* Export generated sequences to a file

## 👨‍💻 Author

**Hemanth D**

Built with ❤️ using Python.

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub!
