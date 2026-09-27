# Inecuaciones — Cheatsheet

## 1. ¿Qué es una inecuación?

Una **ecuación** busca valores que hacen que dos expresiones sean iguales:

$$
2x+3=9
$$

$$
x=3
$$

Una **inecuación** busca todos los valores que hacen que una expresión sea mayor o menor que otra:

$$
2x+3<9
$$

$$
x<3
$$

La solución normalmente es un **intervalo de números**, no un único número.

---

# 2. Signos de desigualdad

| Signo | Significado |
|---|---|
| $<$ | menor que |
| $>$ | mayor que |
| $\leq$ | menor o igual que |
| $\geq$ | mayor o igual que |

Ejemplos:

$$
x<3
$$

significa todos los números menores que $3$.

$$
x\geq3
$$

significa $3$ y todos los números mayores que $3$.

---

# 3. Intervalos

Las soluciones suelen expresarse mediante **intervalos**.

### Menor que

$$
x<3
$$

$$
\boxed{(-\infty,3)}
$$

### Menor o igual

$$
x\leq3
$$

$$
\boxed{(-\infty,3]}
$$

### Mayor que

$$
x>3
$$

$$
\boxed{(3,+\infty)}
$$

### Mayor o igual

$$
x\geq3
$$

$$
\boxed{[3,+\infty)}
$$

### Entre dos valores

$$
2<x\leq5
$$

$$
\boxed{(2,5]}
$$

## Paréntesis y corchetes

El **paréntesis** indica que el extremo NO está incluido:

$$
(2,5)
$$

El **corchete** indica que el extremo SÍ está incluido:

$$
[2,5]
$$

Con $\pm\infty$ siempre se utiliza paréntesis:

$$
(-\infty,3]
$$

$$
[2,+\infty)
$$

---

# 4. Inecuaciones de primer grado

Se resuelven casi igual que las ecuaciones.

Ejemplo:

$$
3x+5<17
$$

Restamos $5$:

$$
3x<12
$$

Dividimos entre $3$:

$$
\boxed{x<4}
$$

Solución:

$$
\boxed{(-\infty,4)}
$$

---

## Ejemplo con $x$ en ambos lados

$$
5x-7\geq2x+8
$$

Agrupamos:

$$
5x-2x\geq8+7
$$

$$
3x\geq15
$$

$$
\boxed{x\geq5}
$$

Solución:

$$
\boxed{[5,+\infty)}
$$

---

# 5. Regla fundamental: números negativos

⚠️ **Si multiplicamos o dividimos una inecuación por un número negativo, hay que invertir el signo.**

$$
<\quad\longleftrightarrow\quad>
$$

$$
\leq\quad\longleftrightarrow\quad\geq
$$

Ejemplo:

$$
-2x<6
$$

Dividimos entre $-2$:

$$
\boxed{x>-3}
$$

¿Por qué?

Porque:

$$
2<5
$$

pero al multiplicar por $-1$:

$$
-2>-5
$$

---

# 6. Sistemas de inecuaciones

En un sistema, **todas las inecuaciones deben cumplirse simultáneamente**.

Por tanto:

$$
\boxed{\text{Sistema}=\text{intersección de soluciones}}
$$

Ejemplo:

$$
\begin{cases}
x>2\\
x\leq7
\end{cases}
$$

Primera solución:

$$
(2,+\infty)
$$

Segunda solución:

$$
(-\infty,7]
$$

Buscamos la zona común:

$$
(2,+\infty)\cap(-\infty,7]
$$

Resultado:

$$
\boxed{(2,7]}
$$

---

## Resolver primero, intersectar después

Ejemplo:

$$
\begin{cases}
2x-1>3\\
3x+2\leq17
\end{cases}
$$

Primera:

$$
2x>4
$$

$$
x>2
$$

Segunda:

$$
3x\leq15
$$

$$
x\leq5
$$

Por tanto:

$$
\boxed{2<x\leq5}
$$

o:

$$
\boxed{(2,5]}
$$

---

## Sistema sin solución

$$
\begin{cases}
x<2\\
x>5
\end{cases}
$$

No existe ningún número que cumpla ambas condiciones:

$$
\boxed{\varnothing}
$$

---

# 7. Unión e intersección

Estas dos operaciones aparecen constantemente.

## Intersección: $\cap$

Significa **Y**.

Deben cumplirse las dos condiciones.

$$
x>2\quad\text{Y}\quad x<5
$$

$$
(2,+\infty)\cap(-\infty,5)
$$

$$
\boxed{(2,5)}
$$

---

## Unión: $\cup$

Significa **O**.

Puede cumplirse una condición o la otra.

$$
x<2\quad\text{O}\quad x>5
$$

$$
\boxed{(-\infty,2)\cup(5,+\infty)}
$$

### Regla mental

$$
\boxed{\cap=\text{Y}}
$$

$$
\boxed{\cup=\text{O}}
$$

---

# 8. Inecuaciones polinómicas

Ejemplo:

$$
x^2-5x+6>0
$$

Primero llevamos todo a un lado y **factorizamos**:

$$
(x-2)(x-3)>0
$$

Los factores se anulan en:

$$
x=2
$$

$$
x=3
$$

Estos valores dividen la recta en tres intervalos:

$$
(-\infty,2)
$$

$$
(2,3)
$$

$$
(3,+\infty)
$$

Ahora estudiamos el signo.

| Intervalo | $x-2$ | $x-3$ | Producto |
|---|---:|---:|---:|
| $x<2$ | $-$ | $-$ | $+$ |
| $2<x<3$ | $+$ | $-$ | $-$ |
| $x>3$ | $+$ | $+$ | $+$ |

Queremos:

$$
(x-2)(x-3)>0
$$

Por tanto elegimos las zonas positivas:

$$
\boxed{(-\infty,2)\cup(3,+\infty)}
$$

---

# 9. Tabla de signos

La idea fundamental es:

1. Factorizar.
2. Encontrar dónde cada factor vale $0$.
3. Colocar esos puntos ordenados en la recta.
4. Estudiar el signo de cada factor.
5. Obtener el signo del producto.
6. Elegir los intervalos que pide la inecuación.

Ejemplo:

$$
(x+1)(x-2)(x-4)<0
$$

Puntos críticos:

$$
x=-1,\quad x=2,\quad x=4
$$

Intervalos:

$$
(-\infty,-1),\quad(-1,2),\quad(2,4),\quad(4,+\infty)
$$

Estudiamos los signos:

| Intervalo | $x+1$ | $x-2$ | $x-4$ | Producto |
|---|---:|---:|---:|---:|
| $x<-1$ | $-$ | $-$ | $-$ | $-$ |
| $-1<x<2$ | $+$ | $-$ | $-$ | $+$ |
| $2<x<4$ | $+$ | $+$ | $-$ | $-$ |
| $x>4$ | $+$ | $+$ | $+$ | $+$ |

Como queremos $<0$:

$$
\boxed{(-\infty,-1)\cup(2,4)}
$$

---

# 10. $>$ frente a $\geq$

Consideremos:

$$
(x-2)(x-3)>0
$$

Los valores $2$ y $3$ hacen que la expresión valga $0$.

Como queremos **mayor que cero**, no se incluyen:

$$
\boxed{(-\infty,2)\cup(3,+\infty)}
$$

Pero si tenemos:

$$
(x-2)(x-3)\geq0
$$

también aceptamos el cero.

Por tanto:

$$
\boxed{(-\infty,2]\cup[3,+\infty)}
$$

### Regla

Con:

$$
>,\quad<
$$

normalmente los ceros **no se incluyen**.

Con:

$$
\geq,\quad\leq
$$

los ceros **sí pueden incluirse**.

---

# 11. Inecuaciones de segundo grado

Una inecuación como:

$$
x^2-5x+6<0
$$

puede resolverse factorizando:

$$
(x-2)(x-3)<0
$$

Ya sabemos que el producto tiene signo:

$$
+\qquad-\qquad+
$$

en los intervalos:

$$
(-\infty,2),\quad(2,3),\quad(3,+\infty)
$$

Queremos la zona negativa:

$$
\boxed{(2,3)}
$$

---

## Interpretación gráfica

Si:

$$
f(x)=x^2-5x+6
$$

resolver:

$$
f(x)>0
$$

significa:

**¿Dónde está la gráfica por encima del eje $x$?**

Y resolver:

$$
f(x)<0
$$

significa:

**¿Dónde está por debajo del eje $x$?**

Las raíces:

$$
x=2,\qquad x=3
$$

son precisamente los puntos donde la gráfica cruza el eje $x$.

---

# 12. Inecuaciones racionales

Ejemplo:

$$
\frac{x-2}{x+1}>0
$$

Buscamos los puntos donde el signo puede cambiar.

### Numerador igual a cero

$$
x-2=0
$$

$$
x=2
$$

### Denominador igual a cero

$$
x+1=0
$$

$$
x=-1
$$

Estos puntos dividen la recta:

$$
(-\infty,-1),\quad(-1,2),\quad(2,+\infty)
$$

Tabla:

| Intervalo | $x-2$ | $x+1$ | Cociente |
|---|---:|---:|---:|
| $x<-1$ | $-$ | $-$ | $+$ |
| $-1<x<2$ | $-$ | $+$ | $-$ |
| $x>2$ | $+$ | $+$ | $+$ |

Queremos:

$$
\frac{x-2}{x+1}>0
$$

Resultado:

$$
\boxed{(-\infty,-1)\cup(2,+\infty)}
$$

---

# 13. Cuidado con el denominador

Un denominador **nunca puede valer cero**.

Por ejemplo:

$$
\frac{x-2}{x+1}\geq0
$$

El numerador vale cero en:

$$
x=2
$$

y puede incluirse porque tenemos $\geq$.

Pero:

$$
x=-1
$$

anula el denominador.

Por tanto, **jamás puede incluirse**.

Resultado:

$$
\boxed{(-\infty,-1)\cup[2,+\infty)}
$$

### Regla fundamental

$$
\boxed{\text{Cero del numerador: puede incluirse}}
$$

$$
\boxed{\text{Cero del denominador: nunca se incluye}}
$$

---

# 14. No multiplicar alegremente por expresiones con $x$

Ante:

$$
\frac{x-2}{x+1}>0
$$

NO conviene multiplicar directamente por:

$$
x+1
$$

porque no sabemos si $x+1$ es positivo o negativo.

Si fuera negativo, tendríamos que invertir el signo de la desigualdad.

Por eso en las inecuaciones racionales es más seguro utilizar una **tabla de signos**.

---

# 15. Método general para inecuaciones polinómicas y racionales

Intentar obtener:

$$
f(x)>0
$$

$$
f(x)<0
$$

$$
f(x)\geq0
$$

o:

$$
f(x)\leq0
$$

Después:

### ① Llevar todo a un lado

$$
f(x)>0
$$

### ② Factorizar

Usar los métodos del cheatsheet de **factorización**.

### ③ Encontrar los puntos críticos

- Ceros del numerador.
- Ceros de los factores.
- Ceros del denominador.

### ④ Ordenarlos en la recta

Por ejemplo:

$$
-2\qquad1\qquad5
$$

generan:

$$
(-\infty,-2),\quad(-2,1),\quad(1,5),\quad(5,+\infty)
$$

### ⑤ Construir la tabla de signos

Determinar si la expresión es:

$$
+\quad\text{o}\quad-
$$

en cada intervalo.

### ⑥ Elegir los intervalos correctos

Si pide:

$$
>0
$$

elegimos los positivos.

Si pide:

$$
<0
$$

elegimos los negativos.

### ⑦ Revisar los extremos

- Con $\geq$ o $\leq$, los ceros pueden incluirse.
- Los valores que anulan un denominador nunca se incluyen.

---

# 16. Errores frecuentes

### ❌ No cambiar el signo al dividir por un negativo

Incorrecto:

$$
-2x<6\Rightarrow x<-3
$$

Correcto:

$$
\boxed{-2x<6\Rightarrow x>-3}
$$

---

### ❌ Confundir unión e intersección

$$
\cap=\text{Y}
$$

$$
\cup=\text{O}
$$

---

### ❌ Incluir un cero del denominador

$$
\frac{x-2}{x+1}\geq0
$$

Nunca podemos incluir:

$$
x=-1
$$

---

### ❌ Resolver solo los ceros

En:

$$
(x-2)(x-5)>0
$$

encontrar:

$$
x=2,\qquad x=5
$$

**no es la solución**.

Son los puntos que dividen la recta.

Después hay que estudiar los signos.

---

### ❌ Olvidar el signo $=$

No es lo mismo:

$$
x>2
$$

que:

$$
x\geq2
$$

Sus intervalos son:

$$
(2,+\infty)
$$

y:

$$
[2,+\infty)
$$

---

# 17. Mapa rápido

## ¿Es de primer grado?

$$
3x-2>7
$$

→ **Despejar $x$**

---

## ¿Es un sistema?

$$
\begin{cases}
x>2\\
x\leq5
\end{cases}
$$

→ **Resolver cada una + intersección**

---

## ¿Hay productos de factores?

$$
(x-2)(x+3)\leq0
$$

→ **Tabla de signos**

---

## ¿Es de segundo grado?

$$
x^2-5x+6>0
$$

→ **Factorizar + tabla de signos**

---

## ¿Hay cocientes?

$$
\frac{x-2}{x+1}\geq0
$$

→ **Ceros del numerador + ceros del denominador + tabla de signos**

---

# Resumen esencial

### Inecuación lineal

$$
\boxed{\text{Despejar }x}
$$

Recordar:

$$
\boxed{\text{Dividir/multiplicar por negativo }\Rightarrow\text{ invertir signo}}
$$

### Sistema

$$
\boxed{\text{Resolver cada inecuación + intersectar}}
$$

### Polinómica

$$
\boxed{\text{Factorizar + puntos críticos + tabla de signos}}
$$

### Racional

$$
\boxed{\text{Numerador y denominador + puntos críticos + tabla de signos}}
$$

Y la idea central de todo el tema:

$$
\boxed{\text{Resolver una inecuación = encontrar zonas de la recta real}}
$$
