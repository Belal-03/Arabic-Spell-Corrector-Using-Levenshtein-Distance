# 📝 Arabic Spell Corrector Using Levenshtein Distance

A Python program that corrects misspelled Arabic words by finding the closest correct word(s) from a predefined dictionary using the **minimum edit distance** (Levenshtein distance).

---

## 🔍 Overview

The program works by:

1. Accepting a **misspelled Arabic word** as input  
2. Comparing the input word against a **predefined dictionary** of correct Arabic words  
3. Calculating the **Levenshtein edit distance** (number of insertions, deletions, substitutions) between the input and each dictionary word  
4. Suggesting the closest matching word(s) as correction(s)  

---

## ⚙️ Features & Requirements

- Implementation of the **Levenshtein distance algorithm** using a **dynamic programming** approach  
- Supports Arabic text input and correction  
- Uses a **predefined word list** as the reference dictionary  
- Provides the best possible suggestions for misspelled words  

---

## 💻 Usage

- Run the Python script  
- Enter a misspelled Arabic word  
- Receive the suggested correction(s) based on minimum edit distance  
