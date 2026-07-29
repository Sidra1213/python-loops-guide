# 🔄 Python Loops Practice & Problem Solving

This repository contains practical examples and exercises on **`for` loops** and **`while` loops** in Python, implemented in a Jupyter Notebook (`python-loops-guide.ipynb`).

---

## 📌 Topics & Concepts Covered

### 1. `for` Loop Fundamentals
* Basic syntax and iterating with `range()`[cite: 1]
* Custom ranges (e.g., `range(10, 16)`)[cite: 1]
* **Step Size:** Incrementing by specific values (e.g., `range(0, 11, 2)`)[cite: 1]
* **Reverse Loops:** Counting down using negative steps (e.g., `10` to `1`)[cite: 1]

### 2. `while` Loop Usage
* Basic syntax and condition-based execution[cite: 1]
* Printing number sequences using counter variables[cite: 1]

### 3. Loop Control Statements
* **`break`**: Terminating loop execution early (e.g., stopping when `i == 7`)[cite: 1]
* **`continue`**: Skipping specific iterations (e.g., skipping `5`)[cite: 1]

---

## 🎯 Code Examples & Problems Solved

Here are the key problems and algorithms implemented in the notebook:

1. **Even & Odd Numbers:** Filtering even numbers (`2–20`) and odd numbers (`1–19`)[cite: 1].
2. **Multiplication Table:** Generating custom multiplication tables via user input[cite: 1].
3. **Sum Accumulation:** Calculating the sum of numbers from `1` to `100` (`5050`)[cite: 1].
4. **String Iteration:** Printing string characters line-by-line[cite: 1].
5. **Number Squares:** Calculating and printing squares for numbers `1` to `10`[cite: 1].
6. **Divisibility Counter:** Counting numbers between `1` and `100` that are divisible by `5`[cite: 1].
7. **Find Largest Number:** Finding the maximum element in a list without built-in functions[cite: 1].
8. **Find Second Largest Number:** Algorithm to track both the largest and second-largest values in a list[cite: 1].
9. **Reverse a String:** Reversing string characters using loop concatenation (e.g., `"PYTHON"` $\rightarrow$ `"NOHTYP"`)[cite: 1].
10. **Vowel Counter:** Counting vowels (`a, e, i, o, u`) in a given word[cite: 1].

---

## 💡 Quick Highlights

### Finding Second Largest Number in a List
```python
numbers = [10, 20, 30, 40, 50]
largest = numbers[0]
second_largest = numbers[0]

for num in numbers:
    if num > largest:
        second_largest = largest
        largest = num
    elif num > second_largest and num != largest:
        second_largest = num

print("LARGEST NUMBER:", largest)
print("SECOND LARGEST:", second_largest)
```[cite: 1]

### Reversing a String
```python
name = 'PYTHON'
reverse = ""
for char in name:
    reverse = char + reverse
print(reverse)
```[cite: 1]

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
