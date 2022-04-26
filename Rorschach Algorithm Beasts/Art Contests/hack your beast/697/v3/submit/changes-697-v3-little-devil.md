# Beast 697 - v3 (Little Devil) - Modification 

---

## *Change 1*
>
>    #### from
>    ``` js
>    var t = 1e4 * Math.sin(w++);
>    ```
>    
>    #### to
>    
>    ``` js
>    var t = 1e4 * Math.log(w++);
>    ```

---

## *Change 2*
> ### from
> 
> ``` js
> N = D, j(1), x.fillStyle = "#fff", x.fillRect(0, 0, A, A), j(.2), t = 0;
> ```
> 
> ### to
> 
> ``` js
> N = D, j(1), x.fillStyle = "#000", x.fillRect(0, 0, A, A), j(.2), t = 0;
> ```
---

## *Change 3*
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
> [7]: [999, 50, 20, 0, 0, 0],
> 20: [999, 35, 14, 0, 14, 5],
> 21: [999, 30, 0, 20, 10, -3],
> 22: [999, 20, 0, 20, 0, 0],
> 29: [999, 5, 5, -3, 0, 0]
> ```

---

## *Change 4*
> ### from
> 
> ``` js
> for (let t = o; t < o + i; t++) U[t] = new g(2 * l() - 1, 2 * l() - 1, 2 * l() - 1, n, e, h, c, s, T(a))
> ```
> 
> ### to
> 
> ``` js
> for (let t = o; t < o + i; t++) U[t] = new g(1.6 * l() - 1, 8.99 * l() - 1, 2 * l() - 1, n, e, h, c, s, T(a))
> ```
> 
---

## *Change 5*
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
> ---

> ## *Change 6*
> ### from
> 
> ``` js
> x0 = this.x, y0 = this.y, this.rotate(), x.beginPath(), x.lineWidth = 1, x.strokeStyle = this.t;
> ```
> 
> ### to
> 
> ``` js
> x0 = this.x, y0 = this.y, this.rotate(), x.beginPath(), x.lineWidth = 2.5, x.strokeStyle = this.t;
> ```

---
















