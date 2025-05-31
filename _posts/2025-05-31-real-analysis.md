---
layout: default
title: "Limits and Continuity"
categories: [real-analysis]
---

Let \( f : D \to \mathbb{R} \), and let \( a \in \mathbb{R} \) be a limit point of the domain \( D \subseteq \mathbb{R} \).  
We say that the **limit of \( f(x) \) as \( x \to a \) is \( L \)**, and write

\[
\lim_{x \to a} f(x) = L
\]

if for every \( \varepsilon > 0 \), there exists a \( \delta > 0 \) such that

\[
0 < |x - a| < \delta \quad \Rightarrow \quad |f(x) - L| < \varepsilon
\]

This definition excludes \( x = a \), so the value of the function at \( a \) (if it exists) is irrelevant to the existence of the limit.

