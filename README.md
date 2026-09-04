# 🔢 NumPy Random Data Generation and Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Data%20Analysis-013243?logo=numpy\&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?logo=googlecolab\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter\&logoColor=white)

> 🐍 A collection of Python and NumPy programs focused on **random data generation, array manipulation, filtering, loops, indexing, and data analysis**.

---

## 📌 Description

This project contains a collection of Python programs using **NumPy's random module** to generate random data and perform different types of analysis.

The exercises cover:

🎲 Random number generation
🔎 Filtering
🔢 Counting
📊 Statistical calculations
🔄 Loops
📍 Indexing
⚙️ Conditional statements
✨ Uniqueness checks

These programs help demonstrate how **NumPy arrays** can be used to work with randomly generated data in practical situations.

---

# 📚 Questions Covered

## 1️⃣ 🎯 Generate Random Numbers and Find Even Numbers

Generated **20 random integers between 1 and 100** using NumPy.

### 🔍 The program:

* 📋 Displays the generated array.
* 🔎 Finds all even numbers.
* 🔢 Counts the number of even numbers generated.

### 🧠 Concepts Used

* `np.random.randint()`
* Array filtering
* `len()`
* `np.sum()`

---

## 2️⃣ 🎲 Generate Random Dice Rolls

Simulated rolling a **six-sided dice 20 times** using NumPy.

### 🔍 The program:

* 🎲 Generates 20 random dice results.
* 📋 Displays the results.
* 🔢 Counts how many times the number `6` appeared.
* 📊 Calculates the percentage of rolls that resulted in `6`.

### 🧠 Concepts Used

* `np.random.randint()`
* Array filtering
* Counting
* Basic calculations
* `len()`

---

## 3️⃣ 🎓 Random Student Marks Analysis

Generated random marks for **10 students** in the range of **0 to 100**.

### 🔍 The program:

* 📋 Displays the student marks.
* 🏆 Finds the highest mark.
* 📉 Finds the lowest mark.
* 📊 Calculates the average mark.
* 🔎 Counts students who scored above `75`.
* 📋 Displays the marks of students who scored above `75`.

### 🧠 Concepts Used

* `np.random.randint()`
* `np.max()`
* `np.min()`
* `np.mean()`
* Array filtering
* `len()`

---

## 4️⃣ 🔢 Random Number Guessing Game

Created a **number guessing game** using a randomly generated number between **1 and 100**.

### 🎮 The program:

* 🎲 Generates a random number.
* ⌨️ Asks the user to enter guesses repeatedly.
* 🔼 Displays `Too High` when the guess is greater than the generated number.
* 🔽 Displays `Too Low` when the guess is smaller.
* ✅ Displays `Correct` when the number is guessed.
* 🔢 Counts and displays the number of attempts.

### 🧠 Concepts Used

* `np.random.randint()`
* `while` loop
* `input()`
* Conditional statements
* `break`
* Counter variables

---

## 5️⃣ 💰 Random Sales Data Generator and Analysis

Generated random daily sales data for **30 days** between **₹5,000 and ₹50,000**.

### 📊 The program:

* 🎲 Generates sales data for 30 days.
* 📅 Displays each day's sales using a `for` loop.
* 💵 Calculates total sales.
* 📊 Calculates average daily sales.
* 🏆 Finds the highest sales value.
* 📉 Finds the lowest sales value.
* 🔎 Identifies sales above the average.
* 📍 Finds the day with the highest sales.
* 🔢 Counts the number of days with sales above ₹30,000.

### 🧠 Concepts Used

* `np.random.randint()`
* `np.sum()`
* `np.mean()`
* `np.max()`
* `np.min()`
* `np.argmax()`
* Array filtering
* `for` loops
* Indexing
* Aggregation

---

## 6️⃣ 🔐 Random Password/OTP Security Simulation

Generated **100 random six-digit OTPs** and performed security-related analysis.

### 🔍 The program:

* 🔢 Generates 100 six-digit OTPs.
* ✨ Counts the number of unique OTPs.
* 🔁 Checks whether any OTP was generated more than once.
* 🔎 Identifies repeated OTPs.
* 🔐 Counts OTPs containing at least one repeated digit.

### 🧪 Examples

```text
123456 → ✅ No repeated digit
112345 → ⚠️ Repeated digit
778899 → ⚠️ Repeated digits
```

The program uses a **`for` loop** to examine the digits of each OTP.

### 🧠 Concepts Used

* `np.random.randint()`
* `np.unique()`
* `np.sum()`
* `for` loops
* Array filtering
* Indexing
* `set()`
* String manipulation
* `len()`
* Conditional statements
* List manipulation

---

# 🛠️ Technologies Used

| 🛠️ Technology          | 📌 Purpose                                  |
| ----------------------- | ------------------------------------------- |
| 🐍 **Python**           | Programming language                        |
| 🔢 **NumPy**            | Random data generation and array operations |
| 🟢 **Google Colab**     | Running and testing notebooks               |


---

# 🔧 NumPy Functions Used

| 🔧 Function           | 📖 Purpose                             |
| --------------------- | -------------------------------------- |
| `np.random.randint()` | 🎲 Generate random integers            |
| `np.unique()`         | ✨ Find unique values                   |
| `np.sum()`            | ➕ Calculate total or count conditions  |
| `np.mean()`           | 📊 Calculate average                   |
| `np.max()`            | 🏆 Find maximum value                  |
| `np.min()`            | 📉 Find minimum value                  |
| `np.argmax()`         | 📍 Find the index of the maximum value |

---

# 🧠 Key Concepts Practiced

Throughout these exercises, the following Python and NumPy concepts were practiced:

* 🎲 Random data generation
* 🔢 NumPy arrays
* 📍 Array indexing
* 🔎 Array filtering
* ☑️ Boolean conditions
* 🔄 `for` loops
* ♾️ `while` loops
* ⚙️ Conditional statements
* 🔢 `len()`
* ✨ `set()`
* 🔤 String conversion
* 📝 List manipulation
* 🔢 Counting values
* ✨ Finding unique values
* 🔁 Finding duplicate values
* 📊 Statistical calculations
* 🧮 Basic mathematical calculations

---

# 🎯 Learning Outcome

These exercises provide practical experience with **NumPy's random functionality and basic array operations**.

They demonstrate how randomly generated data can be analyzed in different real-world scenarios such as:

🎲 **Dice Simulation**
🎓 **Student Marks Analysis**
💰 **Sales Analysis**
🔢 **Number Guessing Game**
🔐 **OTP Security Analysis**

The exercises also strengthen understanding of:

> 🔄 Loops • ⚙️ Conditions • 🔎 Filtering • 📍 Indexing • 📊 Aggregation • 🔢 NumPy Functions

---


# 📈 Skills Demonstrated

```text
🐍 Python
    │
    ├── 🔢 NumPy
    ├── 🎲 Random Data Generation
    ├── 🔎 Array Filtering
    ├── 📊 Data Analysis
    ├── 🔄 Loops
    ├── ⚙️ Conditional Logic
    ├── 📍 Array Indexing
    ├── ✨ Unique & Duplicate Detection
    └── 🧮 Statistical Calculations
```

---

# 🏁 Conclusion

This project helped build a strong foundation in **NumPy random data generation and array analysis** through practical programming exercises.

From generating 🎲 random dice rolls and analyzing 🎓 student marks to studying 💰 sales data and 🔐 OTP patterns, each exercise demonstrates how NumPy can be applied to solve different data-related problems.

---

## 👩‍💻 Author

### **Abhi S**

🐍 Python | 📊 Data Analytics | 🔢 NumPy | 💻 Programming

