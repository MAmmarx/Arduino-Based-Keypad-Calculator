# Arduino-Based-Keypad-Calculator
This project was made in 1st Year of University by a group of 4 andit is an Arduino-powered calculator using a 4x4 keypad and an I2C LCD. It performs basic arithmetic operations (+, -, *, /) and displays results in real time.

# 🔢 ArduCalc: Arduino Keypad Calculator

## 📌 Overview  
ArduCalc is a simple **Arduino-powered calculator** that uses a **4x4 keypad** and an **I2C LCD** to perform basic arithmetic operations (`+`, `-`, `*`, `/`). It allows users to input numbers, execute calculations, and display results in real-time.

---

## 🧑‍💻 Objective  
The goal of this project is to create a functional calculator using an **Arduino**, a **keypad for input**, and an **LCD for output**, helping users learn about embedded systems and microcontroller programming.

---

## 🛠️ Features  

### ✅ **1. Keypad Input Handling**  
- Uses a **4x4 keypad** for number and operator inputs.
- Detects and processes button presses accurately.

### ✅ **2. LCD Display Output**  
- Displays user input and results on an **I2C LCD**.
- Provides a clear and interactive user interface.

### ✅ **3. Arithmetic Operations**  
- Supports **addition (+), subtraction (-), multiplication (*), and division (/).**
- Processes calculations and updates the display accordingly.

---

## 🛠️ Setup & Usage  

### **🔹 Hardware Requirements**  
- **Arduino Board** (Uno, Mega, etc.)  
- **4x4 Keypad**  
- **I2C LCD Display (16x2 or 20x4)**  
- **Jumper wires**  

### **🔹 Software Requirements**  
- **Arduino IDE**  
- Install required libraries:  
  ```cpp
  #include "Keypad.h"
  #include "LiquidCrystal_I2C.h"
