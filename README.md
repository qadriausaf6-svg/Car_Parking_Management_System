# Car_Parking_Management_System

# 🚗 Car Parking Management System (Stack Based)

A simple and efficient **Car Parking Management System in C**, implemented using a **stack data structure**. This project allows you to manage car entries, exits, search, and file persistence.

---

## 📌 Features

### ✅ **Stack-Based Parking**

* Last-In-First-Out (LIFO) parking logic
* Cars are parked and unparked from the top of the stack

### ✅ **Functions Implemented**

* **Push** (Park a car)
* **Pop** (Remove last parked car)
* **Remove by Registration Number**
* **Display all parked cars**
* **Save parking state to file**
* **Load previous state from file**
* **Free all allocated memory**

### 📂 **File Persistence**

Parking state is saved to:

```
parking_state.txt
```

This means the system remembers all cars even after closing the program.

---

## 📁 Project Structure

```
CarParkingSystem/
│── main.c          # Main program (menu + user input)
│── stack.c         # Implementation of all stack functions
│── stack.h         # Header file (structures + prototypes)
│── parking_state.txt  # Auto-saved parking data
│── README.md       # Project documentation
```

---

## 🛠️ Requirements

* GCC Compiler
* Any OS (Windows, Linux, macOS)
* Terminal / Command Prompt

---

## ▶️ How to Compile

Use this command:

```
gcc main.c stack.c -o parking
```

### Run the Program:

```
./parking
```

(Windows users run: `parking.exe`)

---

## 🖥️ Menu Options

```
1. Park a car
2. Remove last parked car (POP)
3. Remove a car by registration number
4. Display all parked cars
5. Save state
6. Exit
```

---

## 📦 Data Stored for Each Car

* Registration Number
* Owner Name
* Arrival Time
* Pointer to next car (stack implementation)

---

## 📘 Explanation of Files

### **main.c**

Contains:

* Menu
* User input
* Function calls

### **stack.c**

Contains:

* push()
* pop()
* removeByReg()
* displayStack()
* saveToFile()
* loadFromFile()
* freeAll()

### **stack.h**

Contains:

* Structure `Car`
* Function prototypes
* Macro definitions

---

## 🤝 Contribution

Pull requests are welcome.
If you’d like to add new features (e.g., queue version, GUI version), feel free to contribute.

---

## 📄 License

This project is provided for educational purposes and open for modifications.

---

## ⭐ If you like this project

Consider giving it a **Star** on GitHub!

---

### 🔰 Developed for Data Structures / C Programming Projects

Perfect for:

* BCA
* B.Tech
* Diploma
* College lab assignments
