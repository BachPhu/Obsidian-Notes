---
tag: calculus/unit
unit: 1
---

# Symbols
 
 Link to calculus symbol :
  https://mathvault.ca/hub/higher-math/math-symbols/calculus-analysis-symbols/
  https://en.wikipedia.org/wiki/List_of_mathematical_symbols_by_subject



___

$$\lim_{x → a} f(x)$$

This is read as: “the limit of $f(x)$ as x approaches a.”
a ∈ ℝ = a is a real number 
 

> [!warning]
> WARNING 1: → means “approaches.” Avoid using this symbol outside the context of limits.
> 
> WARNING 2: Sometimes, the limit value $\color{#84C1FF}\lim_{x → a} f(x)$ does not equal the function value $f(a)$
> 
> WARNING 3: Do not omit the limit operator $\color{#84C1FF}\lim_{x → 1}$  until this substitution phase.

___

# [[Limit Existence Theorem]]

> [!Important]
> $\lim_{x → a} f(x)$ = L exists if:
> $$\lim_{x → a^-} f(x) = \lim_{x → a^+} f(x) = L$$
> where L is any real number (not -∞ or ∞) 

# Limits of Exponential Function

$$ y = \color{#FF6666}a \color{#84C1FF}b \color{white}^ {x ± h} ± k$$ 
- if $\color{#ff6666} a$ is negative ⇒ reflect over x-axis
- if $\color{#84C1FF}b > 1$⇒ growth function
- if $0 < \color{#84C1FF}b < 1$ ⇒ decay func
- k is the HA

## [[Two Special Trig Function]]

> [!NOTE]
> 
> $$\lim_{\theta → 0} \frac{1 - cos \color{#84C1FF}c \color{white} \theta}{\theta} = 0$$
> $$\lim_{\theta → 0} \frac{sin \color{#84C1FF}c \color{white} \theta}{\theta} $$


# [[Limit-Based Continuity]]

> [!Important]
> 
> Three piece of information in order for a function; $f(x)$ to be continuous at $x = a$: 
> 1. $f(x)$ is defined
> 2. $\lim_{x → a} f(x)$ exist
> 3.  $f(x) = \lim_{x → a} f(x)$
> 


## Types of Func that are <font color= #B8C8B8 >Continuous</font> at very Point on their Domain


1. Polynomial Func    $$f(x) = ax^{h}+ ax^{h-1} + ax + a$$
2. Rational Func  $$f(x) = \frac{p(x)}{q(x)}; q(x)≠ 0$$
3. Radical Func $$f(x) = \sqrt[n]{x} $$
4. Trig Func $$sin, tan, cos, sec, csc, cot$$
5. Exponential Func $$f(x) = b^{x}, b > 0, b ≠ 1$$
6. Log Func $$f(x) = \log_{b}x$$

# [[Intermediate Value Theorem]]

if $f(x)$ is *continuous* on $\color{#84C1FF}[a, b]$ AND $\color{#FF6666}f(a) < y < f(b)$ then there <mark class="hltr-light-purple">exists at least ONE</mark> value $x = c$ on $[a ,b]$ such that $f(c) = y$


# Infinite Limits and Limits at Infinity

| Limits at Infinity                                                         | Infinite Limits                        |
| -------------------------------------------------------------------------- | -------------------------------------- |
| are limit that = $∞$ or $-∞$, and where $x → a$ and $a$ is a *real* number | are limit in which $x → ∞$ or $x → -∞$ |
| Vertical Asymptotes| Horizontal Asymptotes / Slant Asymp / **End Behavior**   |

# Derivative and Antiderivative of sin(x) and cos(x)

## Derivative of sinx and cosx

$$\frac{d}{dx} \text{ sin(x) = cos(x)}$$

$$\frac{d}{dx} \text{ cos(x) = - sin(x)}$$
## Antiderivative of sinx and cosx
$$\int \text{cos(x) dx = sin(x) + c}$$
$$\int \text{sin(x) dx = -cos(x) + c}$$