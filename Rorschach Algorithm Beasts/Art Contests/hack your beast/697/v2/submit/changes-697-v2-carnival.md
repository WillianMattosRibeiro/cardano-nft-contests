# Beast 697 - v2 (Carnival) - Modification 

---

## *Change 1*

> ### from
> 
> ```
> [7]: [5, 50, 20, 20, 60, 10],
> 20: [14, 35, 14, 20, 14, 35],
> 21: [170, -130, 200, 20, 50, -30],
> 22: [20, 20, 20, 20, 20, 20],
> 29: [10, 5, 5, -3, 40, 15]
> ```
> 
> ### to
> 
> ```
> [7]: [100, 50, 0, 20, 0, 1000],
> 20: [14, 35, 1000, 20, 14, 35],
> 21: [0, 0, 1000, 20, 950, 0],
> 22: [-20, -20, -20, -20, -20, 0],
> 29: [10, 7000, 5, -300, 40, 15]
> ```

---

## *Change 2*

> ### from
> 
> ```
> for (let t = o; t < o + i; t++) U[t] = new g(2 * l() - 1, 2 * l() - 1, 2 * l() - 1, n, e, h, c, s, T(a))
> 
> ```
> 
> ### to
> 
> ```
> for (let t = o; t < o + i; t++) U[t] = new g(25 * l() - 1, 15 * l() - 1, 500 * l() - 1, n, e, h, c, s, T(a))
> 

---

## *Change 3*

>### from
>
>```
>x0 = this.x, y0 = this.y, this.rotate(), x.beginPath(), x.lineWidth = 1, x.strokeStyle = this.t;
>
>```
>
>### to
>
>```
>x0 = this.x, y0 = this.y, this.rotate(), x.beginPath(), x.lineWidth = 1.7, x.strokeStyle = this.t;
>```
---