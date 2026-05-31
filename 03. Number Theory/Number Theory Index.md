---
title: "Number Theory"
date: 2026-05-29
tags:
  - Maths/Discrete/NumberTheory
summary: "Study guide and learning tracker for elementary Number Theory."
---

# Chapter 03: Number Theory

This chapter explores the properties of integers, modular arithmetic, prime numbers, divisibility, and how these mathematical concepts underpin modern computer science applications like cryptography (e.g., RSA encryption).

---

## 🗺️ Learning Roadmap & Syllabus Checklist

Use this checklist to track your understanding of each topic. Mark items with `[x]` as you master them!

### 🟩 1. Divisibility and Primes
- [ ] **Divisibility**: Definition of $a \mid b$. Division Algorithm ($a = dq + r$).
- [ ] **Prime Numbers**: Prime vs. composite numbers, Fundamental Theorem of Arithmetic (unique prime factorization).
- [ ] **Infinitude of Primes**: Understanding Euclid's proof.
- [ ] **Greatest Common Divisor (GCD) & LCM**: Definition, properties, relatively prime integers.
- [ ] **Euclidean Algorithm**: Computing GCD efficiently using repeated division.

### 🟦 2. Modular Arithmetic
- [ ] **Congruences**: $a \equiv b \pmod m$ definition and properties.
- [ ] **Modular Operations**: Addition and multiplication modulo $m$.
- [ ] **Applications**: Hashing functions, pseudorandom number generators, check digits (e.g., ISBN/UPC).

### 🟨 3. Advanced Number Theory & Theorems
- [ ] **Bézout's Identity**: $ax + by = \gcd(a, b)$.
- [ ] **Extended Euclidean Algorithm**: Finding Bézout coefficients $x$ and $y$.
- [ ] **Modular Inverse**: Finding $a^{-1} \pmod m$ (exists iff $\gcd(a, m) = 1$).
- [ ] **Linear Congruences**: Solving $ax \equiv b \pmod m$.
- [ ] **Chinese Remainder Theorem**: Solving systems of simultaneous linear congruences modulo pairwise coprime integers.
- [ ] **Fermat's Little Theorem**: $a^{p-1} \equiv 1 \pmod p$ for prime $p$ and $p \nmid a$.
- [ ] **Euler's Totient Function ($\phi(n)$)**: Definition and computation.
- [ ] **Euler's Generalization**: $a^{\phi(n)} \equiv 1 \pmod n$ for $\gcd(a, n) = 1$.

---

## 🔑 Core Theorems & Algorithms Quick-Reference

### Division Algorithm
For $a \in \mathbb{Z}$ and $d \in Z^+$, there exist unique integers $q$ and $r$ with $0 \le r < d$ such that:
$$a = dq + r$$

### Bézout's Identity
$$\gcd(a, b) = d \implies \exists x, y \in \mathbb{Z} \text{ such that } ax + by = d$$

### Fermat's Little Theorem
If $p$ is a prime and $a$ is an integer such that $p \nmid a$, then:
$$a^{p-1} \equiv 1 \pmod p \implies a^p \equiv a \pmod p$$

---

## 📝 Study Notes & Exercises
*Add your personal notes, examples, and solved problems here!*

---

## 🔗 Navigation
- [[Discrete Mathematics Dashboard|⬅️ Back to Course Dashboard]]
