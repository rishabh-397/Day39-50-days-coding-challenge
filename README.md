# Day39-50-days-coding-challenge

## 🚀 Overview

Welcome to Day 39 of my 50 Days of Coding Challenge!  
Today’s problems focus on:
1. Inserting a new value in a Binary Search Tree (BST)
2. Removing adjacent duplicates from a string until stable

---

## 🌲 Problem 1: Insert into Binary Search Tree

### 🧩 Problem Statement
Insert a given value into a BST and return the root of the updated tree.  
The tree should retain the properties of a BST.

### 💡 Sample Input/Output
**Input:** root = [4,2,7,1,3], val = 5  
**Output:** [4,2,7,1,3,5]

### ✅ Constraints
- 0 ≤ number of nodes ≤ 10⁴
- All node values are unique
- Value to be inserted does not already exist in the BST

### 🧠 Approach
- Recursively traverse left/right subtree depending on value
- Insert when a null spot is found (base case)

---

## 🔁 Problem 2: Remove All Adjacent Duplicates in String

### 🧩 Problem Statement
Given a string `s`, perform duplicate removals (of adjacent equal characters) until none remain.

### 💡 Sample Input/Output
**Input:** s = "abbaca"  
**Output:** "ca"

### ✅ Constraints
- 1 ≤ s.length ≤ 10⁵
- Only lowercase letters

### 🧠 Approach
- Use a **stack** to keep characters.
- If the top matches the current character, pop.
- Else, push the character.

---

## 🧠 Learnings Today
- Recursive insertion in BST is clean and efficient.
- Stacks can simplify problems involving character manipulation and cleanup.
- Practice helps reduce the implementation time for commonly asked DSA problems.
