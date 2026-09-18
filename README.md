# 🔢 Number To Text Converter (C++)

An efficient numerical-to-string translation algorithm implemented in modern C++ utilizing recursion and modular tokenization to parse numbers into written English words (up to Billions).

---

## 🚀 Key Features

* **Recursive Decomposition:** Breaks down large numbers into natural magnitude boundaries (Hundreds, Thousands, Millions, Billions) dynamically.
* **Grammatical Accuracy:** Accurately formats singular vs. plural cases (e.g., *One Thousand* vs. *Thousands*).
* **Defensive Termination:** Includes base-case safeguards to handle zero values and prevent infinite recursion loops.
* **Zero-Based Mapping Optimization:** Employs zero-offset indexed arrays to map direct numerical tokens without redundant arithmetic subtractions.

---

## 🛠️ Concepts & Technologies Applied

* **Language:** C++
* **Core Technique:** Recursion & Modular Arithmetic (`/` and `%` operators)
* **Data Mapping:** Array lookups with optimized indexing
* **Clean Code:** Separation of concerns between numerical parsing and console rendering

---

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/abdulkaremsuliman646-collab/Number-To-Text-Converter-CPP.git](https://github.com/abdulkaremsuliman646-collab/Number-To-Text-Converter-CPP.git)
