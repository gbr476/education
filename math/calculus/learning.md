# Calculus — Learning Log

## Index

- [Notation: d/dx vs dy/dx](#notation-ddx-vs-dydx)
- [Derivative of cos(x)](#derivative-of-cosx)
- [Integral of sin(x)](#integral-of-sinx)

---

## Notation: d/dx vs dy/dx

**`d/dx` is a verb; `dy/dx` is a noun.**

- **`d/dx`** is an *operator* — the instruction "take the derivative with respect
  to x of whatever comes next." On its own it's incomplete; it needs something to
  act on.
- **`dy/dx`** is the *result* — the actual derivative *of y* with respect to x
  (a slope / rate of change). It's what you get.

They connect as:

$$\frac{dy}{dx} = \frac{d}{dx}(y)$$

i.e. `dy/dx` is just `d/dx` **applied to y**, with the `y` moved into the top slot.

### Worked example

If $y = x^3$:

$$\underbrace{\frac{dy}{dx}}_{\text{answer (noun)}} = \underbrace{\frac{d}{dx}}_{\text{operation (verb)}}\big(x^3\big) = 3x^2$$

- Use **`dy/dx`** when the function is *named* `y`.
- Use **`d/dx(...)`** to say "differentiate this expression" without naming it,
  e.g. $\frac{d}{dx}(\sin x) = \cos x$.

### Analogy

Like the square-root symbol: **`√`** alone is the operation (≈ `d/dx`), while
**`√9`** is an actual value, 3 (≈ `dy/dx`). `d/dx` is the empty operation;
`dy/dx` is that operation carried out on `y`.

### Related notation

| Notation | Read as | Type |
|---|---|---|
| $\frac{d}{dx}$ | "derivative w.r.t. x of…" | operator (verb) |
| $\frac{dy}{dx}$ | "derivative of y w.r.t. x" | result (noun) |
| $\frac{d}{dx}\big[f(x)\big]$ | "differentiate f(x)" | operator acting on a bracket |
| $y'$ or $f'(x)$ | "y prime" | same result as dy/dx (Lagrange notation) |
| $\frac{d^2y}{dx^2}$ | "second derivative of y" | apply d/dx *twice* |

This is all **Leibniz notation** — written as a fraction because `dy/dx` really does
behave like a ratio of tiny changes (Δy/Δx as they shrink to 0), which becomes handy
for the chain rule and u-substitution.

[↑ Back to index](#index)

## Derivative of cos(x)

$$\frac{d}{dx}\cos(x) = -\sin(x)$$

**Watch the negative sign** — it's the most commonly forgotten part.

### Compare with sin(x)

$$\frac{d}{dx}\sin(x) = +\cos(x)$$

So sin and cos differentiate into each other, but **only cos picks up a minus sign**.
The full cycle of repeated differentiation:

$$\sin(x) \to \cos(x) \to -\sin(x) \to -\cos(x) \to \sin(x) \to \cdots$$

(It repeats every 4 derivatives.)

### Intuition (why the minus sign)

- At **x = 0**, cos(x) is at its peak (value 1) and momentarily flat → slope = 0,
  and −sin(0) = 0. ✅
- Just **past x = 0**, cos(x) is *decreasing* → slope is negative,
  and −sin(x) is negative there. ✅

The graph of cos is falling wherever sin is positive, which is exactly what
"derivative = −sin" says.

### Takeaway

- d/dx cos(x) = **−sin(x)**  (minus)
- d/dx sin(x) = **+cos(x)**  (plus)

[↑ Back to index](#index)

## Integral of sin(x)

$$\int \sin(x)\,dx = -\cos(x) + C$$

**Don't forget** the negative sign *and* the **+ C**.

### Check by differentiating back

$$\frac{d}{dx}\big(-\cos(x)\big) = -\big(-\sin(x)\big) = \sin(x) \checkmark$$

### The sin/cos derivative–integral table

|            | sin                              | cos                              |
|------------|----------------------------------|----------------------------------|
| **derivative** | d/dx sin(x) = **+cos(x)**     | d/dx cos(x) = **−sin(x)**        |
| **integral**   | ∫ sin(x) dx = **−cos(x)** + C | ∫ cos(x) dx = **+sin(x)** + C    |

**Pattern:** the minus sign appears whenever cos is the *result*.
Differentiating cos and integrating sin both land on a negative.

[↑ Back to index](#index)
