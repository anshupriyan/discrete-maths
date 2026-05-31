---
title: "Graphs and Trees"
date: 2026-05-29
tags:
  - Maths/Discrete/GraphsAndTrees
summary: "Study guide and learning tracker for Graphs and Trees."
---

# Chapter 05: Graphs and Trees

This chapter covers the properties and applications of graphs (collections of vertices and edges) and trees (acyclic connected graphs). These mathematical structures are fundamental to data structures, networking, routing, and database theory.

---

## 🗺️ Learning Roadmap & Syllabus Checklist

Use this checklist to track your understanding of each topic. Mark items with `[x]` as you master them!

### 🟩 1. Graph Fundamentals
- [ ] **Terminology**: Vertices ($V$), edges ($E$), degrees ($\text{deg}(v)$), adjacent/incident.
- [ ] **The Handshaking Lemma**: Sum of degrees equals twice the number of edges.
- [ ] **Graph Families**: Simple graphs, multigraphs, pseudographs, directed graphs, complete graphs ($K_n$), cycles ($C_n$), wheels ($W_n$), bipartite graphs ($K_{m,n}$).
- [ ] **Graph Representations**: Adjacency lists, adjacency matrices, incidence matrices.
- [ ] **Isomorphism**: Determining if two graphs have identical structures.

### 🟦 2. Connectivity, Paths, and Circuits
- [ ] **Paths & Circuits**: Walk, path, cycle, circuit definitions.
- [ ] **Connectedness**: Strongly vs. weakly connected in digraphs, connected components.
- [ ] **Euler Paths & Circuits**: Traverses every edge exactly once (exist iff even degrees or exactly two vertices of odd degree).
- [ ] **Hamilton Paths & Circuits**: Visits every vertex exactly once.
- [ ] **Shortest-Path Algorithms**: Dijkstra's algorithm, Traveling Salesperson Problem (TSP) overview.
- [ ] **Planar Graphs & Euler's Formula**: $R = E - V + 2$.
- [ ] **Graph Coloring**: Chromatic number ($\chi(G)$), Four Color Theorem.

### 🟨 3. Trees
- [ ] **Definition**: Aconnected undirected graph with no simple circuits (forest = multiple trees).
- [ ] **Properties**: A tree with $n$ vertices has exactly $n-1$ edges.
- [ ] **Rooted Trees**: Parent, child, sibling, ancestor, descendant, leaf, internal vertex, subtree.
- [ ] **Binary Trees**: $m$-ary trees, balanced trees, height.
- [ ] **Tree Traversals**: Preorder, inorder, postorder traversals.
- [ ] **Spanning Trees**: Finding a spanning tree in a connected graph.
- [ ] **Minimum Spanning Trees (MST)**: Prim's Algorithm and Kruskal's Algorithm.

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

## 📝 Study Notes & Exercises
*Add your personal notes, examples, and solved problems here!*

---

## 🔗 Navigation
- [[Discrete Mathematics Dashboard|⬅️ Back to Course Dashboard]]
