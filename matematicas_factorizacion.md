# Factorización de polinomios — Cheatsheet

## 1. Factor común

**Comprobar siempre primero.**

$$
ab+ac=a(b+c)
$$

Ejemplos:

$$
6x^3+9x^2=3x^2(2x+3)
$$

$$
x^3-4x^2+3x=x(x^2-4x+3)
$$

---

## 2. Diferencia de cuadrados

### Fórmula

$$
a^2-b^2=(a-b)(a+b)
$$

Ejemplos:

$$
x^2-9=(x-3)(x+3)
$$

$$
4x^2-25=(2x-5)(2x+5)
$$

⚠️ Solo funciona con una **resta** de cuadrados.

---

## 3. Trinomio cuadrado perfecto

### Suma

$$
a^2+2ab+b^2=(a+b)^2
$$

Ejemplo:

$$
x^2+6x+9=(x+3)^2
$$

### Resta

$$
a^2-2ab+b^2=(a-b)^2
$$

Ejemplo:

$$
x^2-10x+25=(x-5)^2
$$

---

## 4. Trinomio $x^2+bx+c$

Buscar dos números $r$ y $s$ que cumplan:

$$
r+s=b
$$

$$
r\cdot s=c
$$

Entonces:

$$
x^2+bx+c=(x+r)(x+s)
$$

### Ejemplo

$$
x^2+5x+6
$$

Buscamos dos números que sumen $5$ y multipliquen $6$:

$$
2+3=5
$$

$$
2\cdot3=6
$$

Por tanto:

$$
\boxed{x^2+5x+6=(x+2)(x+3)}
$$

### Ejemplo con negativos

$$
x^2-5x+6
$$

$$
(-2)+(-3)=-5
$$

$$
(-2)(-3)=6
$$

Por tanto:

$$
\boxed{x^2-5x+6=(x-2)(x-3)}
$$

---

## 5. Mediante las raíces

Para un polinomio:

$$
ax^2+bx+c
$$

calculamos sus raíces con:

$$
\boxed{x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}}
$$

Si las raíces son $x_1$ y $x_2$:

$$
\boxed{ax^2+bx+c=a(x-x_1)(x-x_2)}
$$

### Ejemplo

$$
2x^2-10x+12
$$

Sus raíces son:

$$
x_1=2,\qquad x_2=3
$$

Por tanto:

$$
\boxed{2x^2-10x+12=2(x-2)(x-3)}
$$

### Regla fundamental

Si:

$$
P(r)=0
$$

entonces:

$$
\boxed{(x-r)\text{ es un factor de }P(x)}
$$

---

## 6. Ruffini

Útil principalmente para polinomios de grado $3$ o superior.

### Procedimiento

1. Buscar una posible raíz $r$.
2. Comprobar que $P(r)=0$.
3. Dividir mediante Ruffini entre $(x-r)$.
4. Factorizar el polinomio resultante.

### Posibles raíces enteras

Si el coeficiente principal es $1$, probar los divisores del término independiente:

$$
\pm1,\pm2,\pm3,\ldots
$$

### Ejemplo

$$
P(x)=x^3-6x^2+11x-6
$$

Probamos $x=1$:

$$
P(1)=1-6+11-6=0
$$

Por tanto:

$$
(x-1)
$$

es un factor.

Ruffini da:

$$
P(x)=(x-1)(x^2-5x+6)
$$

Factorizamos el segundo término:

$$
x^2-5x+6=(x-2)(x-3)
$$

Resultado:

$$
\boxed{P(x)=(x-1)(x-2)(x-3)}
$$

---

## 7. Factorización por agrupación

Agrupar términos para obtener factores comunes.

Ejemplo:

$$
x^3+2x^2+3x+6
$$

Agrupamos:

$$
(x^3+2x^2)+(3x+6)
$$

Sacamos factor común:

$$
x^2(x+2)+3(x+2)
$$

Volvemos a sacar factor común:

$$
\boxed{(x+2)(x^2+3)}
$$

---

# Identidades notables

### Diferencia de cuadrados

$$
\boxed{a^2-b^2=(a-b)(a+b)}
$$

### Cuadrado de una suma

$$
\boxed{a^2+2ab+b^2=(a+b)^2}
$$

### Cuadrado de una diferencia

$$
\boxed{a^2-2ab+b^2=(a-b)^2}
$$

### Suma de cubos

$$
\boxed{a^3+b^3=(a+b)(a^2-ab+b^2)}
$$

### Diferencia de cubos

$$
\boxed{a^3-b^3=(a-b)(a^2+ab+b^2)}
$$

---

# ¿Qué método uso?

| Si veo... | Intento... |
|---|---|
| Todos los términos tienen algo en común | **Factor común** |
| $a^2-b^2$ | **Diferencia de cuadrados** |
| $a^2\pm2ab+b^2$ | **Cuadrado perfecto** |
| $x^2+bx+c$ | **Buscar dos números** |
| $ax^2+bx+c$ | **Calcular las raíces** |
| Polinomio de grado $\geq3$ | **Ruffini** |
| Varios términos que se pueden agrupar | **Agrupación** |

---

# Algoritmo rápido

Ante un polinomio:

### ① ¿Hay factor común?

**Sí → sacarlo primero.**

### ② ¿Reconozco una identidad notable?

$$
a^2-b^2
$$

$$
a^2\pm2ab+b^2
$$

### ③ ¿Es de segundo grado?

$$
ax^2+bx+c
$$

Buscar las raíces y usar:

$$
a(x-x_1)(x-x_2)
$$

### ④ ¿Es de grado 3 o superior?

Buscar una raíz y aplicar **Ruffini**.

### ⑤ Volver a mirar

Después de factorizar una vez, comprobar si alguno de los factores **se puede seguir factorizando**.

---

# Idea clave

**Factorizar** significa transformar una suma o resta en un producto:

$$
x^2-5x+6
$$

se convierte en:

$$
\boxed{(x-2)(x-3)}
$$

Esto permite ver inmediatamente las raíces:

$$
x=2,\qquad x=3
$$

Por eso la factorización es especialmente importante para resolver **ecuaciones e inecuaciones**.
