---
title: "Sets, Relations and Functions"
date: 2026-05-29
tags:
  - Maths/Discrete/Sets
summary: "Study guide and learning tracker for Sets, Relations, and Functions."
---

# Chapter 01: Sets, Relations and Functions

This chapter covers the absolute foundational language of modern mathematics and computer science: sets (collections of objects), relations (how objects associate), and functions (rules that map inputs to outputs).

---

## 🗺️ Learning Roadmap & Syllabus Checklist

Use this checklist to track your understanding of each topic. Mark items with `[x]` as you master them!

### 🟩 1. Set Theory
- [ ] **Basic Definitions**: Sets, elements, subsets ($\subseteq$, $\subset$), power sets ($\mathcal{P}(S)$), cardinality ($|S|$) — [[01. Introduction to Sets|Intro Note]] \| [[02. Venn Diagrams, Subsets, and Cardinality|Subsets Note]] \| [[03. Power Sets|Power Sets Note]] \| [[09. Multisets|Multisets Note]]
- [ ] **Set Operations**: Union ($\cup$), intersection ($\cap$), set difference ($-$), symmetric difference ($\oplus$), complement ($A^c$) — [[05. Set Operations|Set Operations Note]] | [[07. Generalized Unions and Intersections|Generalized Note]] | [[08. Computer Representation of Sets|Computer Rep Note]]
- [ ] **Venn Diagrams**: Visualizing sets and operations — [[02. Venn Diagrams, Subsets, and Cardinality|Venn Diagrams Note]]
- [ ] **Set Identities**: Commutative, associative, distributive, De Morgan's laws (and how to prove them) — [[06. Proving Set Identities|Proving Set Identities Note]]

### 🟦 2. Relations
- [ ] **Cartesian Product**: $A \times B$ definition and cardinality — [[04. Cartesian Products|Cartesian Products Note]]
- [ ] **Binary Relations**: Definition, representation using Cartesian products, ordered pairs, and relations on a single set — [[20. Introduction to Relations|Intro to Relations Note]]
- [ ] **Functions as Relations**: Bridging functions and relations, the graph of a function as a relation subset, and the single-first-element function condition — [[21. Functions as Relations|Functions as Relations Note]]
- [ ] **Relations on a Set**: Subsets of $A \times A$, directed graphs (digraphs) visualization, loop/vertex mapping, and counting relations ($2^{n^2}$) — [[22. Relations on a Set|Relations on a Set Note]]
- [ ] **Properties of Relations**: Reflexive vs. irreflexive, symmetric vs. antisymmetric, and transitive relations with logical and graphical checks — [[23. Properties of Relations|Properties of Relations Note]]
- [ ] **Combining Relations**: Set operations on relations (union, intersection, difference), relational composition ($S \circ R$), and relational powers ($R^n$) — [[24. Combining Relations|Combining Relations Note]]
- [ ] **Representing Relations**: Zero-one matrices ($M_R$), rows/columns mappings, and determining properties (reflexive, symmetric) via matrix structures — [[25. Representing Relations|Representing Relations Note]] \| [[26. Representing Relations Using Digraphs|Digraphs Note]]
- [ ] **Equivalence Relations**: Definition (reflexive, symmetric, transitive), equivalence classes, and partitions.
- [ ] **Partial Orderings (Posets)**: Definition (reflexive, antisymmetric, transitive), Hasse diagrams, maximal/minimal elements, upper/lower bounds.

### 🟨 3. Functions
- [ ] **Definition**: Domain, codomain, range, image, and preimage — [[10. Introduction to Functions|Introduction to Functions Note]]
- [ ] **Types of Functions** — [[11. One-to-One and Onto Functions|One-to-One & Onto Functions Note]]
  - **Injective (One-to-One)**: $f(a) = f(b) \implies a = b$
  - **Surjective (Onto)**: Range equals Codomain
  - **Bijective**: Both injective and surjective (invertible)
- [ ] **Composition**: $(g \circ f)(x) = g(f(x))$ and its properties — [[12. Inverse Functions and Composition|Composition Note]]
- [ ] **Inverse Functions**: $f^{-1}(y) = x$ (exists iff $f$ is bijective) — [[12. Inverse Functions and Composition|Inverse Functions Note]]
- [ ] **Graphs of Functions**: Representing functions as ordered pairs $\{(a, b) \mid f(a) = b\}$ and plotting them — [[13. The Graphs of Functions|Graphs Note]]
- [ ] **Special Functions**: Floor ($\lfloor x \rfloor$), ceiling ($\lceil x \rceil$), and factorial ($n!$) — [[14. Floor and Ceiling Functions|Floor & Ceiling Note]]
- [ ] **Partial Functions**: Domain of definition, total functions, and representing undefined values — [[15. Partial Functions|Partial Functions Note]]

### 🟧 4. Sequences and Summations
- [ ] **Sequences**: Definition as functions, term notation ($a_n$), starting index variation ($0$ vs. $1$) — [[16. Introduction to Sequences|Intro to Sequences Note]]
- [ ] **Geometric & Arithmetic Progressions**: Common ratios ($r$), common differences ($d$), and discrete exponential/linear functional analogies — [[17. Geometric and Arithmetic Progressions|Progressions Note]]
- [ ] **Summations**: Sigma notation ($\sum$), limits of summation, index shifting, key summation formulas, and double summations — [[18. Summations|Summations Note]]
- [ ] **Principle of Inclusion-Exclusion**: Overlapping union cardinality for 2, 3, and n sets, alternating sum expansion, and Venn diagrams — [[19. The Principle of Inclusion-Exclusion|Inclusion-Exclusion Note]]

---

## 🔑 Core Formulas & Definitions Quick-Reference

### Cardinality of Power Set
$$|\mathcal{P}(S)| = 2^{|S|}$$

### De Morgan's Laws for Sets
$$(A \cup B)^c = A^c \cap B^c$$
$$(A \cap B)^c = A^c \cup B^c$$

### Composition order
For $f: A \to B$ and $g: B \to C$, the composition is $g \circ f: A \to C$.

---

## 📝 Study Notes & Exercises
- [[01. Introduction to Sets]] — Section 2.1.1: Comprehensive look at the foundational concept of a set, description methods, and standard boldface number sets.
- [[02. Venn Diagrams, Subsets, and Cardinality]] — Sections 2.1.2 - 2.1.4: Visualizing sets using Venn diagrams, subsets vs. proper subsets, set cardinality, and finite/infinite sets.
- [[03. Power Sets]] — Section 2.1.5: Detailed study on Power Sets, listing subsets, empty set subsets, nested empty sets, and the cardinality theorem.
- [[04. Cartesian Products]] — Section 2.1.6: Ordered pairs, n-tuples, definitions of Cartesian products of two or more sets, standard set powers, and introduction to binary relations.
- [[05. Set Operations]] — Sections 2.2 - 2.2.1: Foundations of set operations (union, intersection, disjoint sets, set difference, and absolute complement).
- [[06. Proving Set Identities]] — Section 2.2.2: The three primary methods used to prove set identities (mutual containment, set-builder with logical equivalence, and membership tables).
- [[07. Generalized Unions and Intersections]] — Section 2.2.3: Understanding set combinations across finite and infinite families of sets, indexed notations, and existential/universal quantifiers.
- [[08. Computer Representation of Sets]] — Section 2.2.4: Using ordered finite universal sets and bit strings to represent subsets, enabling ultra-fast low-level hardware bitwise logic operations.
- [[09. Multisets]] — Section 2.2.5: Unordered collections allowing multiple member repetitions, multiplicity notations, multiset operations, and cardinality sum rule.
- [[10. Introduction to Functions]] — Sections 2.3 - 2.3.1: Formal definition of mathematical functions, mappings, domain, codomain, range, subset images, and arithmetic operations on functions.
- [[11. One-to-One and Onto Functions]] — Section 2.3.2: Textbook classification of functions: one-to-one (injective), onto (surjective), and bijections, along with algebraic proofs and examples.
- [[12. Inverse Functions and Composition]] — Section 2.3.3: Formal definitions and textbook examples of inverse functions, domain restriction, composition of functions, and composition with identity/inverses.
- [[13. The Graphs of Functions]] — Section 2.3.4: Visualizing mathematical functions geometrically using sets of ordered pairs, coordinate plotting, and the vertical line test.
- [[14. Floor and Ceiling Functions]] — Section 2.3.5: Detailed study of Floor and Ceiling functions, step graphs, computer science data packing and transmission limits applications, and algebraic fractional proofs.
- [[15. Partial Functions]] — Section 2.3.6: Understanding partial functions, the domain of definition, total functions, and representing undefined values mathematically and computationally.
- [[16. Introduction to Sequences]] — Section 2.4.1: Foundational definition of sequences as functions, term notation, and index range variations.
- [[17. Geometric and Arithmetic Progressions]] — Section 2.4.2: Formal definitions and properties of geometric and arithmetic progressions, functional analogies, and textbook examples.
- [[18. Summations]] — Section 2.4.5: Sigma notation, limits, index shifting, closed-form summation formulas, and double summations.
- [[19. The Principle of Inclusion-Exclusion]] — Section 8.5: Formal study of the Principle of Inclusion-Exclusion (PIE) for 2, 3, and n sets, dynamic proofs via Venn diagrams, and textbook examples.
- [[20. Introduction to Relations]] — Sections 9.1 - 9.1.1: Foundational definition of binary relations, relations vs. functions, and relations on a single set.
- [[21. Functions as Relations]] — Section 9.1.2: Formal study of functions as restricted relations, the coordinate graph mapping, and conditions for relation-to-function conversion.
- [[22. Relations on a Set]] — Section 9.1.3: Defining and visualizing relations on a single set, directed graphs (digraphs) representation, and counting the total number of distinct relations.
- [[23. Properties of Relations]] — Section 9.1.4: Detailed study of reflexive, symmetric, antisymmetric, and transitive properties of relations on a set, with textbook examples and proof checking.
- [[24. Combining Relations]] — Section 9.1.5: Study of set-theoretic combinations of relations, relational composition rules, pathfinding representations, and relational powers.
- [[25. Representing Relations]] — Section 9.3: Representing relations on finite sets using zero-one matrices, matrix constructions, and evaluating reflexivity and symmetry via matrix structures.
- [[26. Representing Relations Using Digraphs]] — Section 9.3.3: Visualizing binary relations on finite sets using directed graphs (digraphs), examining relation properties visually, and solving textbook examples and exercises.

---

## 🔗 Navigation
- [[Discrete Mathematics Dashboard|⬅️ Back to Course Dashboard]]
