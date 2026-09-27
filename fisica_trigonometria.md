# Trigonometría — Física · 1.º Bachillerato

## 1. Grados y radianes

Un **radián** es el ángulo cuyo arco tiene la misma longitud que el radio.

Una vuelta completa:

$$
360^\circ=2\pi\ \text{rad}
$$

Por tanto:

$$
\boxed{180^\circ=\pi\ \text{rad}}
$$

### Grados → radianes

$$
\boxed{\alpha_{\text{rad}}=\alpha_{\text{grados}}\frac{\pi}{180}}
$$

### Radianes → grados

$$
\boxed{\alpha_{\text{grados}}=\alpha_{\text{rad}}\frac{180}{\pi}}
$$

| Grados | Radianes |
|---:|---:|
| $0^\circ$ | $0$ |
| $30^\circ$ | $\pi/6$ |
| $45^\circ$ | $\pi/4$ |
| $60^\circ$ | $\pi/3$ |
| $90^\circ$ | $\pi/2$ |
| $180^\circ$ | $\pi$ |
| $270^\circ$ | $3\pi/2$ |
| $360^\circ$ | $2\pi$ |

---

# 2. Razones trigonométricas

En un triángulo rectángulo, respecto a un ángulo $\alpha$:

$$
\boxed{\sin\alpha=
\frac{\text{cateto opuesto}}{\text{hipotenusa}}}
$$

$$
\boxed{\cos\alpha=
\frac{\text{cateto adyacente}}{\text{hipotenusa}}}
$$

$$
\boxed{\tan\alpha=
\frac{\text{cateto opuesto}}{\text{cateto adyacente}}}
$$

### Regla para recordar

**SOH — CAH — TOA**

$$
\text{SOH:}\quad
\sin=\frac{O}{H}
$$

$$
\text{CAH:}\quad
\cos=\frac{A}{H}
$$

$$
\text{TOA:}\quad
\tan=\frac{O}{A}
$$

---

# 3. Teorema de Pitágoras

Para un triángulo rectángulo:

$$
\boxed{a^2+b^2=c^2}
$$

donde $c$ es la hipotenusa.

Por tanto:

$$
c=\sqrt{a^2+b^2}
$$

También podemos despejar cualquiera de los catetos:

$$
a=\sqrt{c^2-b^2}
$$

$$
b=\sqrt{c^2-a^2}
$$

---

# 4. Seno y coseno como componentes

Esta es una de las aplicaciones más importantes en Física.

Si una magnitud $A$ forma un ángulo $\alpha$ **con el eje horizontal**:

$$
\boxed{A_x=A\cos\alpha}
$$

$$
\boxed{A_y=A\sin\alpha}
$$

Es decir:

$$
\boxed{
A
\longrightarrow
\begin{cases}
A_x=A\cos\alpha\\
A_y=A\sin\alpha
\end{cases}}
$$

### Regla práctica

Respecto al ángulo que estamos utilizando:

- **coseno → componente adyacente**
- **seno → componente opuesta**

⚠️ Por tanto, no hay que memorizar siempre «$x=$ coseno, $y=$ seno».

Si el ángulo se mide respecto al eje vertical, pueden intercambiarse:

$$
A_y=A\cos\alpha
$$

$$
A_x=A\sin\alpha
$$

**Mira siempre desde qué eje está medido el ángulo.**

---

# 5. De componentes a módulo

Si conocemos las componentes:

$$
A_x,\qquad A_y
$$

aplicamos Pitágoras:

$$
\boxed{A=\sqrt{A_x^2+A_y^2}}
$$

### Ejemplo

Si:

$$
A_x=3,\qquad A_y=4
$$

entonces:

$$
A=\sqrt{3^2+4^2}
=\sqrt{25}
=5
$$

---

# 6. De componentes a ángulo

Como:

$$
\tan\alpha=\frac{A_y}{A_x}
$$

podemos utilizar la función inversa:

$$
\boxed{
\alpha=
\arctan\left(\frac{A_y}{A_x}\right)
}
$$

### Ejemplo

Si:

$$
A_x=4,\qquad A_y=3
$$

entonces:

$$
\alpha=
\arctan\left(\frac34\right)
\approx36.9^\circ
$$

⚠️ Hay que tener en cuenta los signos de $A_x$ y $A_y$ para determinar correctamente el cuadrante.

---

# 7. Funciones trigonométricas inversas

Sirven para encontrar un **ángulo** a partir de una razón.

Si:

$$
\sin\alpha=x
$$

entonces:

$$
\boxed{\alpha=\arcsin(x)}
$$

Si:

$$
\cos\alpha=x
$$

entonces:

$$
\boxed{\alpha=\arccos(x)}
$$

Si:

$$
\tan\alpha=x
$$

entonces:

$$
\boxed{\alpha=\arctan(x)}
$$

En la calculadora suelen aparecer como:

- $\sin^{-1}$
- $\cos^{-1}$
- $\tan^{-1}$

⚠️ $\sin^{-1}x$ significa aquí **arcoseno**, no $1/\sin x$.

---

# 8. Circunferencia trigonométrica

En una circunferencia de radio $1$, un punto determinado por el ángulo $\alpha$ tiene coordenadas:

$$
\boxed{(\cos\alpha,\sin\alpha)}
$$

Por tanto:

$$
x=\cos\alpha
$$

$$
y=\sin\alpha
$$

Esto permite extender seno y coseno más allá de los triángulos rectángulos.

### Signos según el cuadrante

| Cuadrante | $\sin$ | $\cos$ | $\tan$ |
|---|:---:|:---:|:---:|
| I | $+$ | $+$ | $+$ |
| II | $+$ | $-$ | $-$ |
| III | $-$ | $-$ | $+$ |
| IV | $-$ | $+$ | $-$ |

---

# 9. Identidad fundamental

La identidad trigonométrica más importante:

$$
\boxed{\sin^2\alpha+\cos^2\alpha=1}
$$

De ella:

$$
\boxed{\sin^2\alpha=1-\cos^2\alpha}
$$

$$
\boxed{\cos^2\alpha=1-\sin^2\alpha}
$$

También:

$$
\boxed{
\tan\alpha=\frac{\sin\alpha}{\cos\alpha}
}
$$

### Ejemplo

Si:

$$
\sin\alpha=0.6
$$

entonces:

$$
\cos^2\alpha=1-0.6^2
$$

$$
\cos^2\alpha=0.64
$$

$$
\cos\alpha=\pm0.8
$$

El signo depende del cuadrante.

Si $\alpha$ está en el primer cuadrante:

$$
\boxed{\cos\alpha=0.8}
$$

y:

$$
\tan\alpha=\frac{0.6}{0.8}=0.75
$$

---

# 10. Ángulos frecuentes

Conviene reconocer estos valores:

| $\alpha$ | $\sin\alpha$ | $\cos\alpha$ | $\tan\alpha$ |
|---:|---:|---:|---:|
| $0^\circ$ | $0$ | $1$ | $0$ |
| $30^\circ$ | $1/2$ | $\sqrt3/2$ | $1/\sqrt3$ |
| $45^\circ$ | $\sqrt2/2$ | $\sqrt2/2$ | $1$ |
| $60^\circ$ | $\sqrt3/2$ | $1/2$ | $\sqrt3$ |
| $90^\circ$ | $1$ | $0$ | No definida |

---

# 11. El esquema fundamental para Física

Muchísimos problemas se reducen a este triángulo:

### Módulo + ángulo → componentes

$$
\boxed{
A_x=A\cos\alpha
}
$$

$$
\boxed{
A_y=A\sin\alpha
}
$$

### Componentes → módulo

$$
\boxed{
A=\sqrt{A_x^2+A_y^2}
}
$$

### Componentes → ángulo

$$
\boxed{
\alpha=\arctan\left(\frac{A_y}{A_x}\right)
}
$$

Por tanto:

$$
\boxed{
(A,\alpha)
\quad\Longleftrightarrow\quad
(A_x,A_y)
}
$$

Este mismo esquema aparecerá después con:

- desplazamientos
- velocidades
- aceleraciones
- fuerzas
- movimiento parabólico
- planos inclinados

---

# 12. Calculadora: cuidado con DEG y RAD

Antes de calcular una función trigonométrica, comprueba el modo de la calculadora.

Si el ángulo está en grados:

$$
30^\circ\quad\Rightarrow\quad\boxed{\text{DEG}}
$$

Si está en radianes:

$$
\frac{\pi}{6}\quad\Rightarrow\quad\boxed{\text{RAD}}
$$

Por ejemplo:

$$
\sin 30^\circ=0.5
$$

y:

$$
\sin\left(\frac{\pi}{6}\right)=0.5
$$

pero la calculadora debe estar en el modo correspondiente.

---

# RESUMEN RÁPIDO

### Triángulo rectángulo

$$
\boxed{
\sin\alpha=\frac{opuesto}{hipotenusa}
}
$$

$$
\boxed{
\cos\alpha=\frac{adyacente}{hipotenusa}
}
$$

$$
\boxed{
\tan\alpha=\frac{opuesto}{adyacente}
}
$$

### Identidades

$$
\boxed{\sin^2\alpha+\cos^2\alpha=1}
$$

$$
\boxed{\tan\alpha=\frac{\sin\alpha}{\cos\alpha}}
$$

### Componentes

$$
\boxed{A_x=A\cos\alpha}
$$

$$
\boxed{A_y=A\sin\alpha}
$$

### Recuperar módulo y ángulo

$$
\boxed{A=\sqrt{A_x^2+A_y^2}}
$$

$$
\boxed{\alpha=\arctan\left(\frac{A_y}{A_x}\right)}
$$

### Radianes

$$
\boxed{180^\circ=\pi\ rad}
$$

### La pregunta que evita muchos errores

> **¿Respecto a qué eje está medido el ángulo?**
