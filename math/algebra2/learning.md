# Algebra 2 — Learning Log

## Converting between logarithmic and exponential form

**Question:** Which answer choice does *not* contain a pair of equivalent equations?

- A. ln(x) = 2  and  e² = x
- B. log₅(x) = 2  and  5² = x
- C. log₂(x) = 5  and  5² = x
- D. log(x) = 2  and  10² = x

**Answer: C**

### The key rule

A logarithm answers the question *"what exponent?"* The definition is:

> **logₐ(x) = b   ⟺   aᵇ = x**

In words: the **base of the log** becomes the **base of the power**, and the value the
log **equals** becomes the **exponent**. Read it as: "base raised to the answer gives x."

### Checking each choice

| Choice | Log form | Correct exponential form | Given exponential form | Equivalent? |
|--------|----------|--------------------------|------------------------|-------------|
| A | ln(x) = 2   (base *e*) | e² = x | e² = x  | ✅ yes |
| B | log₅(x) = 2 | 5² = x | 5² = x  | ✅ yes |
| C | log₂(x) = 5 | **2⁵ = x** | 5² = x  | ❌ **no** |
| D | log(x) = 2  (base 10) | 10² = x | 10² = x | ✅ yes |

### Why C is the odd one out

For **log₂(x) = 5**, the base is **2** and the answer is **5**, so:

- Correct conversion:  **2⁵ = x**, giving x = 32
- The choice instead writes **5² = x**, which gives x = 25

C **swapped the base and the exponent**. The base (2) and the result of the log (5)
were flipped, producing a *different* value (25 instead of 32). So the two equations
in C are **not** equivalent — that makes C the correct answer to the question.

### Takeaway

When converting logₐ(x) = b to exponential form, keep the base on the bottom:
the base of the log stays the base of the power (**aᵇ = x**). Don't let a base and
exponent that happen to be "nice numbers" trick you into swapping them.
