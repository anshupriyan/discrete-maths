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

Use this checklist to track your understanding of each topic. All topics listed below correspond to Chapters 9 and 10 of Liu & Mohapatra's *Elements of Discrete Mathematics*!

### 🟩 1. Discrete Numeric Functions
- [x] **Definition & Notation**: [[01. Introduction to Discrete Numeric Functions|Real-valued functions with domain \mathbb{N}_0, notation a_n or a(n)]].
- [x] **Basic Operations**: [[02. Operations on Numeric Functions|Addition, product, and scalar multiplication of numeric functions]].
- [x] **Shift Operators**: [[02. Operations on Numeric Functions|Forward shift (delay) S^k and backward shift (advance) S^{-k}]].
- [x] **Difference Operators**: [[02. Operations on Numeric Functions|Forward difference \Delta and backward difference \nabla]].
- [x] **Accumulated Sums**: [[02. Operations on Numeric Functions|Accumulated sums of numeric functions]].
- [x] **Convolution**: [[02. Operations on Numeric Functions|Convolution product (a * b) definition and properties]].

### 🟦 2. Recurrence Relations & Modeling
- [x] **Definition**: [[03. Recurrence Relations and Modeling|Recurrence relations, order, degree, linear vs. non-linear, and initial conditions]].
- [x] **Modeling Problems**: [[03. Recurrence Relations and Modeling|Fibonacci numbers, Towers of Hanoi, counting bit strings, and compound interest]].

### 🟪 3. Solving Linear Recurrence Relations
- [x] **Homogeneous Linear Recurrences**: [[04. Solving Homogeneous Linear Recurrences|Solving homogeneous recurrence relations with constant coefficients, characteristic equation, distinct and repeated roots]].
- [x] **Non-Homogeneous Linear Recurrences**: [[05. Solving Non-Homogeneous Linear Recurrences|General solution structure (homogeneous + particular) and finding particular solutions using the method of undetermined coefficients]].

---

## 🔑 Core Formulas & Definitions Quick-Reference

### Shift Operators
* **Forward Shift (Delay):**
  $$S^k a(n) = \begin{cases} 0 & \text{if } 0 \le n < k \\ a(n - k) & \text{if } n \ge k \end{cases}$$
* **Backward Shift (Advance):**
  $$S^{-k} a(n) = a(n + k), \quad n \ge 0$$

### Convolution
$$(a * b)(n) = \sum_{i=0}^{n} a(i) b(n - i)$$

### Linear Recurrence with Constant Coefficients (Degree $k$)
$$c_0 a_n + c_1 a_{n-1} + \dots + c_k a_{n-k} = f(n)$$
* Homogeneous if $f(n) = 0$; Non-homogeneous if $f(n) \ne 0$.

---

## 📝 Study Notes
- [[01. Introduction to Discrete Numeric Functions]] — Definition of discrete numeric functions, graphing, and standard examples.
- [[02. Operations on Numeric Functions]] — Addition, product, scalar product, forward/backward shift operators, difference operators, accumulated sums, and convolution.
- [[03. Recurrence Relations and Modeling]] — Definitions of recurrence relations, order/degree, initial conditions, and modeling classic sequences.
- [[04. Solving Homogeneous Linear Recurrences]] — Derivation of characteristic equations, distinct roots case, repeated roots case, and step-by-step solved examples.
- [[05. Solving Non-Homogeneous Linear Recurrences]] — Solving non-homogeneous linear recurrences using the method of undetermined coefficients for polynomial and exponential forcing functions.

---

## 🔗 Navigation
- [[Discrete Mathematics Dashboard|⬅️ Back to Course Dashboard]]
