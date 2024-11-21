---
date: '2024-11-17T20:36:11+05:30'
menuPre: " "
title: 'Indefinite Integration'
description: 'Indefinite Integration'
weight: 400
---

## Basic Formulas

### 1. Power Rule  

> $\quad (n\not ={-1})$  

$\displaystyle\int (f(x))^n f'(x) \, dx = \dfrac{(f(x))^{n+1}}{n+1} + C$  

$\displaystyle\int x^n \, dx = \dfrac{x^{n+1}}{n+1} + C$

$\displaystyle\int |x|^n \, dx = \dfrac{x |x|^{n}}{n+1} + C$

### 2. Logarithmic Integration  

$\displaystyle\int \dfrac{f'(x)}{f(x)} \, dx = \ln |f(x)| + C$  

$\displaystyle\int \dfrac{1}{x} \, dx = \ln |x| + C$

### 3. Trigonometric Functions  

$\begin{aligned}
\displaystyle\int \sin x \, dx &&& = -\cos x + C \\  
\displaystyle\int \cos x \, dx &&& = \sin x + C \\  
\displaystyle\int \tan x \, dx &&& = -\log |\cos x| + C && = \log |\sec x| + C \\  
\displaystyle\int \cot x \, dx &&& = \log |\sin x| + C && = -\log |\csc x| + C \\  
\displaystyle\int \sec x \, dx &&& = \log |\sec x + \tan x| + C && = \log \left| \tan \left(\frac{\pi}{4} + \frac{x}{2}\right) \right| + C \\  
\displaystyle\int \csc x \, dx &&& = \log |\csc x - \cot x| + C && = \log \left| \tan \frac{x}{2} \right| + C
\end{aligned}$

### 4. Exponential Function  

$\displaystyle\int a^x \, dx = \dfrac{a^x}{\log_e a} + C$  

$\displaystyle\int e^x \, dx = e^x + C$

### 5. Special  

$\begin{aligned}
\displaystyle\int \dfrac{dx}{a^2 + x^2} & = \dfrac{1}{a} \tan^{-1} \dfrac{x}{a} + C \\[8mu]
\displaystyle\int \dfrac{dx}{a^2 - x^2} & = \dfrac{1}{2a} \log \left| \dfrac{a+x}{a-x} \right| + C \\[25mu]
\displaystyle\int \dfrac{dx}{\sqrt{a^2 - x^2}} & = \sin^{-1} \dfrac{x}{a} + C \\[25mu]
\displaystyle\int \dfrac{dx}{\sqrt{x^2 + a^2}} & = \log \left|x + \sqrt{x^2 + a^2}\right| + C \\[8mu]
\displaystyle\int \dfrac{dx}{\sqrt{x^2 - a^2}} & = \log \left| x + \sqrt{x^2 - a^2} \right| + C \\[25mu]
\displaystyle\int \dfrac{dx}{x\sqrt{x^2 - a^2}} & = \dfrac{1}{a} \sec^{-1} \dfrac{x}{a} + C \\[25mu]
\displaystyle\int \sqrt{a^2 - x^2} \, dx & = \dfrac{x}{2} \sqrt{a^2 - x^2} + \dfrac{a^2}{2} \sin^{-1} \dfrac{x}{a} + C \\[8mu]
\displaystyle\int \sqrt{x^2 + a^2} \, dx & = \dfrac{x}{2} \sqrt{x^2 + a^2} + \dfrac{a^2}{2} \log \left(x + \sqrt{x^2 + a^2}\right) + C \\[8mu]
\displaystyle\int \sqrt{x^2 - a^2} \, dx & = \dfrac{x}{2} \sqrt{x^2 - a^2} - \dfrac{a^2}{2} \log \left(x + \sqrt{x^2 - a^2}\right) + C \\[8mu]
\end{aligned}$  
