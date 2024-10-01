## Chain Rule

Let $y = f(u)$ and $u = g(x)$ being both differentiable and for all $x \in dom(g)$ we have that $g(x) \in dom(f)$. We can conclude that $f(g(x))$ is differentiable and $\frac{dy}{dx} = \frac{dy}{du}\frac{du}{dx}$

### Proof

If $\Delta u = g(x + \Delta x) - g(x) \neq 0$, $x$ and $x + \Delta x$ $\in dom(g)$ then:

$$\frac{dy}{dx} = \lim_{\Delta x \to 0}\frac{f(g(x + \Delta x)) - f(g(x))}{\Delta x}$$

$$=\lim_{\Delta x \to 0}\frac{f(g(x + \Delta x)) - f(g(x))}{\Delta x}\cdot \frac{g(x + \Delta x) - g(x)}{g(x + \Delta x) - g(x)}$$

$$= \lim_{\Delta x \to 0}\frac{f(g(x + \Delta x)) - f(g(x))}{g(x + \Delta x) - g(x)}\cdot \frac{\Delta u}{\Delta x}$$

Into $f(g(x + \Delta x))$ we can subtract and sum $g(x)$ having:

$$\frac{dy}{dx} = \lim_{\Delta x \to 0}\frac{f(g(x + \Delta x) - g(x) + g(x)) - f(g(x))}{\Delta x}\cdot \frac{\Delta u}{\Delta x}$$

Since $f(g(x + \Delta x) - g(x) + g(x)) = f(\Delta u + g(x))$ we have:

$$\frac{dy}{dx} = \lim_{\Delta x \to 0}\frac{f(\Delta u + g(x)) - f(g(x))}{g(x + \Delta x) - g(x)}\cdot \frac{\Delta u}{\Delta x}$$

We can substitute $g(x)$ by $u$ since $u = g(x)$

$$\frac{dy}{dx} = \lim_{\Delta x \to 0}\frac{f(\Delta u + u) - f(u)}{g(x + \Delta x) - u}\cdot \frac{\Delta u}{\Delta x}$$

If $y = f(u)$ then $\Delta y =f(\Delta u + u) - f(u)$, therefore:

$$\frac{dy}{dx} = \lim_{\Delta x \to 0}\frac{\Delta y}{g(x + \Delta x) - g(x)}\cdot \frac{\Delta u}{\Delta x} = \lim_{\Delta x \to 0}\frac{\Delta y}{\Delta u}\cdot \frac{\Delta u}{\Delta x}$$

Since $\Delta u = g(x + \Delta x) - g(x)$, if $\Delta x \to 0$, then $\Delta u \to 0$. Separating the limits:

$$\frac{dy}{dx} = \lim_{\Delta u \to 0}\frac{\Delta y}{\Delta u} \cdot \lim_{\Delta x \to 0}\frac{\Delta u}{\Delta x} = \frac{dy}{du}\cdot \frac{du}{dx}$$

Therefore

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$$

---

### Exercises

- $y = e^{3x}$

$u = 3x \Rightarrow y = e^u$

$$\frac{dy}{dx} = \frac{dy}{du}\cdot \frac{du}{dx} = \frac{d}{du}e^u\cdot \frac{d}{dx}3x = e^u 3 = e^{3x}\cdot 3$$

---

- $y = sin(t^2)$

$u = t^2 \Rightarrow y = sin(u)$

$$\frac{dy}{dt} = \frac{dy}{du}\cdot \frac{du}{dx} = \frac{d}{du}sin(u) \cdot \frac{d}{dx}t^2 = cos(u)2t = cos(t^2)2t$$

---

- $y = (3x^2 + 1)^3$

$u = 3x^2 + 1 \Rightarrow y = u^3$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = \frac{d}{du}u^3 \cdot \frac{d}{dx}(3x^2 + 1) =3u^26x = 18xu^2$$

$$\frac{dy}{dx} = 18x(3x^2 + 1)^2$$

---

- $y = cos(3x)$

$u = 3x \Rightarrow y = cos(u)$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}= \frac{d}{du}cos(u) \cdot \frac{d}{dx}3x = -sin(u)3 = -3sin(3x)$$

--- 

- $y = ln(x^2 + 3)$

$u = x^2 + 3 \Rightarrow y = ln(u)$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = \frac{d}{du}ln(u) \cdot \frac{d}{dx}(x^2 + 3) = \frac{1}{u}\cdot 2x$$

$$\frac{dy}{dx} = \frac{2x}{u} = \frac{2x}{x^2 + 3}$$

---

- Let $f: \mathbb{R} \to \mathbb{R}$ a differentiable function and be $g(x) = f(cos(x))$. Calculate $g'\left(\frac{\pi}{3}\right)$ assuming $f'\left(\frac{1}{2}\right) = 4$ 

$ u = cos(x) \Rightarrow g(x) = f(u)$

$$\frac{dg}{dx}(x) = \frac{dg}{du}(u) \cdot \frac{du}{dx} = \frac{d}{du}f(u)\cdot \frac{d}{dx}cos(x) = \frac{d}{du}f(u)\cdot -sin(x)$$

$$x = \frac{\pi}{3} \Rightarrow \frac{dg}{dx}\left(\frac{\pi}{3}\right) = \frac{d}{dx}f\left(cos\ \frac{\pi}{3}\right) \cdot -sin\ \frac{\pi}{3} = \frac{d}{dx}f\left(\frac{1}{2}\right)\cdot - \frac{\sqrt{3}}{2}$$

$$\frac{dg}{dx}(x) =-\frac{4\sqrt{3}}{2} = -2\sqrt{3}$$

---

- $y = sin(4x)$

$u = 4x \Rightarrow y = sin(u)$

$$\frac{dy}{dx} = \frac{dy}{du}\cdot \frac{du}{dx} = \frac{d}{du}sin(u) \cdot \frac{d}{dx}4x = cos(u)4 = 4cos(4x)$$

---

- $y = cos(5x)$

$u = 5x \Rightarrow y = cos(u)$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = \frac{d}{du}cos(u) \cdot \frac{d}{dx}5x = -sin(u)5 = -5sin(5x)$$

---

- $f(x) = e^{3x}$

$u = 3x \Rightarrow y = e^u$

$$\frac{dy}{dx} = \frac{dy}{du}\cdot \frac{du}{dx} = \frac{d}{du}e^u \cdot \frac{d}{dx}3x = e^u 3 = 3e^{3x}$$

---

- $f(x) = cos(8x)$

$u = 8x \Rightarrow f(u) = cos(u)$

$$\frac{df}{dx}(x) = \frac{df}{du}(u)\cdot \frac{du}{dx} = \frac{d}{du}cos(u) \cdot \frac{d}{dx}8x = -sin(u)\cdot 8$$

$$\frac{df}{dx}(x) = -8sin(8x)$$

---

- $y = sin(t^3)$

$u = t^3 \Rightarrow y = sin(u)$

$$\frac{dy}{dt} = \frac{dy}{du} \cdot \frac{du}{dt} = \frac{d}{du}sin(u) \cdot \frac{d}{dt}t^3 = cos(u) 3t^2 = 3t^2cos(t^3)$$

---

- $g(t) = ln(2t + 1)$

$u = 2t + 1 \Rightarrow g(u) = ln(u)$

$$\frac{dg}{dt}(t) = \frac{dg}{du}(u) \cdot \frac{du}{dt} = \frac{d}{du}ln(u) \cdot \frac{d}{dt}(2t + 1) = \frac{1}{u}\cdot 2 = \frac{2}{2t + 1}$$

---

- $y = e^{sin(t)}$

$u = sin(t) \Rightarrow y = e^u$

$$\frac{dy}{dt} = \frac{dy}{du} \cdot \frac{du}{dt} = \frac{d}{du}e^u \cdot \frac{d}{dt}sin(t) = e^u cos(t) = e^{sin(t)}cos(t)$$

---

- $f(x) = cos(e^x)$

$u = e^x \Rightarrow f(u) = cos(u)$

$$\frac{df}{dx}(x) = \frac{df}{du}(u) \cdot \frac{du}{dx} = \frac{d}{du}cos(u) \cdot \frac{d}{dx}e^x = -sin(u)e^x$$

$$\frac{df}{dx}(x) = -e^xsin(e^x)$$

---

- $y = [sin(x) + cos(x)]^3$

$u = sin(x) + cos(x) \Rightarrow y = u^3$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = \frac{d}{du}u^3 \cdot \frac{d}{dx}(sin\ x + cos\ x) = 3u^2 \cdot \frac{d}{dx}(sin\ x + cos\ x)$$

$$\frac{dy}{dx} = 3u^2\left(\frac{d}{dx} sin\ x + \frac{d}{dx}cos\ x\right) = 3u^2\left(cos\ x - sin \ x\right)$$

$$\frac{dy}{dx} = 3(sin\ x + cos\ x)^2 (cos\ x - sin\ x)$$

---

- $y = \sqrt{3x + 1}$

$u = 3x + 1 \Rightarrow y = \sqrt{u}$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = \frac{d}{du}\sqrt{u} \cdot \frac{d}{dx}3x = \frac{1}{2\sqrt{u}} \cdot 3 = \frac{3}{2\sqrt{3x +1}}$$

---

- $f(x) = \sqrt[3]{\frac{x - 1}{x + 1}}$

$u = \frac{x-1}{x + 1} \Rightarrow f(u) = \sqrt[3]{u}$

$$\frac{df}{dx}(x) = \frac{df}{du}(u) \cdot \frac{du}{dx} = \frac{d}{du}\sqrt[3]{u} \cdot \frac{d}{dx}\left(\frac{x-1}{x+1}\right) = \frac{1}{3\sqrt[3]{u^2}}\cdot \frac{d}{dx}\left(\frac{x+1}{x-1}\right)$$

$$\frac{df}{dx}(x) = \frac{1}{3\sqrt[3]{u^2}} \cdot \frac{(x-1)\frac{d}{dx}(x+1) - (x+1)\frac{d}{dx}(x-1)}{(x-1)^2}$$

$$\frac{df}{dx}(x) = \frac{1}{3\sqrt[3]{u^2}}\cdot \frac{x - 1-x-1}{(x-1)^2} = \frac{1}{3\sqrt[3]{u^2}} \cdot \frac{-2}{(x- 1)^2}$$

$$\frac{df}{dx}(x) = \frac{1}{3\sqrt[3]{\left(\frac{x-1}{x+1}\right)^2}} \cdot \frac{-2}{(x - 1)^2}$$

---

- $y = e^{-5x}$

$u = -5x \Rightarrow y = e^u$

$$\frac{dy}{dx} = \frac{dy}{du}\cdot \frac{du}{dx} = \frac{d}{du}e^u \cdot \frac{d}{dx}-5x = e^u\cdot -5 = -5e^{-5x}$$

---

- $x = ln(t^2 + 3t + 9)$

$u = t^2 + 3t + 9 \Rightarrow x = ln(u)$

$$\frac{dx}{dt} = \frac{dx}{du} \cdot \frac{du}{dt} = \frac{d}{du}ln(u) \cdot \frac{d}{dt}(t^2 + 3t + 9) = \frac{1}{u} \cdot (2t + 3)$$

$$\frac{dx}{dt} = \frac{2t + 3}{t^2 + 3t + 9}$$

---

- $f(x) = e^{tan(x)}$

$u = tan(x) \Rightarrow f(u) = e^u$

$$\frac{df}{dx}(x) = \frac{df}{du}(u) \cdot \frac{du}{dx} = \frac{d}{du}e^u \cdot \frac{d}{dx}tan(x) = e^u sec^2(x)$$

$$\frac{df}{dx}(x) = e^{tan(x)} sec^2(x)$$

---

- $y = sin(cos(x))$

$u = cos(x) \Rightarrow y = sin(u)$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = \frac{d}{du}sin(u) \cdot \frac{d}{dx}cos(x) = cos(u)\cdot -sin(x)$$

$$\frac{dy}{dx} = -cos(cos\ x)sin\ x$$

---

- $g(t) = (t^2 + 3)^4$

$u = t^2 + 3 \Rightarrow g(u) = u^4$

$$\frac{dg}{dt}(t) = \frac{dg}{du}(u) \cdot \frac{du}{dt} = \frac{d}{du}u^4 \cdot \frac{d}{dt}(t^2 + 3) = 4u^3\cdot2t$$

$$\frac{dg}{dt}(t) = 8u^3t = 8t(t^2 + 3)^3$$

---

- $f(x) = cos(x^2 + 3)$

$u = x^2 + 3 \Rightarrow f(u) = cos(u)$

$$\frac{df}{dx}(x) = \frac{df}{du}(u) \cdot \frac{du}{dx} = \frac{d}{du}cos(u) \cdot \frac{d}{dx}(x^2 + 3) = -sin(u)2x$$

$$\frac{df}{dx}(x) = -2xsin(x^2 + 3)$$

---

- $y = \sqrt{x + e^x}$

$u = x + e^x \Rightarrow y = \sqrt{u}$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = \frac{d}{du}\sqrt{u} \cdot \frac{d}{dx}(x + e^x) = \frac{1}{2\sqrt{u}}\cdot(1 + e^x)$$

$$\frac{dy}{dx} = \frac{1 + e^x}{2\sqrt{x + e^x}}$$

---

- $y = tan(3x)$

$u = 3x \Rightarrow y = tan(u)$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = \frac{d}{du}tan(u) \cdot \frac{d}{dx}3x = sec^2(u)3 = 3sec^2(3x)$$

---

- $y = sec(3x)$

$u = 3x \Rightarrow y = sec(u)$

$$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx} = \frac{d}{du}sec(u) \cdot \frac{d}{dx}3x = 3tan(u)sec(u)$$

$$\frac{dy}{dx} = 3tan(3x)sec(3x)$$
