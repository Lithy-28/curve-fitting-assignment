# curve-fitting-assignment


### Found Parameters
- θ = 30°
- M = 0.03
- X = 55

### Final Parametric Equations
\[
\begin{aligned}
x(t) &= t\cos(30°) - e^{0.03|t|}\sin(0.3t)\sin(30°) + 55,\\[4pt]
y(t) &= 42 + t\sin(30°) + e^{0.03|t|}\sin(0.3t)\cos(30°)
\end{aligned}
\]

### Desmos Link
[View on Desmos](https://www.desmos.com/calculator)

(You can paste the same equations there to visualize.)

### Method Summary
Performed grid search on θ, M, X to minimize the symmetric Chamfer L1 distance between
the predicted curve and the given 1500 data points.

---

**Result Summary:**  
Best fit achieved at θ ≈ 30°, M ≈ 0.03, X ≈ 55 with minimum L1 ≈ 0.032.
