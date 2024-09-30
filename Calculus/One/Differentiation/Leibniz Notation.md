### Leibniz Notation

- $y = 5x^3 + 6x - 1$

$$\frac{dy}{dx} = \frac{d}{dy}(5x^3 + 6x - 1) = 15x^2 + 6$$

- $s = \sqrt[5]{t} + \frac{3}{t}$

$$\frac{ds}{dt} = \frac{d}{dt}\left(\sqrt[5]{t} + \frac{3}{t}\right) = \frac{1}{5\sqrt[5]{t^4}} + \frac{-3}{t^2}$$

- $x =  \frac{t}{t + 1}$

$$\frac{dx}{dt} = \frac{d}{dt}\left(\frac{t}{t+1}\right) = \frac{t + 1 - t}{(t+1)^2} = \frac{t}{(t + 1)^2}$$

- $y = tcos(t)$

$$\frac{dy}{dt} = \frac{d}{dt}(tcos(t)) = cos(t)\frac{d}{dt}t + t\frac{d}{dt}cos(t) = cos(t) +t(-sin(t))$$

$$cos(t) - tsin(t)$$

- $y = \frac{u + 1}{ln(u)}$

$$\frac{dy}{du} = \frac{d}{du}\left(\frac{u + 1}{ln(u)}\right) = \frac{ln(u)\frac{d}{du}(u+1) - (u+1)\frac{d}{du}ln(u)}{ln^2(u)}$$

$$\frac{ln(u) - (u+1)\frac{1}{u}}{ln^2(u)} = \frac{ln(u) - 1 - \frac{1}{u}}{ln^2(u)}$$

- $x = t^3 e^t$

$$\frac{dx}{dt} = \frac{d}{dt}t^3 e^t = e^t\frac{d}{dt}t^3 + t^3\frac{d}{dt}e^t = e^t 3t^2 + t^3e^t = e^t(3t^2 + t^3)$$

- $s = e^t tan(t)$

$$\frac{ds}{dt} = tan(t)\frac{d}{dt}e^t + e^t\frac{d}{dt}tan(t) = tan(t) e^t + e^t sec^2(t)$$

- $y = \frac{x^3 + 1}{sin(x)}$

$$\frac{dy}{dx} = \frac{d}{dy}\left(\frac{x^3 + 1}{sin(x)}\right) = \frac{sin(x)\frac{d}{dy}(x^3 + 1) - (x^3 + 1)\frac{d}{dy}sin(x)}{sin^2(x)}$$

$$= \frac{3x^2sin(x) - (x^3 + 1)cos(x)}{sin^2(x)}$$

- $y = \sqrt[3]{u}\cdot sec(u)$

$$\frac{dy}{du} = \frac{d}{du}\sqrt[3]{u}\cdot sec(u) = sec(u)\frac{d}{du}\sqrt[3]{u} + \sqrt[3]{u}\frac{d}{du}sec(u)$$

$$= sec(u) \frac{1}{3\sqrt[3]{u^2}} + \sqrt[3]{u}\cdot tan(u)\cdot sec(u)$$

$$ = sec(u)\left[\frac{1}{3\sqrt[3]{u^2}} + \sqrt[3]{u} \cdot tan(u)\right] = sec(u)\left[\frac{1+3\cdot u \cdot tan(u)}{3\sqrt[3]{u^2}}\right]$$

- $x = \frac{3}{t} + \frac{2}{t^2}$

$$\frac{dx}{dt} = \frac{d}{dt}\left(\frac{3}{t} + \frac{2}{t^2}\right) = \frac{d}{dt}\left(\frac{3}{t}\right) + \frac{d}{dt}\left(\frac{2}{t^2}\right) = \frac{-3}{t^2} + \frac{-4t}{t^4}$$

- $x = e^t cos(t)$

$$\frac{dx}{dt} = \frac{d}{dt}[e^t cos(t)] = cos(t)\frac{d}{dt}e^t + e^t\frac{d}{dt}cos(t) = cos(t) e^t+e^t(-sin(t))$$

$$=cos(t) e^t - e^t sin(t) = e^t[cos(t) - sin(t)]$$

- $u = 5v^2  + \frac{3}{v^4}$

$$\frac{du}{dv} = \frac{d}{dv}\left(5v^2 + \frac{3}{v^4}\right) = \frac{d}{dv}5v^2 + \frac{d}{dv}\left(\frac{3}{v^4}\right)= 10v +\frac{-3\frac{d}{dv}v^4}{v^8}$$

$$ = 10v + \frac{-3\cdot4v^3}{v^8} = 10v + \frac{-12v^3}{v^8} = 10v + \frac{-12}{v^5}$$

- $V = \frac{4}{3} \pi r^3$

$$\frac{dV}{dr} = \frac{d}{dr}\left(\frac{4}{3} \pi r^3\right) = \frac{4 \pi}{3}\frac{d}{dr}r^3 = \frac{4 \pi}{3} \cdot 3r^2 = 4 \pi r^2$$

- $E = \frac{1}{2} v^2$

$$\frac{dE}{dv} = \frac{d}{dv}\left(\frac{1}{2}v^2\right) = \frac{1}{2} \frac{d}{dv} v^2 = \frac{1}{2} \cdot 2v = v$$

- $E = \frac{1}{2}mv^2$, $m$ is constant

$$\frac{dE}{dv} = \frac{d}{dV}\left(\frac{1}{2}mv^2\right) = \frac{m}{2}\frac{d}{dV}v^2 = \frac{m}{2}\cdot 2v = mv$$

- $U = \frac{a}{x^{12}} - \frac{b}{x^6}$, $a$ and $b$ constants

$$\frac{dU}{dx}= \frac{d}{dx} \left(\frac{a}{x^{12}} - \frac{b}{x^6}\right) = \frac{d}{dx}\left(\frac{a}{x^{12}}\right) - \frac{d}{dx}\left(\frac{b}{x^6}\right)$$

$$= \frac{-a\frac{d}{dx}x^{12}}{x^{24}} - \frac{-b\frac{d}{dx}x^6}{x^{12}} = \frac{-12ax^{11}}{x^{24}} - \frac{-6bx^5}{x^{12}} = \frac{-12a}{x^{13}}+\frac{6b}{x^7}$$
