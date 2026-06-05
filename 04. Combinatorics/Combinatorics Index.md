---
title: "Combinatorics"
date: 2026-05-29
tags:
  - Maths/Discrete/Combinatorics
summary: "Study guide and learning tracker for Combinatorics and Counting principles."
---

# Chapter 04: Combinatorics

This chapter focuses on the art of counting—determining the number of elements in finite sets, arranging structures, and calculating possibilities without enumerating them explicitly. This is vital for analyzing algorithms and computing probabilities.

> [!NOTE]
> **Textbook Reference:** All topics correspond directly to the textbook extract:
> [[combi.pdf|Combinatorics Core Extract]]. (For details, see [[combi - Index|Resource Index Note]]).

---

## 🗺️ Learning Roadmap & Syllabus Checklist

Use this checklist to track your understanding of each topic. Mark items with `[x]` as you master them!

### 🟩 1. Basic Counting Rules
- [x] **Sum Rule**: [[01. Basic Counting Rules|If tasks are disjoint, select task 1 OR task 2 ($n_1 + n_2$)]].
- [x] **Product Rule**: [[01. Basic Counting Rules|If tasks are sequential, perform task 1 AND task 2 ($n_1 \times n_2$)]].
- [x] **Subtraction Rule (Inclusion-Exclusion)**: [[01. Basic Counting Rules|For non-disjoint sets ($|A \cup B| = |A| + |B| - |A \cap B|$)]] — See also [[19. The Principle of Inclusion-Exclusion|Inclusion-Exclusion Note]].
- [x] **Division Rule**: [[01. Basic Counting Rules|Adjusting count when elements are counted multiple equivalent times ($n / d$)]].
- [ ] **Tree Diagrams**: Representing multi-step outcomes visually.

### 🟦 2. Permutations and Combinations
- [x] **Permutations**: [[02. Permutations and Combinations|Order matters. Choosing $r$ elements from $n$ elements ($P(n, r)$)]].
- [x] **Combinations**: [[02. Permutations and Combinations|Order does NOT matter. Choosing $r$ elements from $n$ elements ($C(n, r)$ or $\binom{n}{r}$)]].
- [ ] **Permutations with Repetition**: Multi-set arrangements ($n! / (n_1! n_2! \dots n_k!)$).
- [ ] **Combinations with Repetition**: Stars and bars method ($\binom{n+r-1}{r}$).
- [ ] **Binomial Coefficients**: Properties and Pascal's Triangle.
- [ ] **Binomial Theorem**: Expanding $(x+y)^n$ and utilizing algebraic properties.

### 🟨 3. Advanced Principles
- [x] **Pigeonhole Principle**: [[03. Pigeonhole Principle|Basic formulation (if $n+1$ pigeons are placed into $n$ holes, at least one hole has $\ge 2$ pigeons)]].
- [x] **Generalized Pigeonhole Principle**: [[03. Pigeonhole Principle|If $N$ objects are placed into $k$ boxes, at least one box contains $\ge \lceil N/k \rceil$ objects]].
- [ ] **Inclusion-Exclusion Principle**: Finding cardinality of union of $n$ sets — See also [[19. The Principle of Inclusion-Exclusion|Inclusion-Exclusion Note]].

---

## 🔑 Core Formulas Quick-Reference

### Permutations (No Repetition)
$$P(n, r) = \frac{n!}{(n-r)!}$$

### Combinations (No Repetition)
$$C(n, r) = \binom{n}{r} = \frac{n!}{r!(n-r)!}$$

### Combinations with Repetition (Stars & Bars)
$$\binom{n+r-1}{r}$$

### Binomial Theorem
$$(x+y)^n = \sum_{k=0}^{n} \binom{n}{k} x^{n-k} y^k$$

---

## 📝 Study Notes & Exercises
- [[01. Basic Counting Rules]] — Section 3.2: Formal study of basic counting principles including the Sum, Product, Subtraction, and Division Rules.
- [[02. Permutations and Combinations]] — Section 3.3 - 3.4: Thorough study of permutations ($P(n,r)$) and combinations ($C(n,r)$) with derivations, formulas, differences, and worked examples.
- [[03. Pigeonhole Principle]] — Section 6.2: Detailed study of the Pigeonhole Principle and Generalized Pigeonhole Principle, including proofs, worst-case scenario strategies, and advanced application proofs.
- [[19. The Principle of Inclusion-Exclusion]] — Section 8.5: Formal study of the Principle of Inclusion-Exclusion (PIE) for 2, 3, and n sets, dynamic proofs via Venn diagrams, and textbook examples.

---

## 🔗 Navigation
- [[Discrete Mathematics Dashboard|⬅️ Back to Course Dashboard]]
