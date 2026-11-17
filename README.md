# Student Grade Calculator (Python Week 2 Project)

## 📌 Project Overview
The Student Grade Calculator is a command-line Python application designed to process student marks, evaluate their performance using conditional logic, and provide structured letter grades along with personalized, encouraging feedback.

## 🛠️ Features & Technical Requirements
- **Functions:** Modular code structure separating calculation logic (`calculate_grade`) from input handling (`get_valid_marks`).
- **Control Flow:** Utilizes `if-elif-else` branching to evaluate scores across standard grading tiers.
- **Robust Error Handling:** Implements a `while` loop combined with `try-except` blocks to catch invalid data types and out-of-range inputs (allowing numbers strictly between `0` and `100`).
- **Feedback System:** Delivers motivational messages tailored to each grade category.

## 📋 Grading Logic
- **A:** 90 - 100
- **B:** 80 - 89
- **C:** 70 - 79
- **D:** 60 - 69
- **F:** 0 - 59

## 🚀 Setup & Execution Instructions
1. Ensure you have Python 3 installed on your system.
2. Clone or download this repository.
3. Open your terminal or command prompt in the project directory.
4. Run the script:
   ```bash
   python grade_calculator.py