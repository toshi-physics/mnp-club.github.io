---
layout: event
title: Talk on Graph Theory
pseudo_title: Talk on Graph Theory
modified:
categories: events
excerpt:
tags: []
image:
  feature:
date: 2016-09-23T23:18:04+00:00
day: 23
month: SEP
status: Finished
---

We started with a recap of the definition and various representations of graphs. We reviewed bi-partite graphs, n-partite graphs, planar graphs and trees. 
Cographs can be defined inductively as: a trivial graph is a cograph and a “disjoint union” or a “join” of two cographs is a cograph. Every cograph can be represented by a binary cotree (not unique) with leaf nodes as vertices and all internal nodes being labelled either as “disjoint union” or “join”. A graph is a cograph iff P3 (path of length 3) is not an induced subgraph. This characterization can be used to determine whether a graph is a cograph in linear time.
The cotree representation suggests a generalization of the class of cographs. As before, each vertex is a leaf node in the tree representation. Assign a label to each leaf node from a set of labels L. Now each internal node is a relation on L. Two leaf nodes are adjacent iff their labels are related by the relation defined by their least common ancestor in the tree representation. The special case where L is singleton gives us cographs. 
After this we looked at representing graph theoretic problems in first order and second order logic. Relation between complexity of solving a problem and complexity of stating a problem in a formal language was discussed. For example, all problems expressible in First Order logic have polynomial time algorithms (ie they are in P). Furthermore, Fagin showed in 1973 that the set of all properties expressible in existential second-order logic is precisely the complexity class NP! This suggests a new approach to P vs NP.

Graph (definition): <a href="https://en.wikipedia.org/wiki/Graph_theory#Graph">here</a> 
<br>
Cographs : <a href="https://en.wikipedia.org/wiki/Cograph">here</a>
<br>
Fagin’s theorem: <a href="https://en.wikipedia.org/wiki/Fagin%27s_theorem">here</a>



