---
title: How to Topologize
layout: post
post-image: "https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/C751A_depot.jpg/1280px-C751A_depot.jpg"
description: A light and fast introduction to the pure math subject of topology, and its computational interface.
tags:
- topology
- topological data analysis
- TDA
- computational topology
- shape
- data
---

---
## Overview



***Objectives***: After this session, we hope you will be able to:
> - Define "shape"
> - Describe topological and geometric properties of a space/shape
> - Explain how to represent data as a complex

---
## 1. Getting Started

We are glad that you are here with us for this workshop!  The first activity is
hands-on, literally.

We start by standing in a circle.  Then, hold hands with two differnt people
(both cannot be next to you).  Can we unknot ourselves?

Knot theory is fun!  If we can unknot ourselves and we have formed one connected component,
then we have formed **the unknot**, or the most basic/fundamental of all knots.
If we created two cycles (each an unknot or not), then we have formed a link.

[![unknotting](https://img.youtube.com/vi/UmF0-Tz1oWc/hqdefault.jpg)](https://www.youtube.com/watch?v=UmF0-Tz1oWc)

Other knots that are interesting (and not equivelent to the unknot) are the
trefoil knot and the figure 8 knot.  These are the first two knots of the
"sixteen simplest knots":

![simple knots](https://knotplot.com/knot-theory/inlines/row1KnTb.gif)
![simple knots](https://knotplot.com/knot-theory/inlines/row2KnTb.gif)

Variants to try (in smaller groups):

1. If you start facing each other and hold your neighbor's hands, can you
   turn your circle "inside-out" and have your backs facing inward?
2. Can you form the trefoil knot?
3. What about the figure 8 knot?

---
## 2. What is Shape (in Data Science)?


<details>
<summary style="color:red">See the Dictionary Definition and Brittany's Definition</summary>
<br>
<pre style="background-color:lightcoral">
From Meriam Webster:
<ul>
  <li>The visible makeup characteristic of a particular item or kind of items</li>
  <li>Spatial form or contour</li>
  <li>A standard or universally recognized spatial form</li>
</ul>
<br>
From Brittany: shape is a way of putting meaning or interpretability to a set. 
<br>
</pre>
</details>


---
## 3. Koenigsberg


![Koenigsberg](https://comptag.github.io/t4ds/assets/images/bridges.jpg)


<details>
<summary>See the Answer</summary>
<br>
<pre style="background-color:lightcoral">
<br>
<img src="https://comptag.github.io/t4ds/assets/images/bridges-map-and-graph.png" alt="bridges with graphs">
<br>
</pre>
</details>


---
## 4. Are Two Shapes the Same or Different?

First, we need to understand what a *topological space* is.  

> A topological space $(X,T)$ is a set $X$
> (e.g., the real line) with a set of sets $T \subseteq 2^X$ (elements of $T$
> are called *open sets*) that follows the
> following two rules:
> 
> 1. The intersection of a finite number of open sets is open.
> 2. Any (potentially infinite) union of open sets is open.


---
### Representing Shapes

---
[1]: <https://upload.wikimedia.org/wikipedia/commons/5/5d/Konigsberg_bridges.png> (bridges of Koenigsberg)
[2]: https://en.wikipedia.org/wiki/Human_knot 
[3]: https://mathlesstraveled.com/2010/11/19/the-mathematics-of-human-knots/
[4]: <https://scholarlycommons.pacific.edu/euler-works/53/> 
