---
layout: post
title: Math Note -- domain
tags: [math, study-note]
comments: true
---

# Why I wrote this note

I was doing my homework and I found a question about domain. I thought it was a good question, so I decided to write a note about it.

# What is domain?

The domain of a function is the set of all values for which the function is defined. Easily, domain is the range of x-values. That is a definition of domain. But what does it mean? Let's see an example.

## Example 1

Let's say we have a function $f(x) = x^2$. What is the domain of this function? The domain of this function is the set of all real numbers. Why? Because the function is defined for all real numbers. Let's see another example.

## Example 2

Let's say we have a function $f(x) = \frac{1}{x}$. What is the domain of this function? The domain of this function is the set of all real numbers except 0. Why? Because the function is not defined for $x = 0$.

## Problem 1 (from my homework)

Find $f+g$, $f - g$, $f·g$, and $\frac{f}{g}$. Determine the domain for each function.
$f(x) = \frac{3x+1}{x^2-25}\\
g(x) = \frac{2x-4}{x^2-25}$

## Solution 1

$f+g = \frac{3x+1}{x^2-25} + \frac{2x-4}{x^2-25} = \frac{3x+1+2x-4}{x^2-25} = \frac{5x-3}{x^2-25}$

The domain of $f+g$ is the set of all real numbers except $x = \pm \sqrt{25} = \pm 5$.

$f-g = \frac{3x+1}{x^2-25} - \frac{2x-4}{x^2-25} = \frac{(3x+1)-(2x-4)}{x^2-25} = \frac{x+5}{x^2-25}$ = $\frac{x+5}{(x+5)(x-5)}$ = $\frac{1}{x-5}$ $(x ≠ 5)$

The domain of $f-g$ is the set of all real numbers except $x = 5$ and $x = -5$. Wait, excluding positive five is understandable, but why excluding negative five? In the expression for the function f(x) = $\frac{(3x+1)}{(x^2-25)} - \frac{(2x-4)}{(x^2-25)}$, the denominator of both fractions is $x^2 - 25$. This means that the function is undefined when $x^2 - 25 = 0$, or when $x^2 = 25$.

This equation has two solutions: $x = 5$ and $x = -5$. These are the values that make the function undefined, so they must be excluded from the domain.

If we substitute x = 5 into the original expression for f(x), we get:

$f(5) = \frac{35+1}{5^2-25} - \frac{25-4}{5^2-25}
= \frac{36}{25-25} - \frac{21}{25-25}
= \frac{36}{0} - \frac{21}{0} = \frac{15}{0} = undefined$

If we substitute x = -5 into the original expression for f(x), we get:

$f(-5) = \frac{3×(-5)+1}{(-5)^2-25} - \frac{2*(-5)-4}{(-5)^2-25}
= \frac{-15+1}{25-25} - \frac{-10-4}{25-25}
= -\frac{14}{0} - (-\frac{14}{0})$ = $\frac{28}{0} = undefined$

The function is undefined when x = 5 and x = -5, because the denominator of either fraction is equal to zero (division by zero is undefined). Therefore, x = 5 and x = -5 must be excluded from the domain of the function.

The simplified form of the function, f(x) = 1/(x-5), is only valid for values of x that are not equal to 5. The original expression for the function, f(x) = (3x+1)/(x^2-25) - (2x-4)/(x^2-25), is valid for all real numbers except x = 5 and x = -5.

$f·g = \frac{3x+1}{x^2-25} \cdot \frac{2x-4}{x^2-25} = \frac{3x+1}{x^2-25} \cdot \frac{2x-4}{x^2-25} = \frac{6x^2-12x-4x+100}{x^4-50x^2+625}$

The domain of $f·g$ is the set of all real numbers
except $x = \pm \sqrt{25} = \pm 5$.

$\frac{f}{g} = \frac{\frac{3x+1}{x^2-25}}{\frac{2x-4}{x^2-25}} = \frac{3x+1}{x^2-25} \cdot \frac{x^2-25}{2x-4} = \frac{3x^2+3x-4}{2x^2-10x+100}$

The domain of $\frac{f}{g}$ is the set of all real numbers except $x = \pm \sqrt{25} = \pm 5$.
