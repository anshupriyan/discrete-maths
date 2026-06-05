---
title: "Graphs and Trees"
date: 2026-05-29
tags:
  - Maths/Discrete/GraphsAndTrees
summary: "Study guide and learning tracker for Graphs and Trees."
---

# Chapter 05: Graphs and Trees

This chapter covers the properties and applications of graphs (collections of vertices and edges) and trees (acyclic connected graphs). These mathematical structures are fundamental to data structures, networking, routing, and database theory.

> [!NOTE]
> **Textbook Reference:** All topics and page ranges correspond directly to the textbook extract:
> [[graph and trees.pdf|Graphs and Trees Extract - Chapter 10 & 11]].
> For the targeted mapping of pages to sections, see the [[graph and trees - Index|Graphs and Trees Resource Index Note]].

---

## 🗺️ Learning Roadmap & Syllabus Checklist

Use this checklist to track your understanding of each topic. All topics listed below correspond to the targeted course syllabus!

### 🟩 1. Graph Fundamentals & Representations
- [x] **Terminology**: [[01. Introduction to Graphs|Vertices ($V$), edges ($E$), degrees ($\text{deg}(v)$), adjacent/incident]].
- [x] **The Handshaking Lemma**: [[01. Introduction to Graphs|Sum of degrees equals twice the number of edges]].
- [x] **Graph Families**: [[01. Introduction to Graphs|Simple graphs, complete graphs ($K_n$), cycles ($C_n$), wheels ($W_n$), bipartite, complete bipartite ($K_{m,n}$)]].
- [x] **Graph Representations**: [[02. Graph Representations and Isomorphism|Adjacency lists, adjacency matrices, and incidence matrices]].
- [x] **Isomorphism**: [[02. Graph Representations and Isomorphism|Mathematical definition, bijections, and isomorphic invariants]].

### 🟦 2. Connectivity, Paths, and Algorithms
- [x] **Paths & Circuits**: [[03. Connectivity and Paths|Walks, simple paths, circuits, and simple circuits]].
- [x] **Connectedness**: [[03. Connectivity and Paths|Connected components, strongly vs. weakly connected digraphs, cut vertices, and bridges]].
- [x] **Paths & Isomorphism**: [[03. Connectivity and Paths|Path-related structural invariants (cycles, paths of length $k$)]].
- [x] **Path Counting**: [[03. Connectivity and Paths|Calculating paths between vertices using adjacency matrix powers ($A^r$)]].
- [x] **Euler Paths & Circuits**: [[04. Euler and Hamilton Paths|Traversing every edge exactly once, existence conditions]].
- [x] **Hamilton Paths & Circuits**: [[04. Euler and Hamilton Paths|Visiting every vertex exactly once, Dirac's and Ore's Theorems]].
- [x] **Applications of Hamilton Circuits**: [[04. Euler and Hamilton Paths|Traveling Salesperson Problem (TSP) and Gray codes]].
- [x] **Shortest-Path Algorithms**: [[05. Shortest-Path Problems and Dijkstra|Dijkstra's shortest path algorithm trace on weighted graphs]].

### 🟪 3. Planar Graphs
- [x] **Planar Representations**: [[06. Planar Graphs|Drawing graphs without crossings, region degrees]].
- [x] **Euler's Formula**: [[06. Planar Graphs|Euler's formula ($R = E - V + 2$) with algebraic proofs of corollaries ($E \le 3V - 6$ and $E \le 2V - 4$)]].
- [x] **Nonplanarity Proofs**: [[06. Planar Graphs|Proving K_5 and K_3,3 are nonplanar using Euler's formula bounds]].
- [x] **Kuratowski's Theorem**: [[06. Planar Graphs|forbidden subgraphs, homeomorphisms, and subdivisions]].

### 🟨 4. Trees
- [x] **Definition**: [[07. Introduction to Trees and Properties|Connected acyclic graphs, forests, and unique path theorem]].
- [x] **Tree Edge Theorem**: [[07. Introduction to Trees and Properties|Theorem 2: A tree with n vertices has exactly n - 1 edges (with mathematical induction proof)]].

---

## 🔑 Core Theorems & Formulas Quick-Reference

### The Handshaking Lemma
$$\sum_{v \in V} \text{deg}(v) = 2|E|$$

### Tree Edge Formula
For any tree $T = (V, E)$:
$$|E| = |V| - 1$$

### Euler's Formula for Planar Graphs
For a connected planar graph with $V$ vertices, $E$ edges, and $R$ regions:
$$R = E - V + 2$$

---

## 📝 Study Notes
- [[01. Introduction to Graphs]] — Basic graph models, terminology, isolated/pendant vertices, Handshaking Lemma (with proof), and special graph families.
- [[02. Graph Representations and Isomorphism]] — Representing graphs via lists/matrices, sparse/dense trade-offs, and isomorphism invariants.
- [[03. Connectivity and Paths]] — Paths, connectedness (undirected/directed), paths-isomorphism invariants, cut vertices, bridges, and path counting using $A^r$ powers (with proof).
- [[04. Euler and Hamilton Paths]] — Euler and Hamilton paths/circuits, Dirac's and Ore's Theorems, TSP, and Gray codes.
- [[05. Shortest-Path Problems and Dijkstra]] — Shortest-path problems on weighted graphs and Dijkstra's algorithm.
- [[06. Planar Graphs]] — Planar graphs, Euler's formula with corollary proofs, nonplanarity of $K_5$ and $K_{3,3}$, and Kuratowski's Theorem.
- [[07. Introduction to Trees and Properties]] — Trees/forests, unique path theorem, and tree edge theorem ($E = V - 1$) with mathematical induction proof.

---

## 🔗 Navigation
- [[Discrete Mathematics Dashboard|⬅️ Back to Course Dashboard]]
