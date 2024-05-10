---
layout: ../layouts/Post.astro
title: Hello, World
author: Lázaro Albuquerque
description: Testando o KaTeX
---

# Hi there!

This Markdown file creates a page at `your-domain.com/page-1/`

It probably isn't styled much, but Markdown does support:

-   **bold** and _italics._
-   lists
-   [links](https://astro.build)
-   and more!

Eis uma fórmula matemática: $$\sqrt{a^2 + b^2}$$

Lift($$L$$) can be determined by Lift Coefficient ($$C_L$$) like the following
equation.

$$
L = \frac{1}{2} \rho v^2 S C_L
$$

```math
\varphi: \mathbb{R} \to \mathbb{R^2}
```

**Statement**: For each positive integer $n$, let $$X_n = \{0, 2\}$$ be equipped with the discrete topology and consider $$X = \Pi_{n=1}^{\infty}X_n$$ with the product topology.  
Let $$f : X \to [0, 1] \subset \mathbb{R}$$ be the function defined by

$
f(x) = \sum_{n=1}^\infty \frac{x(n)}{3^n}
$.

Then $f$ is injective and continuous. Moreover, f is a homeomorphism between $X$ and $K = f(X)$, which is the classical Cantor's ternary set.

**Proof**: Take $x, y \in X$ and suppose $f(x)=f(y)$. Then $$0 = f(x)-f(y) = \sum_{n=1}^\infty \frac{x(n) - y(n)}{3^n}$$
Since the series above is absolutely convergent, we can rearrange its terms according to the sets $I = \{ n \ge 1 \ | \ x(n) - y(n) = -2 \}$, $J = \{ n \ge 1 \ | \ x(n) - y(n) = 2 \}$ and $K = \{ n \ge 1 \ | \ x(n) - y(n) = 0 \}$, obtaining

$$
\begin{equation}
\begin{split}
\sum_{n=1}^\infty \frac{x(n) - y(n)}{3^n} &= \sum_{n \in I} \frac{x(n) - y(n)}{3^n} + \sum_{n \in J} \frac{x(n) - y(n)}{3^n} + \sum_{n \in K} \frac{x(n) - y(n)}{3^n} \\
&= \sum_{n \in I} \frac{x(n) - y(n)}{3^n} + \sum_{n \in J} \frac{x(n) - y(n)}{3^n}
\end{split}
\end{equation}
$$

In other words,

$$\sum_{n \in I} \frac{1}{3^n} = \sum_{n \in J} \frac{1}{3^n}$$
