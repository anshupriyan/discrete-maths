---
title: "Logic and Proofs"
date: 2026-05-29
tags:
  - Maths/Discrete/Logic
summary: "Study guide and learning tracker for Logic and Mathematical Proofs."
---

# Chapter 02: Logic and Proofs

This chapter introduces mathematical logic (how we formalize mathematical statements) and the techniques of formal mathematical proofs (how we establish mathematical truth beyond doubt).

> [!NOTE]
> **Textbook Reference:** All topics and page ranges correspond directly to the textbook extract:
> [[RosenDiscreteMath8Ed Extract[24-56,63-69,96-102,107-118,354-366]chapter 2.pdf|Rosen 8th Edition Extract - Chapter 2 (Logic & Proofs)]]. 
> For the targeted mapping of pages to sections, see the [[RosenDiscreteMath8Ed Extract[24-56,63-69,96-102,107-118,354-366]chapter 2 - Index|Syllabus Extract Index Note]].

---

## 🗺️ Learning Roadmap & Syllabus Checklist

Use this checklist to track your understanding of each topic. Mark items with `[x]` as you master them!

### 🟩 1. Propositional Logic
- [ ] **Propositions**: Definition, truth values — [[02. Introduction to Propositional Logic|Intro Note]]
- [ ] **Logical Operators**: Negation ($\neg$), conjunction ($\land$), disjunction ($\lor$), exclusive or ($\oplus$) — [[02. Introduction to Propositional Logic|Operators Note]]
- [ ] **Conditional Statements**: Implication ($p \to q$), converse ($q \to p$), contrapositive ($\neg q \to \neg p$), and inverse ($\neg p \to \neg q$) — [[03. Conditional Statements|Conditional Note]]
- [ ] **Biconditional**: $p \leftrightarrow q$ (if and only if) — [[03. Conditional Statements|Biconditional Note]]
- [ ] **Truth Tables**: Constructing tables to evaluate compound propositions — [[04. Truth Tables and Operator Precedence|Truth Tables Note]]
- [ ] **Bit Operations**: Boolean variables, bit strings, bitwise AND, OR, XOR operations — [[05. Logic and Bit Operations|Bit Ops Note]]
- [ ] **Applications of Propositional Logic**: Translating English sentences, system specifications, logic puzzles, logic gates — [[06. Translating English Sentences|Translation Note]] \| [[07. System Specifications and Consistency|Specs Note]] \| [[08. Boolean Searches|Searches Note]] \| [[09. Logic Puzzles|Puzzles Note]] \| [[10. Logic Circuits|Circuits Note]]
- [ ] **Logical Equivalences**: Tautologies, contradictions, contingencies. De Morgan's laws for logic. — [[11. Propositional Equivalences|Equivalences Note]]

### 🟦 2. Predicates and Quantifiers
- [ ] **Predicates**: Open statements $P(x)$ containing variables. — [[12. Predicates and Quantifiers|Predicates Note]]
- [ ] **Quantifiers**:
  - **Universal Quantifier ($\forall$)**: "For all"
  - **Existential Quantifier ($\exists$)**: "There exists"
- [ ] **Negating Quantified Statements**: De Morgan's laws for quantifiers ($\neg \forall x P(x) \equiv \exists x \neg P(x)$).
- [ ] **Nested Quantifiers**: Statements with multiple quantifiers (e.g., $\forall x \exists y Q(x, y)$) and the importance of order.

### 🟨 3. Rules of Inference & Proof Methods
- [ ] **Rules of Inference**: Modus Ponens, Modus Tollens, Hypothetical Syllogism, Disjunctive Syllogism. — [[13. Rules of Inference|Rules Note]]
- [ ] **Direct Proofs**: Standard algebraic proofs assuming $p$ is true and showing $q$ must be true. — [[14. Introduction to Proofs|Direct Proof Note]]
- [ ] **Proof by Contraposition**: Proving $p \to q$ by proving $\neg q \to \neg p$. — [[14. Introduction to Proofs|Contraposition Note]]
- [ ] **Proof by Contradiction**: Assuming the negation of what you want to prove, and deriving a logical contradiction (e.g., proving $\sqrt{2}$ is irrational).
- [ ] **Proof by Cases**: Exhausting all possible subsets of scenarios.
- [ ] **Mathematical Induction**:
  - **Weak Induction**: Base case, Inductive hypothesis ($P(k)$), Inductive step ($P(k+1)$). — [[15. Mathematical Induction|Induction Note]]
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
- [[01. Introduction to Logic and Proofs]] — Chapter Overview: Introduction to logic, mathematical vocabulary (proofs, theorems, conjectures), and the importance of rigorous proof construction in computer science.
- [[02. Introduction to Propositional Logic]] — Section 1.1: Foundations of propositional logic, defining propositions, atomic propositions, examples/non-examples, and propositional/Boolean variables.
- [[03. Conditional Statements]] — Section 1.1.3: Core guide to implications ($p \rightarrow q$), converse, inverse, contrapositive, logical equivalences, programming vs. logical if-then statements, and biconditionals ($p \leftrightarrow q$) with comprehensive truth tables.
- [[04. Truth Tables and Operator Precedence]] — Sections 1.1.4 - 1.1.5: Guide to constructing truth tables ($2^n$ rows), step-by-step intermediate column evaluation, and the official hierarchy of logical operator precedence.
- [[05. Logic and Bit Operations]] — Section 1.1.6: Mapping truth values to bits (0/1), Boolean variables, bit strings, and bitwise logical operations (AND, OR, XOR) with vertical alignment walkthroughs.
- [[06. Translating English Sentences]] — Section 1.2.2: Strategies for translating natural language statements into unambiguous formal propositional logic expressions with step-by-step textbook evaluations.
- [[07. System Specifications and Consistency]] — Section 1.2.3: Engineering applications of logic to system requirements, mathematical definitions of system consistency, and step-by-step consistency proofs.
- [[08. Boolean Searches]] — Section 1.2.4: Applications of logic to web search querying, logic connectives (AND, OR, NOT) in Boolean searches, and Google search syntax.
- [[09. Logic Puzzles]] — Section 1.2.5: Solved logic puzzles including King's Treasure trunks (deductive elimination), Raymond Smullyan's Knights and Knaves island (self-reference), and Muddy Children (epistemic common knowledge).
- [[10. Logic Circuits]] — Section 1.2.6: Digital hardware logic gates (NOT, OR, AND), tracing combinatorial circuits, and designing physical circuit blueprints from boolean target expressions.
- [[11. Propositional Equivalences]] — Section 1.3: Introduction to propositional equivalences, defining tautologies, contradictions, and contingencies.
- [[12. Predicates and Quantifiers]] — Section 1.4: Introduction to predicate logic, expressing statements in terms of subjects and predicates, and the motivation for predicates and quantifiers.
- [[13. Rules of Inference]] — Section 1.6: Introduction to rules of inference, defining argument forms, premises, and logical validity.
- [[14. Introduction to Proofs]] — Section 1.7: Basic proof terminology (theorems, lemmas, axioms, conjectures) and definitions of parity (even/odd integers).
- [[15. Mathematical Induction]] — Section 5.1: Introduction to mathematical induction, basic base steps, inductive hypotheses, and summation/inequality proofs.

---

## 🔗 Navigation
- [[Discrete Mathematics Dashboard|⬅️ Back to Course Dashboard]]
