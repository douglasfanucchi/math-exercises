### Second Derivative

Calculate the second derivative:

- $y = sin(5t)$

$u = 5t \Rightarrow y = sin(u)$

$$\frac{d^2y}{dt^2} = \frac{d}{dt}\left(\frac{dy}{dt}\right)$$

$$\frac{dy}{dt} = \frac{d}{du}sin(u) \cdot \frac{d}{dt}5t = cos(u)5 = 5cos(5t)$$

$$\frac{dy}{dt} = 5cos\ 5t \Rightarrow \frac{d^2y}{dt^2} = \frac{d}{dt}(5cos\ 5t) = 5\frac{d}{dt}cos(5t) = -25sin(5t)$$

$$\frac{d^2y}{dt^2} = -25sin(5t)$$

---

- $y = cos(4t)$

$$\frac{dy}{dt} = -4sin\ 4t$$

$$\frac{d^2y}{dt^2} = \frac{d}{dt}-4sin\ 4t = -16cos\ 4t$$

$$\frac{d^2y}{dt^2} = -16cos\ 4t$$

---

- $x = sin(wt)$, $w$ is a constant

$$\frac{dx}{dt} = wcos\ wt$$

$$\frac{d^2x}{dt^2} = \frac{d}{dt}wcos\ wt = -w^2sin(wt)$$

$$\frac{d^2x}{dt^2} = -w^2sin\ wt$$

---

- $y = e^{-3x}$

$u = -3x \Rightarrow y = e^u$

$$\frac{dy}{dx} = \frac{d}{du}e^u \cdot \frac{d}{dx}-3x = e^u\cdot-3 = -3e^{-3x}$$

$$\frac{dy}{dx} = -3e^{-3x} \Rightarrow \frac{d^2y}{dx^2} = \frac{d}{dx}-3e^{-3x} = -3\cdot-3e^{-3x} = 9e^{-3x}$$

---

- $y = e^{-x^2}$

$$\frac{dy}{dx} = -2xe^{-x^2}$$

$$\frac{d^2y}{dx^2} = \frac{d}{dx}-2xe^{-x^2} = -2\frac{d}{dx}xe^{-x^2} = -2(e^{-x^2} + x\cdot-2xe^{-x^2})$$

$$\frac{d^2y}{dx^2} = -2e^{-x^2}(1 -2x^2)$$

---

- $y = \frac{e^x}{x + 1}$

$$\frac{dy}{dx} = \frac{e^x(x + 1) - e^x}{(x+ 1)^2}$$

$$\frac{d^2y}{dx^2} = \frac{d}{dx} \frac{e^x(x + 1) - e^x}{(x + 1)^2}$$

$$\frac{d^2y}{dx^2} = \frac{\frac{d}{dx}[e^x(x + 1) - e^x](x + 1)^2 - (e^x(x + 1) - e^x)2(x+1)}{(x + 1)^4}$$

$$\frac{d^2y}{dx^2} = \frac{(e^x(x+1) + e^x - e^x)(x+1)^2-e^x(x+1 - 1)2(x+1)}{(x + 1)^4}$$

$$\frac{d^2y}{dx^2} = \frac{e^x(x + 1)(x+1)^2 - e^xx2(x+1)}{(x+1)^4} = \frac{e^x(x+1)^2 - 2xe^x}{(x + 1)^3}$$

$$\frac{d^2y}{dx^2} = \frac{e^x([x+1]^2 - 2x)}{(x + 1)^3} = \frac{e^x(x^2 + 2x + 1 - 2x)}{(x+1)^3} = \frac{e^x(x^2 + 1)}{(x+1)^3}$$

$$\frac{d^2y}{dx^2} = \frac{e^x(x^2 + 1)}{(x + 1)^3}$$

---

- $y = ln(x^2 + 1)$

$$\frac{dy}{dx} = \frac{2x}{x^2 + 1}$$

$$\frac{d^2y}{dx^2} = \frac{2(x^2 + 1) - 2x2x}{(x^2 + 1)^2} = \frac{2x^2 + 2 - 4x^2}{(x^2 + 1)^2} = \frac{2 - 2x^2}{(x^2 + 1)^2}$$

$$\frac{d^2y}{dx^2} = \frac{2(1 - x^2)}{(x^2 + 1)^2}$$

---

- $y = \frac{x^2}{x - 1}$

$$\frac{dy}{dx} = \frac{2x(x-1) - x^2}{(x - 1)^2} = \frac{2x^2 - 2x - x^2}{(x - 1)^2} = \frac{x^2 - 2x}{(x-1)^2}$$

$$\frac{d^2y}{dx^2} = \frac{(x - 1)^2\frac{d}{dx}(x^2 - 2x) - (x^2 - 2x)\frac{d}{dx}(x - 1)^2}{(x-1)^4}$$

$$\frac{d^2y}{dx^2} = \frac{(x-1)^2(2x - 2) - (x^2 - 2x)2(x-1)}{(x-1)^4}$$

$$\frac{d^2y}{dx^2} = \frac{2(x-1)^3 - 2(x^2-2x)(x-1)}{(x - 1)^4} = \frac{2(x - 1)^2 - 2(x^2 - 2x)}{(x - 1)^3}$$

$$\frac{d^2y}{dx^2} = \frac{2x^2 - 4x + 2 - 2x^2 +
 4x}{(x - 1)^3} = \frac{2}{(x - 1)^3}$$

$$\frac{d^2y}{dx^2} = \frac{2}{(x - 1)^3}$$

---

- $y = e^{-x} - e^{-2x}$

$$u = -x \Rightarrow y = e^u - e^{2u}$$

$$\frac{dy}{dx} = \frac{d}{du}(e^u - e^{2u})\frac{d}{dx}(-x) = -1(e^u - e^{2u}2) = -1(e^u - 2e^{2u})$$

$$\frac{dy}{dx} = 2e^{2u} - e^u = 2e^{-2x} - e^{-x}$$

$$\frac{d^2y}{dx^2} = \frac{d}{du}(2e^{2u} - e^u)\cdot \frac{d}{dx}(-x) = -1(2 e^{2u}2 - e^u) = e^u - 4e^{2u}$$

$$\frac{d^2y}{dx^2} = e^{-x} - 4e^{-2x}$$

---

- $y = e^{-x}cos\ 2x$

$$\frac{dy}{dx} = -e^{-x}cos\ 2x - e^{-x}2sin\ 2x = -e^{-x}(cos\ 2x + 2sin\ 2x)$$

$$\frac{d^2y}{dx^2} = (cos\ 2x + 2sin\ 2x)\frac{d}{dx}(-e^{-x}) + -e^{-x}\frac{d}{dx}(cos\ 2x + 2sin\ 2x)$$

$$\frac{d^2y}{dx^2} = e^{-x}(cos\ 2x + 2sin\ 2x) -e^{-x}(-2sin\ 2x + 4cos\ 2x)$$

$$\frac{d^2y}{dx^2} = e^{-x}(cos\ 2x + 2sin\ 2x +2sin\ 2x - 4cos\ 2x)$$

$$\frac{d^2y}{dx^2} = e^{-x}(4sin\ 2x -3cos\ 2x)$$

---

- $y = \frac{x}{x^2 + 1}$

$$\frac{dy}{dx} = \frac{x^2 + 1 - 2x^2}{(x^2 + 1)^2} = \frac{1- x^2}{(x^2 + 1)^2}$$

$$\frac{d^2y}{dx^2} = \frac{-2x(x^2 + 1)^2 - (1-x^2)2(x^2 + 1)2x}{(x^2 + 1)^4}$$

$$\frac{d^2y}{dx^2} = \frac{-2x(x^2 + 1) + (x^2 -1)4x}{(x^2 + 1)^3} = \frac{-2x^3 - 2x + 4x^3 -4x}{(x^2 + 1)^3}$$

$$\frac{d^2y}{dx^2} = \frac{2x^3-6x}{(x^2 + 1)^3} = \frac{2x(x^2 - 3)}{(x^2 + 1)^3}$$

---

- $y = \frac{3x + 1}{x^2 + x}$

$$\frac{dy}{dx} = \frac{3x^2 + 3x - (3x + 1)(2x + 1)}{(x^2 + x)^2} = \frac{3x^2 + 3x -(6x^2 + 3x + 2x + 1)}{(x^2 + x)^2}$$

$$\frac{dy}{dx} = \frac{-3x^2 -2x - 1}{(x^2 + x)^2}$$

$$\frac{d^2y}{dx^2} = \frac{(x^2 + x)^2\frac{d}{dx}(-3x^2 - 2x - 1) - (-3x^2 - 2x - 1)\frac{d}{dx}(x^2 + x)^2}{(x² + x)^4}$$

$$\frac{d^2y}{dx^2} = \frac{(x^2 + x)^2(-6x -2) + (3x^2 + 2x + 1)2(x^2 + x)(2x + 1)}{(x^2 + x)^4}$$

$$\frac{d^2y}{dx^2} = \frac{(x^2 + x)(-6x - 2) + (3x^2 + 2x + 1)(4x + 2)}{(x^2 + x)^3}$$

$$\frac{d^2y}{dx^2} = \frac{(x^2 + x)(-6x -2) + 12x^3 + 6x^2 + 8x^2+4x + 4x + 2}{(x^2 + x)^3}$$

$$\frac{d^2y}{dx^2} = \frac{(x^2 + x)(-6x -2) + 12x^3 + 14x^2 + 8x + 2}{(x^2 + x)^3}$$

$$\frac{d^2y}{dx^2} = \frac{-6x^3 -2x^2 -6x^2 -2x + 12x^3 + 14x^2 + 8x + 2}{(x^2 + x)^3}$$

$$\frac{d^2y}{dx^2} = \frac{6x^3 + 6x^2 + 6x + 2}{(x^2 + x)^3} = \frac{2(3x^3 + 3x^2 + 3x + 1)}{(x^2 + x)^3}$$

---

- $y = \frac{sin(3x)}{e^x}$

$$\frac{dy}{dx} = \frac{3cos(3x)e^x - sin(3x)e^x}{e^{2x}} = \frac{3cos(3x) - sin(3x)}{e^x}$$

$$\frac{d^2y}{dx^2} = \frac{e^x\frac{d}{dx}[3cos\ 3x - sin\ 3x] - (3cos\ 3x - sin\ 3x)e^x}{e^{2x}}$$

$$\frac{d^2y}{dx^2} = \frac{\frac{d}{dx}[3cos\ 3x - sin\ 3x] - (3cos\ 3x - sin\ 3x)}{e^x}$$

$$\frac{d^2y}{dx^2} = \frac{-9sin\ 3x - 3cos\ 3x - 3cos\ 3x + sin\ 3x}{e^x}$$

$$\frac{d^2y}{dx^2} = \frac{-8sin\ 3x - 6cos\ 3x}{e^x} = \frac{-2[4sin\ 3x + 3cos\ 3x]}{e^x}$$

$$\frac{d^2y}{dx^2} = \frac{-2[4sin\ 3x + 3cos\ 3x]}{e^x}$$

---

- $y = xe^{-2x}$

$$\frac{dy}{dx} = e^{-2x} + x\frac{d}{dx}e^{-2x} = e^{-2x} + x(e^{-2x}\cdot -2) = e^{-2x}(1 - 2x)$$

$$\frac{d^2y}{dx^2} = (1 - 2x)\frac{d}{dx}e^{-2x} + e^{-2x}\cdot-2 = (1 - 2x)e^{-2x}(-2) - 2e^{-2x}$$

$$\frac{d^2y}{dx^2} = -2e^{-2x}(1 + 1-2x) = -4e^{-2x}(1 - x)$$

$$\frac{d^2y}{dx^2} = -4e^{-2x}(1 - x)$$

---

- $y = sin(cos\ x)$

$$\frac{dy}{dx} = cos(cos\ x)\cdot-sin\ x = - cos(cos\ x)sin\ x$$

$$\frac{d^2y}{dx^2} = sin(cos\ x)\cdot -sin\ x sin\ x + (-cos\ (cos\ x))cos\ x$$

$$\frac{d^2y}{dx^2} = -sin^2\ x sin(cos\ x) - cos(cos\ x)cos\ x$$

---

- $f(x) = \frac{4x + 5}{x^2 - 1}$

$$\frac{df}{dx}(x) = \frac{(x^2 - 1)\frac{d}{dx}(4x + 5) -(4x+5)\frac{d}{dx}(x^2 -1)}{(x^2 - 1)^2}$$

$$\frac{
    df
}{
    dx
}(x) = \frac{
    4(x^2-1) - (4x + 5)2x
}{
    (x^2 - 1)^2
}$$

$$\frac{
    df
}{
    dx
}(x) = \frac{
    4x^2 - 4 - 8x^2 - 10x
}{
    (x^2 - 1)^2
}$$

$$\frac{
    df
}{
    dx
}(x) = \frac{
    -4x^2-10x -4
}{
    (x^2 - 1)^2
}$$

$$\frac{
    d^2f
}{
    dx^2
}(x) = \frac{
    (x^2 - 1)^2\frac{
        d
    }{
        dx
    }(-4x^2 - 10x - 4) - (-4x^2 -10x -4) \frac{
        d
    }{
        dx
    }(x^2 - 1)^2
}{
    (x^2 - 1)^4
}$$

$$\frac{
    d^2f
}{
    dx^2
}(x) = \frac{
    (x^2 - 1)^2 (-8x -10) - (-4x^2 -10x -4)2(x^2 - 1)2x
}{
    (x^2 - 1)^4
}$$

$$\frac{
    d^2f
}{
    dx^2
}(x) = \frac{
    (x^2 - 1) (-8x -10) - (-4x^2 -10x -4)2\cdot 2x
}{
    (x^2 - 1)^3
}$$

$$\frac{
    d^2f
}{
    dx^2
}(x) = \frac{
    (x^2-1)(-8x -10) - (-16x^3 -40x^2 - 16x)
}{
    (x^2 - 1)^3
}$$

$$\frac{
    d^2f
}{
    dx^2
}(x) = \frac{
    -8x^3 -10x^2 +8x + 10 + 16x^3 + 40x^2 + 16x
}{
    (x^2 - 1)^3
}$$

$$\frac{
    d^2f
}{
    dx^2
}(x) = \frac{
    8x^3 + 30x^2 + 24x + 10
}{
    (x^2 - 1)^3
}$$

---

- $y = xe^{\frac{1}{x}}$

$$\frac{
    dy
}{
    dx
} xe^{\frac{1}{x}} = e^\frac{1}{x} + xe^\frac{1}{x}(-x^{-2}) = e^\frac{1}{x} -x^{-1}e^\frac{1}{x}$$

$$\frac{
    d^2y
}{
    dx^2
} = -e^\frac{1}{x}x^{-2} - \frac{
    d
}{
    dx
}x^{-1}e^\frac{1}{x}$$

$$\frac{
    d
}{
    dx
} x^{-1}e^\frac{1}{x} = -x^{-2}e^\frac{1}{x} + x^{-1}e^\frac{1}{x}(-x^{-2}) = -e^\frac{1}{x}x^{-2} - e^\frac{1}{x}x^{-3}$$

$$\frac{
    d^2y
}{
    dx^2
}  = -e^\frac{1}{x}x^{-2} -(-e^\frac{1}{x}x^{-2} - e^\frac{1}{x}x^{-3}) = -e^\frac{1}{x}x^{-2} + e^\frac{1}{x}x^{-2} + e^\frac{1}{x}x^{-3} = \frac{
    e^\frac{1}{x}
}{
    x^3
}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{
    e^\frac{1}{x}
}{
    x^3
}$$

---

- $y = \frac{x^2}{x^2 + x + 1}$

$$\frac{dy}{dx} = \frac{
    2x(x^2 + x + 1) - x^2\frac{d}{dx}(x^2 + x + 1)
}{
    (x^2 + x + 1)^2
}$$

$$\frac{
    d
}{
    dx
} (x^2 + x + 1) = 2x + 1$$

$$\frac{
    dy
}{
    dx
} = \frac{
    2x(x^2 + x + 1) - x^2(2x + 1)
}{
    (x^2 + x + 1)^2
} = \frac{
    2x^3 + 2x^2 + 2x - 2x^3 - x^2
}{
    (x^2 + x + 1)^2
} = \frac{
    x^2 + 2x
}{
    (x^2 + x + 1)^2
}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{
    (x^2 + x + 1)^2 \frac{d}{dx}(x^2 + 2x) - (x^2 + 2x)\frac{d}{dx}(x^2 + x + 1)^2
}{
    (x^2 + x + 1)^4
}$$

$$\frac{d}{dx}(x^2 +2x) = 2x + 2 = 2(x+ 1)$$

$$\frac{d}{dx}(x^2 + x + 1)^2 = 2(x^2 + x + 1)(2x + 1)$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{(x^2 + x + 1)^2 2(x + 1) - (x^2 + 2x)\cdot 2(x^2 + x + 1)(2x + 1)}{(x^2 + x + 1)^4}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{(x^2 + x + 1)2(x + 1) - (x^2 + 2x)\cdot 2(2x + 1)}{(x^2 + x + 1)^3}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{
    2(x^3 + x^2 + x + x^2 + x + 1) - 2(2x^3 + 4x^2 + x^2 + 2x)
}{
    (x^2 + x + 1)^3
}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{
    2(x^3 + 2x^2 + 2x + 1) - 2(2x^3 + 5x^2 + 2x)
}{
    (x^2 + x + 1)^3
}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{
    2(x^3+2x^2+2x +1-2x^3-5x^2 - 2x)
}{
    (x^2 + x + 1)^3
}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{
    2(-x^3 - 3x^2 + 1)
}{
    (x^2 + x + 1)^3
}$$

---

- $g(t) = \sqrt{t^2 + 3}$

$$\frac{
    dg
}{
    dt
}(t) = \frac{
    1
}{2\sqrt{t^2 + 3}} \cdot 2t = \frac{
    2t
}{
    2\sqrt{t^2 + 3}
} = \frac{
    t
}{\sqrt{t^2 + 3}}$$

$$\frac{
    d^2g
}{
    dt^2
}(t) = \frac{
    \sqrt{t^2 + 3} - \frac{
        t \cdot t
    }{
        \sqrt{t^2 + 3}
    }
}{
    t^2 + 3
} = \frac{
    t^2 + 3-t^2
}{
    (t^2 + 3)(\sqrt{t^2 + 3})
}$$

$$\frac{
    d^2g
}{
    dt^2
}(t) = \frac{
    3
}{
    (t^2 + 3)\sqrt{t^2 + 3}
}$$

---

- $y = x\sqrt[3]{x + 2}$ 

$$\frac{
    dy
}{
    dx
} = \sqrt[3]{x+2} + \frac{
    x
}{
    3\sqrt[3]{(x + 2)^2}
}$$

$$\frac{
    d
}{
    dx
}3\sqrt[3]{(x+2)^2} = 3(\frac{
    1
}{
    3\sqrt[3]{(x+2)^4}
})\cdot 2(x+2) = \frac{
    2(x+ 2)
}{\sqrt[3]{(x+2)^4}} = \frac{
    2
}{
    \sqrt[3]{x+2}
}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{
    1
}{
    3\sqrt[3]{(x + 2)^2}
} + \frac{
    3\sqrt[3]{(x+2)^2} - x\frac{
        2
    }{
        \sqrt[3]{x + 2}
    }
}{
    9\sqrt[3]{(x+2)^4}
} = \frac{
    1
}{
    3\sqrt[3]{(x+ 2)^2}
} + \frac{
    3(x+2) - 2x
}{
    9\sqrt[3]{(x+2)^4} \sqrt[3]{x+2}
}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{
    1
}{
    3\sqrt[3]{(x+ 2)^2}
} + \frac{
    x + 6
}{
    9\sqrt[3]{(x+2)^2}(x+2)
} = \frac{
    3(x + 2) + x + 6
}{
    9\sqrt[3]{(x+2)^2}(x+2)
} = \frac{
    4x + 12
}{
    9\sqrt[3]{(x+2)^2}(x+2)
}$$

$$\frac{
    d^2y
}{
    dx^2
} = \frac{
    4x + 12
}{
    9\sqrt[3]{(x+2)^5}
}$$

---
