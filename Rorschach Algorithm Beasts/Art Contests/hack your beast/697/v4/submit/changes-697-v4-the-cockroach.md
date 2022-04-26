# Beast 697 - v1 (The Cockroach) - Modification 

---

## *Change 1*
>
>#### from
>``` js
> a = u * Math.cos(r),
>```
>
>
>#### to
>    
>``` js
> a = u * Math.atan(r),
>```

---

## *Change 2*
> ### from
> 
> ``` js
> [7]: [5, 50, 20, 20, 60, 10],
> 20: [14, 35, 14, 20, 14, 35],
> 21: [170, -130, 200, 20, 50, -30],
> 22: [20, 20, 20, 20, 20, 20],
> 29: [10, 5, 5, -3, 40, 15]
> ```
> 
> ### to
> 
> ``` js
> [7]: [70, 50, 20, 20, 60, 10],
> 20: [50, 35, 14, 20, 14, 35],
> 21: [300, 30, 200, 20, 100, -30],
> 22: [20, 20, 20, 20, 20, 20],
> 29: [10, 5, 5, -3, 40, 40]
> ```
---


## *Change 3*
> ### from
> 
> ``` js
> for (let t = o; t < o + i; t++) U[t] = new g(2 * l() - 1, 2 * l() - 1, 2 * l() - 1, n, e, h, c, s, T(a))
> ```
> 
> ### to
> 
> ``` js
> for (let t = o; t < o + i; t++) U[t] = new g(2 * l() - 1, 4.5 * l() - 1, 2 * l() - 1, n, e, h, c, s, T(a))
> ```

---

## *Change 4*
> ### from
> 
> ``` js
> nx = this.x - .05 * Math.sin(this.a * this.y - this.s + this.y * Math.sin(this.x)), ny = this.y - .05 * Math.sin(this.b * this.x - this.r + this.x * Math.sin(this.x)), this.x = nx, this.y = ny, (.95 < .5 + q * this.x || .5 + q * this.x < .05 || .5 + y * (this.y - k) < .05 || .9 < .5 + y * (this.y - k)) && (F = !0)
> ```
> 
> ### to
> 
> ``` js
> nx = this.x - .05 * Math.cos(this.a * this.y - this.s + this.y * Math.exp(this.x)), ny = this.y - .05 * Math.atan(this.b * this.x - this.r + this.x * Math.log(this.x)), this.x = nx, this.y = ny, (.95 < .5 + q * this.x || .5 + q * this.x < .05 || .5 + y * (this.y - k) < .05 || .9 < .5 + y * (this.y - k)) && (F = !0)
> ```

---

## *Change 5*
> ### from
> 
> ``` js
> x0 = this.x, y0 = this.y, this.rotate(), x.beginPath(), x.lineWidth = 1, x.strokeStyle = this.t;
> ```
> 
> ### to
> 
> ``` js
> x0 = this.x, y0 = this.y, this.rotate(), x.beginPath(), x.lineWidth = 20, x.strokeStyle = this.t;
> ```

---
