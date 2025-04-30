---
menuPre: " "
title: 'Ratios and Angles'
description: 'Formulae related to trigonometric ratios and angles'
weight: 100
---

## Basic Formulae

---

$\begin{aligned}
\sin^2\theta + \cos^2\theta & = 1 \\
\tan^2\theta - \sec^2\theta & = 1 \\
\csc^2\theta - \cot^2\theta & = 1
\end{aligned}$

$\begin{aligned}
\sin x & = \cos \left(90^{\circ }-x\right) & = {\dfrac {1}{\csc x}}  \\
\cos x & = \sin \left(90^{\circ }-x\right) & = {\dfrac {1}{\sec x}} \\
\tan x & = \cot \left(90^{\circ }-x\right) & = {\dfrac {\sin x}{\cos x}} = {\dfrac {1}{\cot x}}
\end{aligned}$  

---

A system of rectangular coordinate axes divides a plane into four quadrants. An angle $\theta$ lies in one and
only one of these quadrants.  
The change and sign of the trigonometric ratios in the various quadrants are shown in Fig-1 below.

<figure>

![Fig-1](math-trigo-unit-circle.svg?width=700px&classes=left)
</figure>

<!--

$\begin{tikzpicture}

  % Draw the axes with double-headed arrows
  \draw[semithick, <->] (-3.5, 0) -- (3.5, 0) node[right, align=center] {$0^\circ$ \\ (T-ratio same)};
  \draw[semithick, <->] (0, -3.5) -- (0, 3.5) node[above, align=center] {(T-ratio change) \\ $90^\circ$};
  
  % Add nodes for the quadrants
  \node at (-3.5,0) [left, align=center] {$180^\circ$ \\ (T-ratio same)};
  \node at (0,-3.5) [below, align=center] {$270^\circ$ \\ (T-ratio change)};

  % Label each quadrant
  \node at (1.33, 2) {I quadrant};
  \node[align=center] at (1.33, 1) {All T-ratios \\ are +ve};

  \node at (-1.33, 2) {II quadrant};
  \node[align=center] at (-1.33, 1) {${\left.{\begin{aligned}\sin\theta \\ \csc\theta \end{aligned}}\right\}\text{+ve}}$};

  \node at (-1.33, -0.7) {III quadrant};
  \node[align=center] at (-1.33, -1.7) {${\left.{\begin{aligned}\tan\theta \\ \cot\theta \end{aligned}}\right\}\text{+ve}}$};

  \node at (1.33, -0.7) {IV quadrant};
  \node[align=center] at (1.33, -1.7) {${\left.{\begin{aligned}\cos\theta \\ \sec\theta \end{aligned}}\right\}\text{+ve}}$};

  % Draw circular arcs
  \draw[semithick, ->] (3.3, 0) arc[start angle=0, end angle=15, radius=3.5];
  \draw[semithick, ->] (3.3, 0) arc[start angle=0, end angle=-15, radius=3.5];
  \draw[semithick, ->] (0, 3.3) arc[start angle=90, end angle=105, radius=3.5];
  \draw[semithick, ->] (0, 3.3) arc[start angle=90, end angle=75, radius=3.5];
  \draw[semithick, ->] (-3.3, 0) arc[start angle=180, end angle=195, radius=3.5];
  \draw[semithick, ->] (-3.3, 0) arc[start angle=180, end angle=165, radius=3.5];
  \draw[semithick, ->] (0, -3.3) arc[start angle=270, end angle=285, radius=3.5];
  \draw[semithick, ->] (0, -3.3) arc[start angle=270, end angle=255, radius=3.5];
  
\end{tikzpicture}$

-->

---

## Sum and Difference

### Two Angle

$\begin{aligned}
\sin(A\pm B) & = \sin A\cos B\pm \cos A\sin B \\[3mu]
\cos(A\pm B) & = \cos A\cos B\mp \sin A\sin B
\end{aligned}$  

$\begin{aligned}
\tan\left(A\pm B\right) & = \dfrac{\tan A\pm\tan B}{1\mp\tan A\tan B} \\[10mu]
\cot\left(A\pm B\right) & = \dfrac{\cot A\cot B\mp 1}{\cot B\pm \cot A}
\end{aligned}$  

$\begin{aligned}
\sin\left(A+B\right)\sin\left(A-B\right) && = \sin^2A-\sin^2B && = \cos^2B-\cos^2A \\
\cos\left(A+B\right)\cos\left(A-B\right) && = \cos^2A-\sin^2B && = \cos^2B-\sin^2A
\end{aligned}$  

### Three Angle

$\begin{aligned}
\sin\left(A+B+C\right) & =  \sin A\cos B\cos C+\cos A\sin B\cos C+\cos A\cos B\sin C-\sin A\sin B\sin C  \\[3mu] & =  \cos A\cos B\cos C\left(\tan A+\tan B+\tan C-\tan A\tan B\tan C\right)
\end{aligned}$  

$\begin{aligned}
\cos\left(A+B+C\right) & =  \cos A\cos B\cos C-\sin A\sin B\cos C-\sin A\cos B\sin C-\cos A\sin B\sin C  \\[3mu] & =  \cos A\cos B\cos C(1-\tan A\tan B-\tan B\tan C-\tan C\tan A)
\end{aligned}$  

$\begin{aligned}
\tan\left(A+B+C\right) & =  \dfrac{\tan A+\tan B+\tan C-\tan A\tan B\tan C}{1-\tan A\tan B-\tan B\tan C-\tan C\tan A} \\[12mu]
\cot\left(A+B+C\right) & =  \dfrac{\cot A+\cot B+\cot C-\cot A\cot B\cot C}{1-\cot A\cot B-\cot B\cot C-\cot C\cot A}
\end{aligned}$  

### General

---

$\begin{aligned}
S_{0} & = 1 \\ 
S_{1} & = \sum\limits_{i} x_{i} && = \sum\limits_{i} \tan \theta_{i} \\ 
S_{2} & = \sum\limits_{i < j} x_{i} x_{j} && = \sum\limits_{i < j} \tan \theta_{i} \tan \theta_{j} \\ 
S_{3} & = \sum\limits_{i < j < k} x_{i} x_{j} x_{k} && = \sum\limits_{i < j < k} \tan \theta_{i} \tan \theta_{j} \tan \theta_{k} \\ 
& \quad \vdots && \quad \vdots
\end{aligned}$


Then,

$\begin{aligned}
\tan\left(\theta_1+\theta_2+\cdots+\theta_n\right) & = \dfrac{S_1-S_3+S_5-S_7+\cdots}{1-S_2+S_4-S_6+\cdots} \\[16mu] 
\sec\left(\theta_1+\theta_2+\cdots+\theta_n\right) & = {\dfrac {\sec \theta_1 \sec \theta_2 \cdots \sec \theta_n}{S_{0}-S_{2}+S_{4}-\cdots }} \\[16mu] 
\csc\left(\theta_1+\theta_2+\cdots+\theta_n\right) & = {\dfrac {\sec \theta_1 \sec \theta_2 \cdots \sec \theta_n}{S_{1}-S_{3}+S_{5}-\cdots }} 
\end{aligned}$

---

$\cos2^r\theta\cdot\cos2^{r+1}\theta\cdot\cos2^{r+2}\theta\cdots\cos2^n\theta= \dfrac{\sin2^{n+1}\theta}{2^{n-r+1}\sin2^r\theta}$ 

$\begin{aligned}
\sin(\alpha)+\sin(\alpha+\beta)+\sin(\alpha+2\beta)+\cdots+\sin\left(\alpha+n\beta\right) & = \dfrac{\sin \left((n+1)\frac{\beta}{2}\right)}{\sin\left(\frac{\beta}{2}\right)}\sin\left(\alpha+n\frac{\beta}{2}\right) \\[16mu]
\cos(\alpha)+\cos(\alpha+\beta)+\cos(\alpha+2\beta)+\cdots+\cos\left(\alpha+n\beta\right) & = \dfrac{\sin\left((n+1)\frac{\beta}{2}\right)}{\sin\left(\frac{\beta}{2}\right)}\cos\left(\alpha+n\frac{\beta}{2}\right)
\end{aligned}$  

$1+2\cos \theta+2\cos(2\theta)+2\cos(3\theta)+\cdots +2\cos(n\theta)={\dfrac {\sin \left(\left(n+{\frac {1}{2}}\right)\theta\right)}{\sin \left({\frac {\theta}{2}}\right)}}$

> Generally not true! only for common values of '$\theta$'. USE WITH CAUTION  
> 
> $\dfrac{\sin{\theta_1} \pm \sin{\theta_2} + \sin{\theta_3} + \cdots + \sin{\theta_n}}{\cos{\theta_1} \pm \cos{\theta_2} + \cos{\theta_3} + \cdots + \cos{\theta_n}} = \tan{\dfrac{\theta_1 \pm \theta_2 + \theta_3 + \cdots + \theta_n}{n} }$  

## Product to Sum

$\begin{aligned}
2\sin A\cos B & = \sin\left(A+B\right)+\sin\left(A-B\right) \\[6mu] 
2\cos A\sin B & = \sin\left(A+B\right)-\sin\left(A-B\right) \\[6mu] 
2\cos A\cos B & = \cos\left(A+B\right)+\cos\left(A-B\right) \\[6mu] 
2\sin A\sin B & = \cos\left(A-B\right)-\cos\left(A+B\right)
\end{aligned}$  

## Sum to Product

$\begin{aligned}
\sin C+\sin D & = 2\sin\frac{C+D}2\cos\frac{C-D}2 \\[8mu]
\sin C-\sin D & = 2\cos\frac{C+D}2\sin\frac{C-D}2 \\[8mu]
\cos C+\cos D & = 2\cos\frac{C+D}2\mathrm{cos}\frac{C-D}2 \\[8mu]  
\cos C-\cos D & = -2\sin\frac{C+D}2\sin\frac{C-D}2
\end{aligned}$  

## Multiple Angle

### Two/Three Angle

$\begin{aligned}
\sin2\theta& =  2\sin \theta\cos \theta  \\[3mu] & =  \dfrac{2\tan \theta}{1+\tan^2\theta} 
\end{aligned}$  

$\begin{aligned}
\cos2\theta& =  \cos^2\theta-\sin^2\theta  \\[3mu] & = 2\cos^2\theta-1 \\[3mu] & =  1-2\sin^2\theta  \\[3mu] & =  \dfrac{1-\tan^2\theta}{1+\tan^2\theta} 
\end{aligned}$  

$\tan2\theta= \dfrac{2\tan\theta}{1-\tan^2\theta}$  

$\begin{aligned}
\sin3\theta & = 3\sin \theta-4\sin^3\theta \\[3mu]
& = 4\sin\left(60^\circ-\theta\right)\sin (\theta)\sin\left(60^\circ+\theta\right)
\end{aligned}$  

$\begin{aligned}
\cos3\theta & = 4\cos^3\theta-3\cos \theta \\[3mu]
& = 4\cos\left(60^\circ-\theta\right)\cos (\theta)\cos\left(60^\circ+\theta\right)
\end{aligned}$  

$\begin{aligned}
\tan3\theta & = \dfrac{3\tan \theta-\tan^3\theta}{1-3\tan^2\theta}  \\[3mu]
& = \tan\left(60^{\circ}-\theta\right)\tan (\theta)\tan\left(60^{\circ}+\theta\right)
\end{aligned}$  

### Multi(>3) Angle

$\begin{aligned}
\sin4\theta & = 4\sin \theta\cos^3 \theta - 4\cos \theta\sin^3 \theta \\ 
\cos4\theta & = 8\cos^4\theta-8\cos^2\theta+1 \\ 
\tan4\theta & = \dfrac{4\tan\theta-4\tan^3\theta}{1-6\tan^2\theta+\tan^4\theta} \\ 
\sin5\theta & = 16\sin^5\theta-20\sin^3\theta+5\sin \theta \\ 
\cos5\theta & = 16\cos^5\theta-20\cos^3\theta+5\cos \theta
\end{aligned}$  

### Half Angle

$\begin{aligned}
\sin {\dfrac {\theta }{2}} & = \operatorname {sgn} \left(\sin {\dfrac {\theta }{2}}\right){\sqrt {\dfrac {1-\cos \theta }{2}}} \\
\cos {\dfrac {\theta }{2}} & = \operatorname {sgn} \left(\cos {\dfrac {\theta }{2}}\right){\sqrt {\dfrac {1+\cos \theta }{2}}}
\end{aligned}$  

$\begin{aligned}
\tan {\dfrac {\theta }{2}}
& ={\frac {1-\cos \theta }{\sin \theta }}\\[8mu]
& ={\frac {\sin \theta }{1+\cos \theta }}\\[8mu]
& =\csc \theta -\cot \theta \\[1mu]
& ={\frac {\tan \theta }{1+\sec {\theta }}}\\[1mu]
& =\operatorname {sgn}(\sin \theta ){\sqrt {\frac {1-\cos \theta }{1+\cos \theta }}}
\end{aligned}$  

#### Special Cases

$\tan {\dfrac {\eta \pm \theta }{2}}={\dfrac {\sin \eta \pm \sin \theta }{\cos \eta +\cos \theta }}$  

$\tan \left({\dfrac {\theta }{2}}+{\dfrac {\pi }{4}}\right)=\sec \theta +\tan \theta$  
${\sqrt {\dfrac {1-\sin \theta }{1+\sin \theta }}}=\left|{\dfrac {1-\tan {\dfrac {\theta }{2}}}{1+\tan {\dfrac {\theta }{2}}}}\right|$

## Power Reduction

| Sine $(\sin^n\theta)$                                                     | Cosine  $(\cos^n\theta)$                                                  | Combined $(\sin^n\theta\cos^m\theta)$                                                      |
| :------------------------------------------------------------------------ | :------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------- |
| $\sin ^{2}\theta ={\dfrac {1-\cos2\theta}{2}}$                            | $\cos ^{2}\theta ={\dfrac {1+\cos2\theta}{2}}$                            | $\sin ^{2}\theta \cos ^{2}\theta ={\dfrac {1-\cos4\theta}{8}}$                             |
| $\sin ^{3}\theta ={\dfrac {3\sin \theta -\sin3\theta}{4}}$                | $\cos ^{3}\theta ={\dfrac {3\cos \theta +\cos3\theta}{4}}$                | $\sin ^{3}\theta \cos ^{3}\theta ={\dfrac {3\sin2\theta-\sin6\theta}{32}}$                 |
| $\sin ^{4}\theta ={\dfrac {3-4\cos2\theta+\cos4\theta}{8}}$               | $\cos ^{4}\theta ={\dfrac {3+4\cos2\theta+\cos4\theta}{8}}$               | $\sin ^{4}\theta \cos ^{4}\theta ={\dfrac {3-4\cos4\theta+\cos8\theta}{128}}$              |
| $\sin ^{5}\theta ={\dfrac {10\sin \theta -5\sin3\theta+\sin5\theta}{16}}$ | $\cos ^{5}\theta ={\dfrac {10\cos \theta +5\cos3\theta+\cos5\theta}{16}}$ | $\sin ^{5}\theta \cos ^{5}\theta ={\dfrac {10\sin2\theta-5\sin6\theta+\sin10\theta}{512}}$ |


## Special Cases 

If $A+B+C=180^{\circ}=\pi$ , then

$\begin{aligned}
\sin2A+\sin2B+\sin2C & = 4\sin A\sin B\sin C \\
\sin2A+\sin2B-\sin2C & = 4\cos A\cos B\sin C \\
\cos2A+\cos2B+\cos2C & = -1-4\cos A\cos B\cos C \\
\cos2A+\cos2B-\cos2C & = 1-4\sin A\sin B\cos C \\[20mu]
\sin A+\sin B+\sin C & =4\cos\frac A2\cos\frac B2\cos\frac C2 \\
\sin A+\sin B-\sin C & =4\sin\frac A2\sin\frac B2\cos\frac C2 \\
\cos A+\cos B+\cos C & =1+4\sin\frac A2\sin\frac B2\sin\frac C2 \\
\cos A+\cos B-\cos C & =-1+4\cos\frac A2\cos\frac B2\sin\frac C2 \\[20mu]
\sin^2A+\sin^2B-\sin^2C & = 2\sin A\sin B\cos C \\
\cos^2A+\cos^2B-\cos^2C & = 1-2\sin A\sin B\cos C \\
\cos^2A+\cos^2B+\cos^2C & = 1-2\cos A\cos B\cos C \\
\sin^2A+\sin^2B+\sin^2C & = 2+2\cos A\cos B\cos C \\[20mu]
\tan A+\tan B+\tan C & = \tan A\tan B\tan C \\
\cot B\cot C+\cot C\cot A+\cot A\cos B  & = 1 \\
\tan\frac B2\tan\frac C2+\tan\frac C2\tan\frac A2+\tan\frac A2.\tan\frac B2 & = 1 \\
\cot\frac A2+\cot\frac B2+\cot\frac C2 & = \cot\frac A2\cot\frac B2\cot\frac C2
\end{aligned}$  

## Series Expansion

$\begin{aligned}
\sin x & = x-\dfrac{x^3}{3!}+\dfrac{x^5}{5!}-\dfrac{x^7}{7!}+\cdots  && = \sum\limits_{n=0}^\infty\dfrac{(-1)^nx^{2n+1}}{(2n+1)!} \\
\cos x & = 1-\dfrac{x^2}{2!}+\dfrac{x^4}{4!}-\dfrac{x^6}{6!}+\cdots  && = \sum\limits_{n=0}^\infty\dfrac{(-1)^nx^{2n}}{(2n)!} \\
\tan x & = x+\dfrac{x^{3}}{3}+\dfrac{2x^{5}}{15}+\dfrac{17x^{7}}{315}+\dfrac{62x^{9}}{2835}\cdots
\end{aligned}$

## Complex Exponential Function

$e^{ix}=\cos x+i\sin x=\operatorname {cis}(\theta)$  

$\begin{aligned}
\cos x & = {\dfrac {e^{ix}+e^{-ix}}{2}} \\
\sin x & = {\dfrac {e^{ix}-e^{-ix}}{2i}}
\end{aligned}$  

---

## References

- [Wikipedia: Trigonometric Functions](https://en.wikipedia.org/wiki/Trigonometric_functions)
- [Wikipedia: List of Trigonometric Identities](https://en.wikipedia.org/wiki/List_of_trigonometric_identities)