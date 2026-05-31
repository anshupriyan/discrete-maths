---
title: "Logic and Proofs"
date: 2026-05-29
tags:
  - Maths/Discrete/Logic
summary: "Study guide and learning tracker for Logic and Mathematical Proofs."
---

# Chapter 02: Logic and Proofs

This chapter introduces mathematical logic (how we formalize mathematical statements) and the techniques of formal mathematical proofs (how we establish mathematical truth beyond doubt).

---

## 🗺️ Learning Roadmap & Syllabus Checklist

Use this checklist to track your understanding of each topic. Mark items with `[x]` as you master them!

### 🟩 1. Propositional Logic
- [ ] **Propositions**: Definition, truth values.
- [ ] **Logical Operators**: Negation ($\neg$), conjunction ($\land$), disjunction ($\lor$), exclusive or ($\oplus$).
- [ ] **Conditional Statements**: Implication ($p \to q$), converse ($q \to p$), contrapositive ($\neg q \to \neg p$), and inverse ($\neg p \to \neg q$).
- [ ] **Biconditional**: $p \leftrightarrow q$ (if and only if).
- [ ] **Truth Tables**: Constructing tables to evaluate compound propositions.
- [ ] **Logical Equivalences**: Tautologies, contradictions, contingencies. De Morgan's laws for logic.

### 🟦 2. Predicates and Quantifiers
- [ ] **Predicates**: Open statements $P(x)$ containing variables.
- [ ] **Quantifiers**:
  - **Universal Quantifier ($\forall$)**: "For all"
  - **Existential Quantifier ($\exists$)**: "There exists"
- [ ] **Negating Quantified Statements**: De Morgan's laws for quantifiers ($\neg \forall x P(x) \equiv \exists x \neg P(x)$).
- [ ] **Nested Quantifiers**: Statements with multiple quantifiers (e.g., $\forall x \exists y Q(x, y)$) and the importance of order.

### 🟨 3. Rules of Inference & Proof Methods
- [ ] **Rules of Inference**: Modus Ponens, Modus Tollens, Hypothetical Syllogism, Disjunctive Syllogism.
- [ ] **Direct Proofs**: Standard algebraic proofs assuming $p$ is true and showing $q$ must be true.
- [ ] **Proof by Contraposition**: Proving $p \to q$ by proving $\neg q \to \neg p$.
- [ ] **Proof by Contradiction**: Assuming the negation of what you want to prove, and deriving a logical contradiction (e.g., proving $\sqrt{2}$ is irrational).
- [ ] **Proof by Cases**: Exhausting all possible subsets of scenarios.
- [ ] **Mathematical Induction**:
  - **Weak Induction**: Base case, Inductive hypothesis ($P(k)$), Inductive step ($P(k+1)$).
  - **Strong Induction**: Using the assumption that $P(i)$ is true for all $1 \le i \le k$ to prove $P(k+1)$.

---

## 🔑 Core Laws & Equivalences Quick-Reference

### Implication Equivalence
$$p \to q \equiv \neg p \lor q$$

### Contrapositive Equivalence
$$p \to q \equiv \neg q \to \neg p$$

### De Morgan's Laws (Logic)
$$\neg(p \land q) \equiv \neg p \lor \neg q$$
$$\neg(p \lor q) \equiv \neg p \land \neg q$$

---

## 📝 Study Notes & Exercises
*Add your personal notes, examples, and solved problems here!*

---

## 🔗 Navigation
- [[Discrete Mathematics Dashboard|⬅️ Back to Course Dashboard]]
