# Cheatsheet — Ecuaciones exponenciales y logarítmicas

La idea es **reconocer rápidamente el tipo de ecuación** y saber qué transformación aplicar.

---

# 1. Propiedades de las potencias

## Misma base: multiplicación

$$
a^m\cdot a^n=a^{m+n}
$$

Ejemplo:

$$
2^3\cdot2^4=2^7
$$

## Misma base: división

$$
\frac{a^m}{a^n}=a^{m-n}
$$

Ejemplo:

$$
\frac{3^5}{3^2}=3^3
$$

## Potencia de una potencia

$$
(a^m)^n=a^{mn}
$$

Ejemplo:

$$
(2^3)^4=2^{12}
$$

## Potencia de un producto

$$
(ab)^n=a^nb^n
$$

## Exponente negativo

$$
a^{-n}=\frac{1}{a^n}
$$

## Exponente cero

$$
a^0=1
$$

## Exponente fraccionario

$$
a^{1/n}=\sqrt[n]{a}
$$

y:

$$
a^{m/n}=\sqrt[n]{a^m}
$$

---

# 2. Propiedades de los logaritmos

## Definición fundamental

$$
\boxed{\log_a b=c \iff a^c=b}
$$

Por ejemplo:

$$
\log_2 8=3
$$

porque:

$$
2^3=8
$$

---

## Logaritmo de un producto

$$
\boxed{\log_a(AB)=\log_a A+\log_a B}
$$

Por tanto, también podemos utilizarlo al revés:

$$
\log_a A+\log_a B=\log_a(AB)
$$

---

## Logaritmo de un cociente

$$
\boxed{\log_a\left(\frac{A}{B}\right)=\log_a A-\log_a B}
$$

Y al revés:

$$
\log_a A-\log_a B=\log_a\left(\frac{A}{B}\right)
$$

---

## Logaritmo de una potencia

$$
\boxed{\log_a(A^n)=n\log_a A}
$$

También podemos utilizarlo al revés:

$$
n\log_a A=\log_a(A^n)
$$

---

## Logaritmo de la propia base

$$
\log_a a=1
$$

porque:

$$
a^1=a
$$

## Logaritmo de 1

$$
\log_a1=0
$$

porque:

$$
a^0=1
$$

---

## Cambio de base

$$
\boxed{\log_a b=\frac{\log b}{\log a}}
$$

También:

$$
\log_a b=\frac{\ln b}{\ln a}
$$

Esto permite calcular con la calculadora logaritmos de cualquier base.

---

## Condición fundamental: el argumento debe ser positivo

$$
\boxed{\log_a(f(x))\Rightarrow f(x)>0}
$$

Por ejemplo:

$$
\log(x-2)
$$

solo existe cuando:

$$
x-2>0
$$

es decir:

$$
x>2
$$

---

# 3. Ecuaciones exponenciales

Una ecuación exponencial tiene la incógnita en el exponente.

Por ejemplo:

$$
2^{x+1}=8
$$

## Caso 1 — Conseguir la misma base

**Este es el primer intento.**

Si:

$$
a^{f(x)}=a^{g(x)}
$$

entonces:

$$
\boxed{f(x)=g(x)}
$$

### Ejemplo

$$
2^{x+1}=8^{x-1}
$$

Como:

$$
8=2^3
$$

tenemos:

$$
2^{x+1}=2^{3(x-1)}
$$

Igualamos exponentes:

$$
x+1=3(x-1)
$$

$$
x+1=3x-3
$$

$$
4=2x
$$

$$
\boxed{x=2}
$$

**Consejo:** intenta expresar los números como potencias de $2$, $3$, $5$, $10$, etc.

---

## Caso 2 — No podemos conseguir la misma base

Si tenemos:

$$
a^{f(x)}=b
$$

y no podemos expresar $b$ como una potencia sencilla de $a$, aplicamos logaritmos.

### Ejemplo

$$
3^{2x-1}=7
$$

Aplicamos logaritmos:

$$
\ln(3^{2x-1})=\ln7
$$

Utilizamos:

$$
\ln(a^k)=k\ln a
$$

Entonces:

$$
(2x-1)\ln3=\ln7
$$

$$
2x-1=\frac{\ln7}{\ln3}
$$

$$
\boxed{x=\frac{1+\frac{\ln7}{\ln3}}{2}}
$$

**Patrón:** si la $x$ está en un exponente y no puedes igualar las bases, aplica logaritmos.

---

## Caso 3 — Varias potencias relacionadas

Si aparecen $a^{2x}$ y $a^x$, piensa en una sustitución.

### Ejemplo

$$
2^{2x}-5\cdot2^x+4=0
$$

Como:

$$
2^{2x}=(2^x)^2
$$

hacemos:

$$
t=2^x
$$

Entonces:

$$
t^2-5t+4=0
$$

Factorizamos:

$$
(t-1)(t-4)=0
$$

Por tanto:

$$
t=1
$$

o:

$$
t=4
$$

Volvemos a la variable original:

$$
2^x=1\Rightarrow x=0
$$

$$
2^x=4\Rightarrow x=2
$$

Por tanto:

$$
\boxed{x=0,\;x=2}
$$

**Patrón:** si aparecen $a^{2x}$ y $a^x$, prueba $t=a^x$.

---

# 4. Ecuaciones logarítmicas

Una ecuación logarítmica tiene la incógnita dentro de uno o varios logaritmos.

## Paso 0 — Dominio

**Antes de operar**, los argumentos de todos los logaritmos deben ser positivos.

Si aparece:

$$
\log(f(x))
$$

debemos exigir:

$$
f(x)>0
$$

Una solución que no cumpla el dominio debe descartarse.

---

## Caso 1 — Logaritmo igual a un número

Usamos:

$$
\log_a b=c\iff a^c=b
$$

### Ejemplo

$$
\log_2(x-1)=3
$$

Pasamos a forma exponencial:

$$
x-1=2^3
$$

$$
x-1=8
$$

$$
\boxed{x=9}
$$

---

## Caso 2 — Logaritmo igual a logaritmo

Si:

$$
\log_a(f(x))=\log_a(g(x))
$$

entonces:

$$
\boxed{f(x)=g(x)}
$$

### Ejemplo

$$
\log(x+3)=\log(2x-1)
$$

Igualamos argumentos:

$$
x+3=2x-1
$$

$$
x=4
$$

Comprobamos que los argumentos son positivos y obtenemos:

$$
\boxed{x=4}
$$

---

## Caso 3 — Suma de logaritmos

Usamos:

$$
\log A+\log B=\log(AB)
$$

### Ejemplo

$$
\log(x)+\log(x-3)=1
$$

Primero, dominio:

$$
x>0
$$

$$
x-3>0
$$

Por tanto:

$$
x>3
$$

Agrupamos:

$$
\log(x(x-3))=1
$$

Si $\log$ es decimal:

$$
x(x-3)=10
$$

$$
x^2-3x-10=0
$$

$$
(x-5)(x+2)=0
$$

$$
x=5,\;-2
$$

Pero necesitamos $x>3$, así que:

$$
\boxed{x=5}
$$

---

## Caso 4 — Resta de logaritmos

Usamos:

$$
\log A-\log B=\log\left(\frac{A}{B}\right)
$$

### Ejemplo

$$
\log(x+1)-\log(x)=\log2
$$

Agrupamos:

$$
\log\left(\frac{x+1}{x}\right)=\log2
$$

Igualamos argumentos:

$$
\frac{x+1}{x}=2
$$

$$
x+1=2x
$$

$$
\boxed{x=1}
$$

---

## Caso 5 — Número delante de un logaritmo

Usamos:

$$
k\log A=\log(A^k)
$$

### Ejemplo

$$
2\log x=\log16
$$

Entonces:

$$
\log(x^2)=\log16
$$

Igualamos argumentos:

$$
x^2=16
$$

$$
x=\pm4
$$

Pero el logaritmo original exige:

$$
x>0
$$

Por tanto:

$$
\boxed{x=4}
$$

---

# 5. Árbol de decisión

## Si la incógnita está en el exponente

Es una ecuación **exponencial**.

**¿Puedes conseguir la misma base?**

Sí:

$$
a^{f(x)}=a^{g(x)}
$$

Entonces:

$$
f(x)=g(x)
$$

**¿No puedes conseguir la misma base?**

Aplica logaritmos.

**¿Aparecen $a^{2x}$ y $a^x$?**

Prueba la sustitución:

$$
t=a^x
$$

---

## Si la incógnita está dentro de un logaritmo

Es una ecuación **logarítmica**.

1. Calcula el **dominio**.
2. Intenta agrupar los logaritmos.
3. Si tienes $\log_a(f(x))=\log_a(g(x))$, iguala argumentos.
4. Si tienes $\log_a(f(x))=c$, pasa a forma exponencial.
5. Resuelve.
6. Comprueba las soluciones con el dominio original.

---

# 6. Resumen ultrarrápido

| Si ves... | Haz... |
|---|---|
| $a^m\cdot a^n$ | $a^{m+n}$ |
| $\frac{a^m}{a^n}$ | $a^{m-n}$ |
| $(a^m)^n$ | $a^{mn}$ |
| $2^{f(x)}=2^{g(x)}$ | Iguala exponentes |
| $3^{f(x)}=7$ | Aplica logaritmos |
| $2^{2x}$ y $2^x$ | Sustituye $t=2^x$ |
| $\log_a(f(x))=c$ | Pasa a forma exponencial |
| $\log(f(x))=\log(g(x))$ | Iguala argumentos |
| $\log A+\log B$ | $\log(AB)$ |
| $\log A-\log B$ | $\log(A/B)$ |
| $k\log A$ | $\log(A^k)$ |
| Cualquier $\log(f(x))$ | Exige $f(x)>0$ |

---

# Regla práctica final

Para **exponenciales**:

> **Misma base → igualar exponentes → si no es posible, logaritmos.**

Para **logarítmicas**:

> **Dominio → agrupar logaritmos → eliminar logaritmos → resolver → comprobar dominio.**
