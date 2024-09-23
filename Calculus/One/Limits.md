<h3>Trigonometric limits</h3>

$a) \lim_{x \to 0} \frac{tan(x)}{x}$

$$\lim_{x\to 0} \frac{tan(x)}{x} = \lim_{x\to 0} \frac{\frac{sin(x)}{cos(x)}}{x} = \lim_{x\to 0} \frac{sin(x)}{x\cdot cos(x)} = \lim_{x\to 0} \frac{1}{cos(x)} = 1 $$

---

$b) \lim_{x\to 0} \frac{x}{sin(x)} $

$$ \lim_{x\to 0} \frac{x}{sin(x)} = \lim_{x\to 0} \left(\frac{sin(x)}{x}\right)^{-1} = 1^{-1} =1 $$

---

$c) \lim_{x\to 0} \frac{sin(3x)}{x}$

$$\lim_{x\to 0} \frac{sin(3x)}{x} = \lim_{x\to 0} \frac{3}{3}\cdot \frac{sin(3x)}{x} = \lim_{x\to 0} 3\cdot \frac{sin(3x)}{3x} = \lim_{x\to 0} 3 = 3$$

---

$d) \lim_{x\to \pi} \frac{sin(x)}{x - \pi}$

$$\lim_{x\to \pi} \frac{sin(x)}{x - \pi} $$

Let $x = h + \pi$, therefore $\lim_{x \to \pi} = \lim_{h \to 0}$

$$ \lim_{h \to 0} \frac{sin(h+ \pi)}{(h+\pi) - \pi} = \lim_{h\to 0} \frac{sin(h+\pi)}{h}$$

Since $sin(h+\pi) = -sin(h)$

$$\lim_{h \to 0} \frac{-sin(h)}{h} = -1$$

---

$e) \lim_{x \to 0}\frac{x^2}{sin(x)}$

$$\lim_{x \to 0}\frac{x^2}{sin(x)} = \lim_{x\to 0} \left(\frac{sin(x)}{xx}\right)^{-1} = \lim_{x\to 0} \left(\frac{1}{x}\right)^{-1} = \lim_{x\to 0} x=0$$

---

$f) \lim_{x\to 0} \frac{3x^2}{tan(x)sin(x)}$

$$ \lim_{x\to 0} \frac{3x^2\cdot cos(x)}{\frac{sin(x)}{cos(x)}sin(x)cos(x)} = \lim_{x\to 0} \frac{3x^2\cdot cos(x)}{sin^2(x)}$$

$$ \lim_{x\to 0} \left(\frac{sin^2(x)}{3x^2\cdot cos(x)}\right)^{-1} = \lim_{x\to 0} \left(\frac{1}{3\cdot cos(x)}\right)^{-1} = \left(\frac{1}{3}\right)^{-1} = 3$$

---

$g) \lim_{x\to 0} \frac{tan(3x)}{sin(4x)}$

$$ \lim_{x\to 0} \frac{tan(3x)}{sin(4x)} = \lim_{x \to 0} \frac{sin(3x)}{cos(3x)sin(4x)} = \lim_{x \to 0} \frac{sin(3x)\cdot 3x}{cos(3x)sin(4x)3x}$$

$$\lim_{x \to 0} \frac{3x}{cos(3x)sin(4x)} = \lim_{x \to 0}\frac{3x\cdot 4x}{cos(4x)sin(4x)4x} = \lim_{x \to 0}\frac{3x}{cos(3x)4x}$$

$$\lim_{x \to 0}\frac{3}{cos(3x)4} = \frac{3}{4}$$

---
$h)\lim_{x \to 0}\frac{1-cos(x)}{x}$

$$\lim_{x \to 0}\frac{1-cos(x)}{x} = \lim_{x \to 0}\frac{(1-cos(x))(1+cos(x))}{x(1+cos(x))} = \lim_{x \to 0}\frac{1-cos^2(x)}{x(1+cos(x))}$$

$$ \lim_{x \to 0}\frac{sin^2(x)}{x(1+cos(x))} = \lim_{x \to 0}\frac{sin(x)}{1+cos(x)} = \frac{0}{2} = 0 $$

---

$i) \lim_{x \to \frac{\pi}{2}}\frac{1-sin(x)}{2x - \pi}$

Let $ x = \frac{\pi}{2} + h$, therefore, $\lim_{x \to \frac{\pi}{2}} \Rightarrow \lim_{h\to 0}$


$$ \lim_{x \to \frac{\pi}{2}}\frac{1-sin(x)}{2x - \pi} = \lim_{h \to 0} \frac{1-sin(h+\frac{\pi}{2})}{\pi + 2h-\pi} = \lim_{h \to 0}\frac{1-cos(h)}{2h} $$

$$ \lim_{h \to 0}\frac{sin^2(h)}{2h(1 + cos(h))} = \lim_{h \to 0}\frac{sin(h)}{2(1 + cos(h))} = 0 $$

---

$j) \lim_{x \to 0} x\cdot sin\left(\frac{1}{x}\right)$

Since $-1 \leq sin\left(\frac{1}{x}\right) \leq 1 $ we have that $ 0 \leq \mid sin\left(\frac{1}{x}\right) \mid \leq 1$. Multiplying the inequation by $\mid x \mid$.

$$ 0 \leq \mid x \mid \cdot \mid sin\left(\frac{1}{x}\right) \mid \leq \mid x \mid $$

$$ -\mid x \mid \leq x \cdot sin\left(\frac{1}{x}\right) \leq \mid x \mid $$

By the squeeze theorem we can conclude that $\lim_{x\to 0}x\cdot sin\left(\frac{1}{x}\right) = 0$.

---

$l) \lim_{x \to p} \frac{tan(x-p)}{x^2 - p^2}, p \neq0$

$$ \lim_{x \to p}\frac{sin(x-p)}{cos(x-p)(x+p)(x-p)} = \lim_{x \to p}\frac{1}{cos(x-p)(x+p)} $$

$$= \frac{1}{cos(p-p)(p+p)} = \frac{1}{2p}$$

---

$m) \lim_{x \to p}\frac{sin(x^2-p^2)}{x - p}$

$$\lim_{x \to p}\frac{sin(x^2-p^2)}{x - p} = \lim_{x \to p}\frac{sin((x-p)(x+p))}{x-p} $$

$$ = \lim_{x \to p} \frac{sin((x-p)(x+p))(x+p)}{(x-p)(x+p)} = \lim_{x \to p} x+p = 2p$$

---

$n) \lim_{x \to 0}\frac{sin(x^2+\frac{1}{x})-sin(\frac{1}{x})}{x}$

---

$o) \lim_{x\to 0}\frac{x+sin(x)}{x^2-sin(x)}$

---

$p) \lim_{x\to 0}\frac{x-tan(x)}{x+tan(x)}$

---

$q) \lim_{x\to 1}\frac{sin(\pi x)}{x-1}$