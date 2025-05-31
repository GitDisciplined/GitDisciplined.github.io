---
layout: page
title: "Real Analysis"
permalink: /real-analysis/
---

# Real Analysis

Welcome to the Real Analysis section. This page will serve as an ongoing discussion of various topics in Real Analysis. You can always come back to this page for updates, additions, or corrections.

## 1. Introduction to Real Analysis

Real Analysis is a branch of mathematics that deals with real numbers and real-valued sequences and functions. It is the foundation for much of modern mathematical analysis and is essential for understanding calculus in its deeper form.

Real Analysis builds on the properties of limits, sequences, continuity, and differentiability, as well as integration and series. Here, we will discuss key concepts and provide examples and exercises.

## 2. Limits

The concept of **limit** is central to Real Analysis. A limit describes the behavior of a function as its input approaches a certain value.

### Definition of a Limit

Let \( f(x) \) be a function defined on an open interval containing \( c \), except possibly at \( c \). We say that the **limit** of \( f(x) \) as \( x \to c \) is \( L \), and write:

\[
\lim_{x \to c} f(x) = L
\]

if, for every \( \epsilon > 0 \), there exists a \( \delta > 0 \) such that:

\[
0 < |x - c| < \delta \implies |f(x) - L| < \epsilon
\]

### Example of a Limit:

Consider the function \( f(x) = 3x + 2 \). Let's find the limit as \( x \to 1 \).

\[
\lim_{x \to 1} (3x + 2) = 3(1) + 2 = 5
\]

Thus, the limit is 5.

## 3. Continuity

A function \( f(x) \) is said to be **continuous** at a point \( c \) if:

\[
\lim_{x \to c} f(x) = f(c)
\]

That is, the function does not have any breaks, jumps, or holes at that point.

### Example:

Consider the function \( f(x) = \frac{1}{x} \). This function is **not continuous** at \( x = 0 \), since:

\[
\lim_{x \to 0} f(x) = \infty \quad \text{but} \quad f(0) \text{ is undefined.}
\]

## 4. Sequences and Series

### Sequences:

A **sequence** is an ordered list of numbers. We write a sequence as \( \{ a_n \} \), where \( a_n \) is the nth term of the sequence.

### Series:

A **series** is the sum of the terms of a sequence. The most common series is the **geometric series**, which has the form:

\[
S = a + ar + ar^2 + ar^3 + \cdots
\]

For example, the infinite geometric series:

\[
S = 1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \cdots
\]

has the sum:

\[
S = \frac{1}{1 - \frac{1}{2}} = 2
\]

---

## Exercises

1. **Find the limit** of the function \( f(x) = 2x^2 + 3x - 1 \) as \( x \to 4 \).
2. **Prove** that \( \lim_{x \to 0} \frac{\sin x}{x} = 1 \) using the formal definition of a limit.
3. **Find the sum** of the geometric series \( 5 + 5 \times \frac{1}{3} + 5 \times \left( \frac{1}{3} \right)^2 + \cdots \).

---

## Conclusion

This is just the beginning of Real Analysis. As we progress, we will explore more advanced topics, including **Differentiability**, **Integration**, and **Series Convergence**. Stay tuned for updates to this page!

