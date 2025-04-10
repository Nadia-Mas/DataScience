# 🔤 Word Anagrams – CS 5163 Project 1

Welcome to the **Word Anagrams** project, part of the **CS 5163: Data Science** course at **UTSA (Spring 2025)**. This project focuses on string manipulation, dictionary construction, and algorithmic logic using **Python data containers** such as lists and dictionaries.

> Instructor: Dr. Mohammad Imran Chowdhury  
> Due: February 11, 2025 at 11:59 PM  
> Total Points: 100

---

## 🧩 Project Description

In this project, we analyze a dictionary of English words to:
- Clean and normalize the word list.
- Group words by length.
- Find anagrams (words with the same letters) across word groups.

---

## 🚀 Tasks Breakdown

### ✅ Task 1: Dataset Setup
- Unzip and explore the dataset `words.zip`.
- List contents and confirm expected structure.

### ✅ Task 2: Word List Cleaning
- Load `words.txt` into a Python list (`wordlist`).
- Clean the list by:
  - Stripping whitespace/newlines
  - Converting to lowercase
  - Removing duplicates
  - Sorting lexicographically
- Save cleaned list to `wordclean`.

### ✅ Task 3: Group Words by Length
- Create a dictionary `words_bylength` where:
  - **Key** = word length
  - **Value** = list of words with that length

### ✅ Task 4: Find Anagrams
- Use a function like `anagram_fast(word)` to generate all anagrams.
- Create a dictionary `anagrams_bylength` to map each word group to its valid anagram sets.

---

## 💻 Tools & Technologies

- Python 3.6+
- Jupyter Notebook
- Data containers: `list`, `set`, `dict`
- Algorithms: sorting, dictionary lookup, string operations

---



