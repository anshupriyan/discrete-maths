---
title: "Recurrences"
date: 2026-05-29
tags:
  - Maths/Discrete/Recurrences
summary: "Study guide and learning tracker for Recurrence Relations."
---

# Chapter 06: Recurrences

This chapter examines recurrence relations—equations that recursively define sequences. In computer science, they are used to model and analyze the time complexity of recursive algorithms (e.g., merge sort, quicksort, dynamic programming).

---

## 🗺️ Learning Roadmap & Syllabus Checklist

Use this checklist to track your understanding of each topic. Mark items with `[x]` as you master them!

### 🟩 1. Introduction & Modeling
- [ ] **Definition**: Recurrence relation, initial conditions.
- [ ] **Modeling Problems**: 
  - Fibonacci numbers sequence
  - Towers of Hanoi
  - Counting bit strings without consecutive 0s
  - Compound interest

### 🟦 2. Solving Recurrence Relations
- [ ] **Linear Homogeneous Recurrences**:
  - Degree 1 & 2 definitions.
  - **Characteristic Equation**: Finding roots ($r^2 - c_1 r - c_2 = 0$).
  - **Distinct Roots Case**: $a_n = \alpha_1 r_1^n + \alpha_2 r_2^n$.
  - **Repeated Roots Case**: $a_n = (\alpha_1 + \alpha_2 n) r_1^n$.
- [ ] **Linear Non-Homogeneous Recurrences**:
  - Expressed as $a_n = a_n^{(h)} + a_n^{(p)}$ (homogeneous + particular solutions).
  - Guessing particular solutions based on the forcing function $F(n)$ (polynomials, exponentials).

### 🟨 3. Divide-and-Conquer Recurrences
- [ ] **Definition**: Recurrences of the form $T(n) = a T(n/b) + f(n)$.
- [ ] **The Master Theorem**: A highly useful method to find asymptotic bounds ($O$-notation) for divide-and-conquer recurrences.
- [ ] **Applications**: Analyzing Merge Sort ($T(n) = 2 T(n/2) + O(n)$), Binary Search ($T(n) = T(n/2) + O(1)$).
- [ ] **Generating Functions** *(Advanced topic)*: Using power series to solve recurrences.

---

## 🔑 Core Theorems Quick-Reference

### Master Theorem
For $T(n) = a T(n/b) + f(n)$ where $a \ge 1, b > 1$ and $f(n) = \Theta(n^d)$ with $d \ge 0$:
1. If $d < \log_b a$, then $T(n) = \Theta(n^{\log_b a})$
2. If $d = \log_b a$, then $T(n) = \Theta(n^d \log n)$
3. If $d > \log_b a$, then $T(n) = \Theta(n^d)$

### Characteristic Equation (Degree 2)
For $a_n = c_1 a_{n-1} + c_2 a_{n-2}$, solve:
$$r^2 - c_1 r - c_2 = 0$$

---

## 📝 Study Notes & Exercises
*Add your personal notes, examples, and solved problems here!*

---

## 🔗 Navigation
- [[Discrete Mathematics Dashboard|⬅️ Back to Course Dashboard]]
