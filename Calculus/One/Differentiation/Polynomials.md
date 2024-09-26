### Polynomials

1) Let $f(x) = x^2 + 1$. Calculate:

- $f'(1)$

$$f'(1) = \lim_{x \to 1}\frac{f(x) - f(1)}{x - 1} = \lim_{x \to 1}\frac{x^2 + 1 - (1^2 + 1)}{x - 1} = \lim_{x \to 1}\frac{x^2-1}{x-1} = \lim_{x \to 1}\frac{(x+1)(x-1)}{x-1}$$

$$=\lim_{x \to 1}x+1 = 2$$

- $f'(0)$

$$f'(0) = \lim_{x \to 0}\frac{f(x) - f(0)}{x-1} = \lim_{x \to 0}\frac{x^2+1-(0^2 + 1)}{x - 0} = \lim_{x \to 0}\frac{x^2}{x} = \lim_{x \to 0}x = 0$$

- $f'(x)$

$$f'(x) = \lim_{x \to x_0}\frac{x^2+1-(x_0^2 + 1)}{x - x_0} = \lim_{x \to x_0}\frac{x^2 + 1-x_0^2 - 1}{x - x_0} = \lim_{x \to x_0}\frac{x^2 - x_0^2}{x - x_0}$$

$$=\lim_{x \to x_0}\frac{(x+x_0)(x-x_0)}{x-x_0} = \lim_{x \to x_0}x+x_0 = 2x_0 \Rightarrow f'(x) = 2x$$

---

2) Let $f(x) = 2x$. Calculate $f'(x)$

$$f'(x) = \lim_{x\to x_0}\frac{2x - 2x_0}{x-x_0} = \lim_{x \to x_0}\frac{2(x - x_0)}{x - x_0} = 2$$

---

3) Let $f(x) = 3x + 2$. Calculate:

- $f'(2)$

$$f'(2) = \lim_{x \to 2}\frac{3x + 2 - (6 + 2)}{x - 2} = \lim_{x \to 2}\frac{3x - 6}{x - 2} = \lim_{x \to 2}\frac{3(x - 2)}{x-2} = 3$$

- $f'(0)$

$$f'(0) = \lim_{x \to 0}\frac{3x + 2 - (3\cdot0 + 2)}{x-0} = \lim_{x \to 0}\frac{3x}{x} = 3$$

- $f'(x)$

$$f'(x) = \lim_{x \to x_0}\frac{3x + 2-(3x_0 + 2)}{x-x_0} = \lim_{x \to x_0}\frac{3x-3x_0}{x-x_0} = \lim_{x \to x_0}\frac{3(x - x_0)}{x-x_0} = 3$$

---

4. Calculate $f'(x)$

- $f(x) = x^2 + x \Rightarrow f'(x) = 2x$

- $f(x) = 5x - 3 \Rightarrow f(x) = 5$

- $f'(x) = \sqrt{x} \Rightarrow f'(x)=\frac{1}{2\sqrt{x}}$

- $f(x) = 2x^3 - x^2 \Rightarrow f'(x) = 6x^2-2x$

- $f(x) = \frac{1}{x} \Rightarrow f'(x) = -\frac{1}{x^2}$

- $f(x) = \frac{1}{x^2} \Rightarrow f'(x) = -\frac{2}{x^3}$

- $f(x) = \sqrt[3]{x} \Rightarrow f'(x) = \frac{1}{3\sqrt[3]{x^2}}$

---

5. Find the tangent line to the graph of:

- $f(x) = x^2$

Since $f'(x) = 2x$ then to find the slope of the tangent line at a certain point $p$ will be $f(p) = 2p$. We have that slope is equal $\frac{y - y_0}{x - x_0}$, then:

$$2p = \frac{y - f(p)}{x - p} \Rightarrow 2p(x-p) + f(p) = y$$

$$y = 2px - 2p^2 + f(p)$$

So if we take $p = 2$ 

$$y = 2\cdot 2 \cdot x - 2(2)^2 + f(2) = 4x-8+4 = 4x-4$$

We have $y = 4x-4$ as the equation fo the tangent line of $f(x)$ at $x = 2$

---

- $f(x) = \sqrt{x}$

Since $f'(x) = \frac{1}{2\sqrt{x}}$:

$$\frac{1}{2\sqrt{p}} = \frac{y - f(p)}{x - p} \Rightarrow \frac{x-p}{2\sqrt{p}}+f(p) = y$$

$$y = \frac{x-p}{2\sqrt{p}} + f(p)$$

So if we take p = 9

$$y = \frac{x-9}{2\sqrt{9}} + f(9) = \frac{x-9}{6} +3 = \frac{x+9}{6}$$

We have $y = \frac{x+9}{6}$ as the equation of the tangent line at $p = 9$.

---

- $f(x) = \frac{1}{x}$

Since $f'(x) = -\frac{1}{x^2}$, the line equation at a certain point $p$ is:

$$- \frac{1}{p^2} = \frac{y - f(p)}{x-p} \Rightarrow -\frac{x-p}{p^2} + f(p) = y$$

$$y = -\frac{x-p}{p^2} + f(p)$$

Taking $p = 2$

$$y = -\frac{x - 2}{2^2} + f(2) = \frac{2-x}{4} + \frac{1}{2} = \frac{4-x}{4} = 1-\frac{x}{4}$$

we have $y = 1-\frac{1}{4}$ being the equation of the tangent line at $p=2$

---

- $f(x) = x^2 - x$

Since $f'(x) = 2x - 1$, the line equation at a certain point $p$ is:

$$2p-1 = \frac{y - f(p)}{x - p} \Rightarrow (2p-1)(x-p) + f(p) = y$$

$$y = 2px - 2p^2 -x +p +f(p)$$

Taking $p = 1$

$$y = 2\cdot 1 \cdot x - 2(1)^2 - x + 1 + f(1) = 2x-2-x+1+0 = x-1$$

we have $y=x-1$ being the equation of the tangent line at $p = 1$

---

6. Calculate $g'(x)$, $g$ being:

- $g(x) = x^6 \Rightarrow g'(x) = 6x^5$

- $g(x) = x^{100} \Rightarrow g'(x) = 100x^{99}$

- $g(x) = \frac{1}{x} \Rightarrow g'(x) = - \frac{1}{x^2}$

- $g(x) = x^2 \Rightarrow g'(x) = 2x$

- $g(x) = \frac{1}{x^3} \Rightarrow g'(x) = -\frac{3}{x^4}$

- $g(x) = \frac{1}{x^7} \Rightarrow g'(x) = -\frac{7}{x^8}$

- $g(x) = x^{-3} \Rightarrow g'(x) = \frac{-3}{x^4}$

---

7. Calculate $g'(x)$, $g$ being:

- $g(x) = \sqrt[4]{x} \Rightarrow g'(x) = \frac{1}{4\sqrt[4]{3}}$

- $g(x) = \sqrt[8]{x} \Rightarrow g'(x) = \frac{1}{8\sqrt{8}{x^7}}$

- $g(x) = \sqrt[6]{x} \Rightarrow g'(x) = \frac{1}{6\sqrt[6]{x^5}}$

- $g(x) = \sqrt[9]{x} \Rightarrow g'(x) = \frac{1}{9\sqrt[9]{x^8}}$