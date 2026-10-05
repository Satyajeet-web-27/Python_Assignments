# 🐍 Python String Assignment — Beginner Level

## Topics Covered

- Creating strings
- `input()`
- Indexing
- Slicing
- `len()`
- `upper()` / `lower()`
- `strip()`
- `replace()`
- `count()`
- `find()`
- String concatenation

---

# Part A — Basic String Operations

## 1. Print a String

Write a Python program to store your name in a variable and print it.

**Example:**

```text
Enter your name: Polu
Output: Hello Polu
```

---

## 2. Find String Length

Take a name as input and display the number of characters.

```text
Input: Polu
Output: Length = 4
```

---

## 3. Uppercase and Lowercase

Take a sentence as input and display:

- The sentence in uppercase
- The sentence in lowercase

```text
Input: Python is Easy

Output:
PYTHON IS EASY
python is easy
```

---

## 4. First and Last Character

Take a word as input and print its:

- First character
- Last character

```text
Input: Computer

Output:
First character: C
Last character: r
```

---

## 5. Reverse a String

Take a string from the user and print it in reverse.

```text
Input: Python
Output: nohtyP
```

**Hint:** Use slicing.

---

# Part B — String Methods

## 6. Remove Extra Spaces

Take a string containing spaces at the beginning and end. Remove them using `strip()`.

```text
Input: "   Hello Python   "

Output: "Hello Python"
```

---

## 7. Replace a Word

Take a sentence and replace `"Python"` with `"Programming"`.

```text
Input:
I love Python.

Output:
I love Programming.
```

---

## 8. Count a Character

Take a string and a character from the user. Count how many times the character appears.

```text
Enter string: banana
Enter character: a

Output:
a appears 3 times
```

---

## 9. Find a Word

Take a sentence and a word from the user. Check whether the word exists in the sentence using `find()`.

```text
Sentence: I love Python programming
Word: Python

Output:
Word found
```

---

## 10. Check Starting and Ending

Take a word from the user and check:

- Does it start with `"A"`?
- Does it end with `"ing"`?

**Hint:** Use:

```python
startswith()
endswith()
```

---

# Part C — Small Programs

## 11. Full Name

Take first name and last name separately and combine them.

```text
Enter first name: Polu
Enter last name: Roy

Output:
Full Name: Polu Roy
```

---

## 12. Email Username

Take an email address and extract the username.

```text
Input:
polu@gmail.com

Output:
Username: polu
```

**Hint:** Use `find()` or `split()`.

---

## 13. Character Counter

Take a sentence and display:

```text
Total characters:
Total spaces:
Number of 'a':
```

**Example:**

```text
Input:
I am learning Python

Output:
Total characters: 20
Total spaces: 3
Number of 'a': 2
```

---

## 14. Vowel Counter

Take a string and count the total number of vowels.

```text
Input: education

Output:
Number of vowels: 5
```

**Hint:**

```python
if ch in "aeiou":
```

---

## 15. Simple Password Checker

Take a password from the user.

Check whether:

- Length is at least 8 characters
- It contains `"@"`

**Example:**

```text
Enter password: hello@123

Output:
Password accepted
```

---

# ⭐ Challenge Problems

## 16. Palindrome Checker

Check whether a word reads the same forward and backward.

```text
Input: madam
Output: Palindrome
```

```text
Input: python
Output: Not Palindrome
```

**Hint:**

<details>
    <summary>
        Hint:
    </summary>
    word == word[::-1]
</details>

---

## 17. Count Words

Take a sentence and count the number of words.

```text
Input:
Python is very easy

Output:
Number of words: 4
```

**Hint:** Use:

```python
split()
```

---

## 18. Convert Name Format

Take a full name and convert it to uppercase.

```text
Input:
polu roy

Output:
POLU ROY
```

Then display:

```text
First character: P
Last character: Y
```

---

# 🎯 Mini Project: Student Introduction

Write a program that asks the user for:

- Name
- Age
- Course
- College
- City

Then generate:

```text
----- STUDENT INTRODUCTION -----

My name is Polu.
I am 20 years old.
I am studying B.Sc.
I study at ABC College.
I live in Hooghly.

-------------------------------
```

---

# 📚 Recommended Practice Order

### Level 1 — String Basics

1. Print a String
2. Find String Length
3. Uppercase and Lowercase
4. First and Last Character
5. Reverse a String

### Level 2 — String Methods

6. Remove Extra Spaces
7. Replace a Word
8. Count a Character
9. Find a Word
10. Check Starting and Ending

### Level 3 — Small Programs

11. Full Name
12. Email Username
13. Character Counter
14. Vowel Counter
15. Simple Password Checker

### Challenge

16. Palindrome Checker
17. Count Words
18. Convert Name Format

### Mini Project

**Student Introduction Program**
