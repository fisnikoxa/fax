## Algebra Workbook

### Problem 1 — Factor and/or Solve: 4 − 12x + 9x^2

- Reorder: \(9x^2 - 12x + 4\).
- Check discriminant (for perfect square):
  \[\Delta = b^2 - 4ac = (-12)^2 - 4\cdot 9\cdot 4 = 144 - 144 = 0\]
  A zero discriminant means a repeated root; the trinomial is a perfect square.
- Use perfect-square trinomial identity:
  \[a^2 - 2ab + b^2 = (a - b)^2\]
  Here, \(a = 3x\) and \(b = 2\). Thus
  \[9x^2 - 12x + 4 = (3x - 2)^2\]

— Factorization:

\[(3x - 2)^2\]

— If solving the equation \(4 - 12x + 9x^2 = 0\):

\[(3x - 2)^2 = 0 \;\Rightarrow\; 3x - 2 = 0 \;\Rightarrow\; x = \dfrac{2}{3}\]

Alternative (quadratic formula) for completeness:
\[x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} = \frac{12 \pm \sqrt{144 - 144}}{18} = \frac{12}{18} = \frac{2}{3}\]

> Answer: \((3x - 2)^2\). If set equal to zero, the solution is \(x = \tfrac{2}{3}\) (double root).



### Problem 2 — Equation of the Line through \((-9, 7)\) and \((-6, -3)\)

- Given points: \(P_1(-9,7)\), \(P_2(-6,-3)\).
- Slope:
  \[\Delta y = y_2 - y_1 = -3 - 7 = -10,\quad \Delta x = x_2 - x_1 = -6 - (-9) = -6 + 9 = 3\]
  \[m = \frac{\Delta y}{\Delta x} = \frac{-10}{3}\]
- Point–slope form:
  \[y - y_1 = m(x - x_1)\]
  Using \(P_1(-9,7)\):
  \[y - 7 = -\frac{10}{3}(x - (-9)) = -\frac{10}{3}(x + 9)\]
- Expand and solve for \(y\) (slope–intercept form):
  \[y - 7 = -\frac{10}{3}x - \frac{10}{3}\cdot 9 = -\frac{10}{3}x - 30\]
  \[y = -\frac{10}{3}x - 30 + 7 = -\frac{10}{3}x - 23\]
- Optional standard form:
  \[3y = -10x - 69 \;\Longleftrightarrow\; 10x + 3y + 69 = 0\]

- Verification:
  - For \(x=-9\): \(y = -\tfrac{10}{3}(-9) - 23 = 30 - 23 = 7\).
  - For \(x=-6\): \(y = -\tfrac{10}{3}(-6) - 23 = 20 - 23 = -3\).

> Answer: \(y = -\tfrac{10}{3}x - 23\)

### Problem 3 — Factor completely: \(2x^2 + 7x + 3\)

- Coefficients: \(a=2\), \(b=7\), \(c=3\); thus \(ac = 6\).
- Find integers \(m,n\) with \(m+n=b\) and \(mn=ac\): choose \(m=6\), \(n=1\) since \(6+1=7\) and \(6\cdot 1=6\).
- Split the middle term:
  \[2x^2 + 7x + 3 = 2x^2 + 6x + x + 3\]
- Factor by grouping:
  \[2x(x+3) + 1(x+3) = (2x+1)(x+3)\]

— Optional check (roots): Quadratic formula gives
\[x = \frac{-7 \pm \sqrt{49 - 24}}{2\cdot 2} = \frac{-7 \pm 5}{4} \in \{-3, -\tfrac{1}{2}\}\]
Zeros match factors \((x+3)\) and \((2x+1)\).

> Answer: \((2x+1)(x+3)\)

### Problem 4 — Total copies sold (scientific notation)

- Given: \(5.9\times 10^5\) and \(1.3\times 10^6\).
- Align exponents (write both with \(10^6\)):
  \[5.9\times 10^5 = 0.59\times 10^6\]
- Add mantissas with the common power:
  \[(0.59 + 1.3)\times 10^6 = 1.89\times 10^6\]
- Mantissa check: \(1 \le 1.89 < 10\) — valid scientific notation.

> Answer: \(1.89\times 10^6\) copies

### Problem 5 — Solve the system

\[\begin{aligned}
&7y + 10x - 8 = 0\\
&2y - 5x - 18 = 0
\end{aligned}\]

- Write in standard form:
  \[10x + 7y = 8,\quad -5x + 2y = 18\]
- Eliminate \(x\): multiply the second equation by 2 and add:
  \[-10x + 4y = 36\]
  Add with \(10x + 7y = 8\):
  \[11y = 44 \;\Rightarrow\; y = 4\]
- Back-substitute into \(2y - 5x - 18 = 0\):
  \[2(4) - 5x - 18 = 0 \;\Rightarrow\; 8 - 5x - 18 = 0\]
  \[-5x - 10 = 0 \;\Rightarrow\; -5x = 10 \;\Rightarrow\; x = -2\]

> Answer: \(x = -2,\; y = 4\)

