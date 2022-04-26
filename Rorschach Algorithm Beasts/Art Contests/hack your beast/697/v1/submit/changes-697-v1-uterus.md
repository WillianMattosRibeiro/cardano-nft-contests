# Beast 697 - v1 (Uterus) - Modification 

---

## *Change 1*

> ### from
> 
> ``` Change 1
> for (z(f / 4, n, i, t, M, o, c1), z(f / 4, h, e, t, a, u, c2), z(f / 4, s, c, t, r, m, c3), z(f, s - h, e - i, t, M + a, u + m, c4), z(f, n - h, c - e, t, M - r, o - m, c5), y = .031, F = !(q = .037), b = 0; b < 400 && !F;) U.forEach(t => t.rotate()), b++;
> ```
> 
> ### to
> 
> ```
> for (z(f / 4, n, i, t, M, o, c1), z(f / 4, h, e, t, a, u, c2), z(f / 4, s, c, t, r, m, c3), z(f, s - h, e - i, t, M + a, u + m, c4), z(f, n - h, c - e, t, M - r, o - m, c5), y = .031, F = !(q = .037), b = 0; b < 400 && !F;) U.forEach(t => t.rotate()), b--;
> ```

---

## *Change 2*

> ### from
> 
> ```
> for (let t = o; t < o + i; t++) U[t] = new g(2 * l() - 1, 2 * l() - 1, 2 * l() - 1, n, e, h, c, s, T(a))
> ```
> 
> ### to
> 
> ```
> for (let t = o; t < o + i; t++) U[t] = new g(7 * l() - 12, 4 * l() - 1, 1 * l() - 1, n, e, h, c, s, T(a))
> ```

---