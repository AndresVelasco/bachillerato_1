# Vectores — Física · 1.º Bachillerato

## 1. Escalares y vectores

### Magnitud escalar

Queda determinada por **un número y una unidad**.

Ejemplos:

$$
m=5\ kg
$$

$$
t=10\ s
$$

Masa, tiempo, temperatura y energía son magnitudes escalares.

### Magnitud vectorial

Además del valor necesita:

- **módulo**
- **dirección**
- **sentido**

Desplazamiento, velocidad, aceleración y fuerza son magnitudes vectoriales.

---

# 2. Componentes de un vector

En dos dimensiones:

$$
\boxed{\vec a=a_x\vec i+a_y\vec j}
$$

También podemos escribir:

$$
\boxed{\vec a=(a_x,a_y)}
$$

Por ejemplo:

$$
\vec a=3\vec i+5\vec j
$$

equivale a:

$$
\vec a=(3,5)
$$

---

## En tres dimensiones

Añadimos la componente $z$:

$$
\boxed{\vec a=a_x\vec i+a_y\vec j+a_z\vec k}
$$

o:

$$
\boxed{\vec a=(a_x,a_y,a_z)}
$$

Por ejemplo:

$$
\vec a=3\vec i+5\vec j+\vec k
$$

significa:

$$
\boxed{\vec a=(3,5,1)}
$$

Recuerda:

$$
\vec i=(1,0,0)
$$

$$
\vec j=(0,1,0)
$$

$$
\vec k=(0,0,1)
$$

Son los **vectores unitarios** de los ejes $x$, $y$ y $z$.

---

# 3. Módulo de un vector

El módulo representa la **longitud** del vector.

## En 2D

Si:

$$
\vec a=(a_x,a_y)
$$

entonces:

$$
\boxed{
|\vec a|=\sqrt{a_x^2+a_y^2}
}
$$

### Ejemplo

$$
\vec a=(3,4)
$$

$$
|\vec a|
=
\sqrt{3^2+4^2}
=5
$$

---

## En 3D

Si:

$$
\vec a=(a_x,a_y,a_z)
$$

entonces:

$$
\boxed{
|\vec a|=
\sqrt{a_x^2+a_y^2+a_z^2}
}
$$

### Ejemplo

$$
\vec a=2\vec i+3\vec j+6\vec k
$$

$$
|\vec a|
=
\sqrt{2^2+3^2+6^2}
$$

$$
=\sqrt{49}
$$

$$
\boxed{|\vec a|=7}
$$

---

# 4. Vector unitario

Un vector unitario tiene módulo $1$.

Podemos obtener el vector unitario en la dirección de $\vec a$ dividiendo el vector por su módulo:

$$
\boxed{
\hat a=\frac{\vec a}{|\vec a|}
}
$$

### Ejemplo

Si:

$$
\vec a=(3,4)
$$

y:

$$
|\vec a|=5
$$

entonces:

$$
\hat a=
\left(\frac35,\frac45\right)
$$

y:

$$
|\hat a|=1
$$

---

# 5. Vector opuesto

El vector opuesto tiene:

- mismo módulo
- misma dirección
- sentido contrario

Si:

$$
\vec a=(a_x,a_y,a_z)
$$

entonces:

$$
\boxed{
-\vec a=(-a_x,-a_y,-a_z)
}
$$

y:

$$
\vec a+(-\vec a)=\vec 0
$$

---

# 6. Suma de vectores

Se suman las componentes correspondientes.

Si:

$$
\vec a=(a_x,a_y,a_z)
$$

$$
\vec b=(b_x,b_y,b_z)
$$

entonces:

$$
\boxed{
\vec a+\vec b=
(a_x+b_x,\,
a_y+b_y,\,
a_z+b_z)
}
$$

### Ejemplo

$$
\vec a=(3,5,1)
$$

$$
\vec b=(2,-1,4)
$$

entonces:

$$
\vec a+\vec b
=
(3+2,5-1,1+4)
$$

$$
\boxed{\vec a+\vec b=(5,4,5)}
$$

---

# 7. Resta de vectores

Restamos componente a componente:

$$
\boxed{
\vec a-\vec b=
(a_x-b_x,\,
a_y-b_y,\,
a_z-b_z)
}
$$

También podemos pensar:

$$
\boxed{
\vec a-\vec b=\vec a+(-\vec b)
}
$$

---

# 8. Multiplicación por un número

Si multiplicamos un vector por un escalar $k$:

$$
\boxed{
k\vec a=
(ka_x,ka_y,ka_z)
}
$$

Ejemplo:

$$
\vec a=(2,-1,3)
$$

$$
2\vec a=(4,-2,6)
$$

### Efecto sobre el vector

Si $k>0$ → mismo sentido.

Si $k<0$ → sentido contrario.

Además:

$$
\boxed{|k\vec a|=|k|\,|\vec a|}
$$

---

# 9. Producto escalar

El producto escalar de dos vectores da como resultado **un número**, no un vector.

Por componentes:

$$
\boxed{
\vec a\cdot\vec b=
a_xb_x+a_yb_y+a_zb_z
}
$$

En 2D simplemente desaparece el término $z$:

$$
\vec a\cdot\vec b=
a_xb_x+a_yb_y
$$

### Ejemplo

$$
\vec a=(3,5,1)
$$

$$
\vec b=(2,-1,4)
$$

entonces:

$$
\vec a\cdot\vec b
=
3(2)+5(-1)+1(4)
$$

$$
=6-5+4
$$

$$
\boxed{\vec a\cdot\vec b=5}
$$

---

## Producto escalar y ángulo

También:

$$
\boxed{
\vec a\cdot\vec b=
|\vec a||\vec b|\cos\alpha
}
$$

Por tanto podemos calcular el ángulo entre dos vectores:

$$
\boxed{
\cos\alpha=
\frac{\vec a\cdot\vec b}
{|\vec a||\vec b|}
}
$$

$$
\boxed{
\alpha=
\arccos
\left(
\frac{\vec a\cdot\vec b}
{|\vec a||\vec b|}
\right)
}
$$

---

## Vectores perpendiculares

Si:

$$
\alpha=90^\circ
$$

entonces:

$$
\cos90^\circ=0
$$

por tanto:

$$
\boxed{
\vec a\cdot\vec b=0
}
$$

Esta es una forma muy útil de comprobar si dos vectores son perpendiculares.

---

# 10. Producto vectorial

⚠️ El producto vectorial habitual de Bachillerato se utiliza con **vectores de tres dimensiones**.

$$
\vec a\times\vec b
$$

El resultado es **otro vector**.

Si:

$$
\vec a=(a_x,a_y,a_z)
$$

$$
\vec b=(b_x,b_y,b_z)
$$

entonces:

$$
\boxed{
\vec a\times\vec b=
\begin{vmatrix}
\vec i & \vec j & \vec k\\
a_x&a_y&a_z\\
b_x&b_y&b_z
\end{vmatrix}
}
$$

Desarrollando:

$$
\boxed{
\vec a\times\vec b=
(a_yb_z-a_zb_y)\vec i
-
(a_xb_z-a_zb_x)\vec j
+
(a_xb_y-a_yb_x)\vec k
}
$$

---

## Módulo del producto vectorial

$$
\boxed{
|\vec a\times\vec b|
=
|\vec a||\vec b|\sin\alpha
}
$$

El vector resultante es perpendicular tanto a $\vec a$ como a $\vec b$.

---

## Casos importantes

### Vectores paralelos

$$
\alpha=0^\circ
$$

por tanto:

$$
\boxed{\vec a\times\vec b=\vec 0}
$$

### Vectores perpendiculares

$$
\alpha=90^\circ
$$

por tanto:

$$
\boxed{
|\vec a\times\vec b|
=
|\vec a||\vec b|
}
$$

---

# 11. Producto escalar vs. producto vectorial

| | Producto escalar | Producto vectorial |
|---|---|---|
| Operación | $\vec a\cdot\vec b$ | $\vec a\times\vec b$ |
| Resultado | Número | Vector |
| Usa | $\cos\alpha$ | $\sin\alpha$ |
| Fórmula módulo | $ab\cos\alpha$ | $ab\sin\alpha$ |
| Si son perpendiculares | $0$ | Máximo |
| Si son paralelos | Máximo | $0$ |

Regla para recordar:

$$
\boxed{\text{escalar → coseno}}
$$

$$
\boxed{\text{vectorial → seno}}
$$

---

# 12. Vectores paralelos

Dos vectores son paralelos si uno es múltiplo del otro:

$$
\boxed{
\vec a=k\vec b
}
$$

Ejemplo:

$$
\vec a=(2,4,6)
$$

$$
\vec b=(1,2,3)
$$

Como:

$$
\vec a=2\vec b
$$

son paralelos.

Si $k>0$, tienen el mismo sentido.

Si $k<0$, tienen sentidos contrarios.

---

# 13. Vectores perpendiculares

Dos vectores son perpendiculares si:

$$
\boxed{
\vec a\cdot\vec b=0
}
$$

Ejemplo:

$$
\vec a=(2,1)
$$

$$
\vec b=(1,-2)
$$

Entonces:

$$
\vec a\cdot\vec b
=
2(1)+1(-2)
=0
$$

Por tanto:

$$
\boxed{\vec a\perp\vec b}
$$

---

# 14. De módulo y ángulo a componentes

Para un vector en el plano que forma un ángulo $\alpha$ con el eje $x$:

$$
\boxed{
a_x=|\vec a|\cos\alpha
}
$$

$$
\boxed{
a_y=|\vec a|\sin\alpha
}
$$

Por tanto:

$$
\boxed{
\vec a=
|\vec a|\cos\alpha\,\vec i+
|\vec a|\sin\alpha\,\vec j
}
$$

⚠️ Si el ángulo está medido respecto a otro eje, hay que identificar cuál es la componente adyacente y cuál la opuesta.

---

# MAPA RÁPIDO

## Forma vectorial ↔ componentes

$$
\boxed{
3\vec i+5\vec j+\vec k
\quad\Longleftrightarrow\quad
(3,5,1)
}
$$

## Módulo

2D:

$$
\boxed{
|\vec a|=\sqrt{a_x^2+a_y^2}
}
$$

3D:

$$
\boxed{
|\vec a|=\sqrt{a_x^2+a_y^2+a_z^2}
}
$$

## Suma

$$
\boxed{
(a_x,a_y,a_z)+(b_x,b_y,b_z)
=
(a_x+b_x,a_y+b_y,a_z+b_z)
}
$$

## Producto escalar

$$
\boxed{
\vec a\cdot\vec b
=
a_xb_x+a_yb_y+a_zb_z
}
$$

$$
\boxed{
\vec a\cdot\vec b=ab\cos\alpha
}
$$

**Resultado → número**

## Producto vectorial

$$
\boxed{
|\vec a\times\vec b|
=
ab\sin\alpha
}
$$

**Resultado → vector perpendicular**

---

# Antes de resolver un ejercicio

Pregúntate:

1. **¿Estoy en 2D o en 3D?**
2. **¿Me dan componentes o módulo y ángulo?**
3. **¿Busco un número o un vector?**
4. Si aparece $\vec a\cdot\vec b$ → **producto escalar**.
5. Si aparece $\vec a\times\vec b$ → **producto vectorial**.
6. Si necesito combinar fuerzas, velocidades, etc. → normalmente **trabajo con sus componentes**.
