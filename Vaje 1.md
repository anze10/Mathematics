

## 1. vaja - Kompleksna števila
$$
w = (5+2i)^{2}+(1-2i)^{3}-(4+3i)*(3-2i)+13*(1-i) / (2+3i)+5-14i
$$

### Postopek reševanja:

**Korak 1:** Najprej računamo vsak člen posebej:

$(5+2i)^2 = 25 + 20i + 4i^2 = 25 + 20i - 4 = 21 + 20i$

$(1-2i)^3 = (1-2i)(1-2i)(1-2i)$
- Najprej: $(1-2i)^2 = 1 - 4i + 4i^2 = 1 - 4i - 4 = -3 - 4i$
- Nato: $(-3-4i)(1-2i) = -3 + 6i - 4i + 8i^2 = -3 + 2i - 8 = -11 + 2i$

$(4+3i)(3-2i) = 12 - 8i + 9i - 6i^2 = 12 + i + 6 = 18 + i$

$13(1-i) = 13 - 13i$

**Korak 2:** Delitev $(2+3i) + 5 - 14i = 7 - 11i$ (imenovalec)
Delimo $13(1-i)$ z $(7-11i)$:
$$\frac{13-13i}{7-11i} = \frac{(13-13i)(7+11i)}{(7-11i)(7+11i)} = \frac{91 + 143i - 91i - 143i^2}{49 + 121} = \frac{91 + 52i + 143}{170} = \frac{234 + 52i}{170} = \frac{117 + 26i}{85}$$

**Korak 3:** Seštejemo vse člene:
$$w = (21+20i) + (-11+2i) - (18+i) + \frac{117+26i}{85}$$
$$w = 21 + 20i - 11 + 2i - 18 - i + \frac{117+26i}{85}$$
$$w = -8 + 21i + \frac{117+26i}{85} = \frac{-680 + 1785i + 117 + 26i}{85} = \frac{-563 + 1811i}{85}$$

### Določitve:

**Re(w)** (realni del): $\text{Re}(w) = -\frac{563}{85} \approx -6.62$

**Im(w)** (imaginarni del): $\text{Im}(w) = \frac{1811}{85} \approx 21.31$

**w s črto** (konjugirano): $\overline{w} = -\frac{563}{85} - \frac{1811i}{85}$

**Absolutna vrednost w**: $|w| = \sqrt{\left(\frac{-563}{85}\right)^2 + \left(\frac{1811}{85}\right)^2} = \frac{1}{85}\sqrt{563^2 + 1811^2} = \frac{1}{85}\sqrt{316969 + 3279721} = \frac{\sqrt{3596690}}{85} \approx 22.27$


---

## 2. Definicijska območja

**Definicija:** Definicijsko območje funkcije je množica vseh vrednosti spremenljivke $x$, za katere je funkcija definirana (obstaja).

### a) $f(x)=\sqrt{x^2-4x+3}$

**Postopek:**
Funkcija je definirana, ko je izraz pod korenom **nenegativen** (≥ 0):
$$x^2 - 4x + 3 \geq 0$$

Rešimo enačbo $x^2 - 4x + 3 = 0$:
$$x = \frac{4 \pm \sqrt{16-12}}{2} = \frac{4 \pm 2}{2}$$
$$x_1 = 1, \quad x_2 = 3$$

Parabola $(x-1)(x-3)$ je pozitivna **zunaj ničel**.

**Definicijsko območje:** $D_f = (-\infty, 1] \cup [3, +\infty)$ ali $x \in \mathbb{R} \setminus (1, 3)$

---

### b) $f(x) = \ln\frac{x-1}{2x+7} + \sqrt{x^{2} -4}$

**Postopek:**
Funkcija je definirana, ko veljata **oba pogoja**:

**Pogoj 1:** Logaritem je definiran za pozitiven argument:
$$\frac{x-1}{2x+7} > 0$$

Ničle in poles:
- Števec: $x = 1$
- Imenovalec: $x = -\frac{7}{2} = -3.5$

Analiziramo predznak po intervalih:
- $x < -3.5$: obe negativni → pozitivno ✓
- $-3.5 < x < 1$: negativno/pozitivno → negativno ✗
- $x > 1$: obe pozitivni → pozitivno ✓

**Pogoj 2:** Koren je definiran:
$$x^2 - 4 \geq 0$$
$$(x-2)(x+2) \geq 0$$
$$x \in (-\infty, -2] \cup [2, +\infty)$$

**Presek obeh pogojev:**
- Iz pogoja 1: $(-\infty, -3.5) \cup (1, +\infty)$
- Iz pogoja 2: $(-\infty, -2] \cup [2, +\infty)$

**Definicijsko območje:** $D_f = (-\infty, -3.5) \cup [2, +\infty)$

---

## 3. Kompozitum funkcij

**Definicija:** Kompozitum funkcij $(f \circ g)(x)$ pomeni $f(g(x))$, torej najprej uporabimo funkcijo $g$, nato pa rezultat vstavimo v funkcijo $f$.

Dani funkciji:
$$f(x) = x^{-1} = \frac{1}{x}$$
$$g(x) = \frac{2}{1-x}$$

---

### a) $(f \circ g)(x) = f(g(x))$

**Postopek:**
Vstavimo $g(x)$ v funkcijo $f$:
$$f(g(x)) = f\left(\frac{2}{1-x}\right) = \frac{1}{\frac{2}{1-x}} = \frac{1-x}{2}$$

**Rezultat:** $(f \circ g)(x) = \frac{1-x}{2}$

**Definicijsko območje:**
- $g(x)$ je definirana za $x \neq 1$
- $f(g(x))$ potrebuje $g(x) \neq 0$, torej $\frac{2}{1-x} \neq 0$ (vedno drži)

$D_{f \circ g} = \mathbb{R} \setminus \{1\}$

---

### b) $(g \circ f)(x) = g(f(x))$

**Postopek:**
Vstavimo $f(x)$ v funkcijo $g$:
$$g(f(x)) = g\left(\frac{1}{x}\right) = \frac{2}{1-\frac{1}{x}} = \frac{2}{\frac{x-1}{x}} = \frac{2x}{x-1}$$

**Rezultat:** $(g \circ f)(x) = \frac{2x}{x-1}$

**Definicijsko območje:**
- $f(x)$ je definirana za $x \neq 0$
- $g(f(x))$ potrebuje $1 - \frac{1}{x} \neq 0$, torej $x \neq 1$

$D_{g \circ f} = \mathbb{R} \setminus \{0, 1\}$

---

## 4. Enačba premice skozi dve točki

Točki: $A(-1, 3)$ in $B(2, -1)$

### Postopek:

**Korak 1:** Izračunamo smerni koeficient $k$:
$$k = \frac{y_2 - y_1}{x_2 - x_1} = \frac{-1 - 3}{2 - (-1)} = \frac{-4}{3} = -\frac{4}{3}$$

**Korak 2:** Uporabimo točko $A(-1, 3)$ in obliko $y - y_1 = k(x - x_1)$:
$$y - 3 = -\frac{4}{3}(x + 1)$$
$$y - 3 = -\frac{4}{3}x - \frac{4}{3}$$
$$y = -\frac{4}{3}x - \frac{4}{3} + 3$$
$$y = -\frac{4}{3}x + \frac{5}{3}$$

---

### Tri oblike enačbe premice:

**1. Eksplicitna oblika:** $y = kx + n$
$$y = -\frac{4}{3}x + \frac{5}{3}$$

**2. Implicitna (splošna) oblika:** $Ax + By + C = 0$
$$4x + 3y - 5 = 0$$
(Pomnožimo z 3 in preuredimo)

**3. Odsekovna oblika:** $\frac{x}{a} + \frac{y}{b} = 1$

Iz $4x + 3y = 5$ delimo s 5:
$$\frac{4x}{5} + \frac{3y}{5} = 1$$
$$\frac{x}{\frac{5}{4}} + \frac{y}{\frac{5}{3}} = 1$$

Odsekovna oblika: $\frac{x}{1.25} + \frac{y}{1.67} = 1$ (premica seka x-os v $x = 1.25$ in y-os v $y = 1.67$) 



---

## 5. Premica skozi presečišče dveh premic in točko T

Premici:
- $p_1: 3x + 2y - 13 = 0$
- $p_2: 7x - 4y - 13 = 0$

Točka: $T(2, -3)$

### Postopek:

**Korak 1:** Najdemo presečišče $P$ premic $p_1$ in $p_2$:

Iz prve enačbe:
$$3x + 2y = 13 \quad \Rightarrow \quad y = \frac{13 - 3x}{2}$$

Vstavimo v drugo enačbo:
$$7x - 4 \cdot \frac{13 - 3x}{2} - 13 = 0$$
$$7x - 2(13 - 3x) - 13 = 0$$
$$7x - 26 + 6x - 13 = 0$$
$$13x = 39$$
$$x = 3$$

Izračunamo $y$:
$$y = \frac{13 - 3 \cdot 3}{2} = \frac{4}{2} = 2$$

**Presečišče:** $P(3, 2)$

---

**Korak 2:** Premica gre skozi $P(3, 2)$ in $T(2, -3)$:

Smerni koeficient:
$$k = \frac{-3 - 2}{2 - 3} = \frac{-5}{-1} = 5$$

Enačba premice skozi $T(2, -3)$:
$$y - (-3) = 5(x - 2)$$
$$y + 3 = 5x - 10$$
$$y = 5x - 13$$

**Enačba premice:** $y = 5x - 13$ ali $5x - y - 13 = 0$

---

**Graf:** _(Lahko narišeš v GeoGebra ali na papir)_
- Premica $p_1$ seka osi v $(13/3, 0)$ in $(0, 13/2)$
- Premica $p_2$ seka osi v $(13/7, 0)$ in $(0, -13/4)$
- Presečišče: $P(3, 2)$
- Iskana premica skozi $P(3, 2)$ in $T(2, -3)$ z enačbo $y = 5x - 13$


---

## 6. Reši kvadratne enačbe

### a) $x^2 + 3x - 10 = 0$

**Postopek:**
Uporabimo kvadratno formulo: $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$

Za $a=1, b=3, c=-10$:
$$x = \frac{-3 \pm \sqrt{9 - 4(1)(-10)}}{2} = \frac{-3 \pm \sqrt{9 + 40}}{2} = \frac{-3 \pm \sqrt{49}}{2} = \frac{-3 \pm 7}{2}$$

$$x_1 = \frac{-3 + 7}{2} = \frac{4}{2} = 2$$
$$x_2 = \frac{-3 - 7}{2} = \frac{-10}{2} = -5$$

**Rešitvi:** $x_1 = 2, \quad x_2 = -5$

---

### b) $2x^2 + 7x - 15 = 0$

**Postopek:**
Za $a=2, b=7, c=-15$:
$$x = \frac{-7 \pm \sqrt{49 - 4(2)(-15)}}{4} = \frac{-7 \pm \sqrt{49 + 120}}{4} = \frac{-7 \pm \sqrt{169}}{4} = \frac{-7 \pm 13}{4}$$

$$x_1 = \frac{-7 + 13}{4} = \frac{6}{4} = \frac{3}{2}$$
$$x_2 = \frac{-7 - 13}{4} = \frac{-20}{4} = -5$$

**Rešitvi:** $x_1 = \frac{3}{2}, \quad x_2 = -5$

---

### c) $2x - x^2 - 5 = 0$ → preuredimo v $-x^2 + 2x - 5 = 0$ ali $x^2 - 2x + 5 = 0$

**Postopek:**
Za $a=1, b=-2, c=5$:
$$x = \frac{2 \pm \sqrt{4 - 4(1)(5)}}{2} = \frac{2 \pm \sqrt{4 - 20}}{2} = \frac{2 \pm \sqrt{-16}}{2} = \frac{2 \pm 4i}{2} = 1 \pm 2i$$

**Rešitvi (kompleksni):** $x_1 = 1 + 2i, \quad x_2 = 1 - 2i$


---

## 7. Enačba parabole

**Pogoji:**
- Ničla v $x = -1$
- Seka ordinatno os (y-os) v $A(0, -1)$
- Poteka skozi točko $B(1, 4)$

### Postopek:

**Korak 1:** Splošna oblika parabole: $y = ax^2 + bx + c$

**Pogoj 1:** Seka y-os v $A(0, -1)$ → $c = -1$
$$y = ax^2 + bx - 1$$

**Pogoj 2:** Ničla v $x = -1$ → $y(-1) = 0$:
$$a(-1)^2 + b(-1) - 1 = 0$$
$$a - b - 1 = 0$$
$$a = b + 1 \quad \text{...(1)}$$

**Pogoj 3:** Poteka skozi $B(1, 4)$ → $y(1) = 4$:
$$a(1)^2 + b(1) - 1 = 4$$
$$a + b = 5 \quad \text{...(2)}$$

---

**Korak 2:** Rešimo sistem enačb:

Iz (1): $a = b + 1$

Vstavimo v (2):
$$(b + 1) + b = 5$$
$$2b + 1 = 5$$
$$2b = 4$$
$$b = 2$$

Torej: $a = 2 + 1 = 3$

---

**Enačba parabole:** $y = 3x^2 + 2x - 1$

**Preverjanje:**
- $y(0) = -1$ ✓
- $y(-1) = 3 - 2 - 1 = 0$ ✓
- $y(1) = 3 + 2 - 1 = 4$ ✓ 

---

## 8. Izračunaj izraz z logaritmi

**Izraz (interpretiram):**
$$e^{\ln(1/3)} + \log_4(4^5) + \log 2 + \log\left(\sqrt[3]{16}\right)$$

_(Opomba: če je izraz drugačen, prosim sporoči)_

### Postopek:

**Člen 1:** $e^{\ln(1/3)}$

Lastnost: $e^{\ln x} = x$
$$e^{\ln(1/3)} = \frac{1}{3}$$

---

**Člen 2:** $\log_4(4^5)$

Lastnost: $\log_a(a^x) = x$
$$\log_4(4^5) = 5$$

---

**Člen 3:** $\log 2$ (predpostavljam $\log_{10}$)
$$\log_{10} 2 \approx 0.301$$

---

**Člen 4:** $\log\left(\sqrt[3]{16}\right) = \log(16^{1/3})$

Lastnost: $\log(a^b) = b \cdot \log a$
$$\log(16^{1/3}) = \frac{1}{3} \log 16 = \frac{1}{3} \log(2^4) = \frac{1}{3} \cdot 4 \log 2 = \frac{4}{3} \log 2$$

---

**Končni rezultat:**
$$e^{\ln(1/3)} + \log_4(4^5) + \log 2 + \log\left(\sqrt[3]{16}\right)$$
$$= \frac{1}{3} + 5 + \log 2 + \frac{4}{3}\log 2$$
$$= \frac{1}{3} + 5 + \log 2 \left(1 + \frac{4}{3}\right)$$
$$= \frac{1}{3} + 5 + \frac{7}{3}\log 2$$

**Numerično:**
$$\approx 0.333 + 5 + \frac{7}{3}(0.301) \approx 0.333 + 5 + 0.702 \approx 6.035$$

**Točen rezultat:** $\frac{1}{3} + 5 + \frac{7}{3}\log 2 = \frac{16}{3} + \frac{7}{3}\log 2$

