---
menuPre: " "
title: Algebra
description: Algebra
weight: 100
---

{{% children containerstyle="div" style="h3" %}}

---

## Basic Algebraic Operations

Commutative Property:

$\begin{aligned}
a + b & = b + a \\
a \times b & = b \times a \\
\end{aligned}$

Associative Property:

$\begin{aligned}
(a + b) + c & = a + (b + c) \\
(a \times b) \times c & = a \times (b \times c) \\
\end{aligned}$

Distributive Property:

$\begin{aligned}
a \cdot (b + c) & = ab + ac \\
(a + b)(c + d) & = ac + ad + bc + bd \\
\end{aligned}$

### Exponents and Powers

$\begin{aligned}
a^m \times a^n & = a^{m+n} \\
\frac{a^m}{a^n} & = a^{m-n} \\
(a^m)^n & = a^{m \times n} \\
a^0 & = 1 \\
a^1 & = a \\
a^{-n} & = \frac{1}{a^n} \\
a^{\frac{m}{n}} & = \sqrt[n]{a^m} \\
\end{aligned}$

### Polynomials

##### Quadratic:

$\begin{aligned}
(a + b)^2 & = a^2 + 2ab + b^2 \\
(a - b)^2 & = a^2 - 2ab + b^2 \\
a^2 + b^2 & = (a + b)^2 - 2ab \\
& = (a - b)^2 + 2ab \\
a^2 - b^2 & = (a - b)(a + b) \\
(x + a)(x + b) & = x^2 + (a + b)x + ab \\
(a + b + c)^2 & = a^2 + b^2 + c^2 + 2(ab + ac + bc) \\
\end{aligned}$

##### Cubic:

$\begin{aligned}
(a + b)^3 & = a^3 + b^3 + 3ab(a + b) \\
& = a^3 + 3a^2b + 3ab^2 + b^3 \\
(a - b)^3 & = a^3 - b^3 - 3ab(a - b) \\
& = a^3 - 3a^2b + 3ab^2 - b^3 \\
a^3 + b^3 & = (a + b)(a^2 - ab + b^2) \\
a^3 - b^3 & = (a - b)(a^2 + ab + b^2) \\
(a + b + c)^3 & = a^3 + b^3 + c^3 − 3(a + b)(b + c)(c + a) \\
\end{aligned}$

##### Special:

$\begin{aligned}
a^2 + b^2 + c^2 - ab - bc - ca & = \frac{1}{2}\left[ (a - b)^2 + (b - c)^2 + (c - a)^2 \right] \\
a^3 + b^3 + c^3 - 3abc & = (a + b + c)(a^2 + b^2 + c^2 - ab - bc - ca) \\
& = (a + b + c)^3 − 3(a + b + c)(ab + bc + ca) \\
\end{aligned}$

##### Higher Order Polynomials:

$\begin{aligned}
(a \pm b)^4 & = a^4 \pm 4a^3b + 6a^2b^2 \mp 4ab^3 + b^4 \\
a^4 - b^4 & = (a - b)(a + b)(a^2 + b^2) \\
(a \pm b)^5 & = a^5 \pm 5a^4b + 10a^3b^2 \mp 10a^2b^3 + 5ab^4 \pm b^5 \\
a^5 - b^5 & = (a - b)(a^4 + a^3b + a^2b^2 + ab^3 + b^4) \\
\end{aligned}$

### Quadratic Equations

For a quadratic equation of the form $ ax^2 + bx + c = 0 $,  
the solution is given by the quadratic formula.

$ x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a} $

Determinant: $ \Delta \text{ (or) } D = b^2 - 4ac $

Nature of roots:
- Distince real roots: $ \Delta > 0 $
- Equal real roots: $ \Delta = 0 $
- Dinstinct complex roots: $ \Delta < 0 $

##### Completing the Square

- $ ax^2 + bx + c = \left(x + \dfrac{b}{2a}\right)^2 - \dfrac{b^2-4ac}{4a^2} $
- If $a = 1$ then,  
  $ x^2 + bx + c = \left(x + \dfrac{b}{2}\right)^2 - \dfrac{b^2}{4} + c $

### Logarithms

$ a^x = b \implies x = \log_a b $

$\begin{aligned}
\ln a & = \log_e a \\
\log_a 1 & = 0 \\
\log_a a & = 1 \\
\log_a x^n & = n \log_a x \\
\log_{a^n} x & = \dfrac{1}{n} \log_a x \\
\log_a \sqrt[n]{x} & = \dfrac{1}{n} \log_a x \\
\log_a(x \cdot y) & = \log_a x + \log_a y \\
\log_a\left(\dfrac{x}{y}\right) & = \log_a x - \log_a y \\
a^{\log_a x} & = x \\
\log_a b & = \dfrac{1}{\log_b a} \\
\log_a b & = \dfrac{\log_c b}{\log_c a} \\
\end{aligned}$
