### Chain Rule

Let $y = f(u)$ and $u = g(x)$ being both differentiable and for all $x \in D(g)$ we have that $g(x) \in D(f)$. We can conclude that $f(g(x))$ is differentiable and $\frac{dy}{dx} = \frac{dy}{du}\frac{du}{dx}$

## Proof

If $\Delta u = g(x + \Delta x) - g(x) \neq 0$, $x$ and $x + \Delta x$ $\in D(g)$ then:

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