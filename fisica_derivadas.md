# Derivadas — Física · 1.º Bachillerato

## 1. ¿Qué representa una derivada?

Una derivada mide **cómo cambia una magnitud respecto a otra**.

Si tenemos:

$$
y=f(x)
$$

su derivada se escribe:

$$
\boxed{
f'(x)=\frac{dy}{dx}
}
$$

En Física normalmente una magnitud cambia con el **tiempo**:

$$
\boxed{
\frac{dx}{dt}
}
$$

y representa cuánto cambia $x$ por unidad de tiempo en un instante determinado.

---

# 2. Tasa de variación media e instantánea

Entre dos instantes:

$$
t_1 \qquad t_2
$$

la tasa de variación media es:

$$
\boxed{
\frac{\Delta x}{\Delta t}
=
\frac{x_2-x_1}{t_2-t_1}
}
$$

Esto mide el cambio **durante un intervalo**.

La derivada lleva esta idea al límite cuando el intervalo se hace cada vez más pequeño:

$$
\boxed{
\frac{dx}{dt}
=
\lim_{\Delta t\to0}
\frac{\Delta x}{\Delta t}
}
$$

Por tanto:

> **Derivada = tasa de variación instantánea.**

---

# 3. Interpretación gráfica

Geométricamente, la derivada es la **pendiente de la curva en un punto**.

Entre dos puntos calculamos:

$$
\frac{\Delta y}{\Delta x}
$$

Cuando los dos puntos se acercan:

$$
\boxed{
f'(x)=\text{pendiente de la tangente}
}
$$

### Interpretación del signo

Si:

$$
f'(x)>0
$$

la función está creciendo.

Si:

$$
f'(x)<0
$$

la función está decreciendo.

Si:

$$
f'(x)=0
$$

la tangente es horizontal.

---

# 4. La conexión fundamental en Física

Si conocemos la **posición** de un objeto:

$$
x=x(t)
$$

su derivada respecto al tiempo es la **velocidad**:

$$
\boxed{
v(t)=\frac{dx}{dt}
}
$$

Si derivamos de nuevo:

$$
\boxed{
a(t)=\frac{dv}{dt}
}
$$

Por tanto:

$$
\boxed{
a(t)=\frac{d^2x}{dt^2}
}
$$

El esquema fundamental es:

$$
\boxed{
x(t)
\xrightarrow{\frac{d}{dt}}
v(t)
\xrightarrow{\frac{d}{dt}}
a(t)
}
$$

**Posición → derivar → velocidad → derivar → aceleración**

---

# 5. Ejemplo físico

Supongamos:

$$
x(t)=2t^3-3t^2+5
$$

### Velocidad

Derivamos la posición:

$$
v(t)=x'(t)
$$

$$
v(t)=6t^2-6t
$$

Por tanto:

$$
\boxed{
v(t)=6t^2-6t
}
$$

### Aceleración

Derivamos la velocidad:

$$
a(t)=v'(t)
$$

$$
\boxed{
a(t)=12t-6
}
$$

Así, una sola función $x(t)$ nos permite obtener tanto la velocidad como la aceleración.

---

# 6. Derivadas básicas

## Constante

La derivada de una constante es cero:

$$
\boxed{
(k)'=0
}
$$

Ejemplo:

$$
(5)'=0
$$

¿Por qué?

Porque una constante **no cambia**.

---

## Potencias

La regla fundamental:

$$
\boxed{
(x^n)'=nx^{n-1}
}
$$

Es decir:

1. el exponente baja multiplicando;
2. restamos $1$ al exponente.

### Ejemplos

$$
(x^2)'=2x
$$

$$
(x^3)'=3x^2
$$

$$
(x^7)'=7x^6
$$

---

## Constante por una función

$$
\boxed{
(kf(x))'=kf'(x)
}
$$

Ejemplo:

$$
(4x^7)'=4\cdot7x^6
$$

$$
\boxed{
(4x^7)'=28x^6
}
$$

---

# 7. Raíces como potencias

Conviene convertir una raíz en una potencia:

$$
\sqrt{x}=x^{1/2}
$$

Entonces utilizamos la regla de las potencias:

$$
(\sqrt{x})'
=
(x^{1/2})'
$$

$$
=
\frac12x^{-1/2}
$$

Por tanto:

$$
\boxed{
(\sqrt{x})'=
\frac{1}{2\sqrt{x}}
}
$$

---

## Otras raíces

En general:

$$
\sqrt[n]{x}=x^{1/n}
$$

Por ejemplo:

$$
\sqrt[3]{x}=x^{1/3}
$$

y:

$$
(\sqrt[3]{x})'
=
\frac13x^{-2/3}
$$

---

# 8. Derivadas trigonométricas

Las dos más importantes para este nivel son:

$$
\boxed{
(\sin x)'=\cos x
}
$$

$$
\boxed{
(\cos x)'=-\sin x
}
$$

También:

$$
\boxed{
(\tan x)'=\frac{1}{\cos^2x}
}
$$

o equivalentemente:

$$
(\tan x)'=\sec^2x
$$

⚠️ En cálculo, estas fórmulas trigonométricas se aplican tomando el ángulo en **radianes**.

---

# 9. Suma y resta

La derivada se aplica término a término:

$$
\boxed{
(f(x)\pm g(x))'
=
f'(x)\pm g'(x)
}
$$

### Ejemplo

$$
f(x)=3x^2+2x-5
$$

Derivamos cada término:

$$
f'(x)=6x+2-0
$$

Por tanto:

$$
\boxed{
f'(x)=6x+2
}
$$

---

# 10. Regla del producto

⚠️ La derivada de un producto **no** es simplemente el producto de las derivadas.

Si:

$$
h(x)=f(x)g(x)
$$

entonces:

$$
\boxed{
h'(x)=f'(x)g(x)+f(x)g'(x)
}
$$

Una forma de recordarlo:

$$
\boxed{
(fg)'=f'g+fg'
}
$$

### Ejemplo

$$
h(x)=x^2\sin x
$$

Tenemos:

$$
f(x)=x^2
\qquad
g(x)=\sin x
$$

Por tanto:

$$
f'(x)=2x
$$

$$
g'(x)=\cos x
$$

Aplicamos la regla:

$$
h'(x)
=
2x\sin x+x^2\cos x
$$

$$
\boxed{
h'(x)=2x\sin x+x^2\cos x
}
$$

---

# 11. Regla del cociente

Si:

$$
h(x)=\frac{f(x)}{g(x)}
$$

entonces:

$$
\boxed{
h'(x)
=
\frac{f'(x)g(x)-f(x)g'(x)}
{[g(x)]^2}
}
$$

Una forma de recordarlo:

$$
\boxed{
\left(\frac fg\right)'
=
\frac{f'g-fg'}{g^2}
}
$$

### Ejemplo

$$
h(x)=\frac{x^2}{\cos x}
$$

Entonces:

$$
f(x)=x^2
\qquad
g(x)=\cos x
$$

$$
f'(x)=2x
\qquad
g'(x)=-\sin x
$$

Aplicamos:

$$
h'(x)
=
\frac{2x\cos x-x^2(-\sin x)}
{\cos^2x}
$$

Por tanto:

$$
\boxed{
h'(x)=
\frac{2x\cos x+x^2\sin x}
{\cos^2x}
}
$$

---

# 12. Regla de la cadena

Se utiliza cuando tenemos **una función dentro de otra función**:

$$
f(g(x))
$$

La regla es:

$$
\boxed{
[f(g(x))]'
=
f'(g(x))\cdot g'(x)
}
$$

Una forma práctica de pensar:

> **Deriva la función de fuera y multiplica por la derivada de la función de dentro.**

---

## Ejemplo: coseno

$$
f(x)=\cos(3x^2)
$$

Tenemos una función exterior:

$$
\cos(\square)
$$

y una interior:

$$
3x^2
$$

Derivamos la exterior:

$$
-\sin(3x^2)
$$

Derivamos la interior:

$$
(3x^2)'=6x
$$

Multiplicamos:

$$
\boxed{
f'(x)=-6x\sin(3x^2)
}
$$

---

# 13. Regla de la cadena con raíces

Por ejemplo:

$$
f(x)=\sqrt{x^2+1}
$$

Primero escribimos:

$$
f(x)=(x^2+1)^{1/2}
$$

Función exterior:

$$
(\square)^{1/2}
$$

Función interior:

$$
x^2+1
$$

Aplicamos la cadena:

$$
f'(x)
=
\frac12(x^2+1)^{-1/2}\cdot2x
$$

Simplificando:

$$
\boxed{
f'(x)=
\frac{x}{\sqrt{x^2+1}}
}
$$

---

# 14. Reconocer qué regla utilizar

Antes de derivar, mira la **estructura** de la función.

### Suma

$$
x^3+5x^2-2x
$$

→ deriva término a término.

### Producto

$$
x^2\sin x
$$

→ regla del producto.

### Cociente

$$
\frac{x^2}{\cos x}
$$

→ regla del cociente.

### Función dentro de otra

$$
\sin(3x)
$$

→ regla de la cadena.

### Combinación

$$
x^2\cos(3x)
$$

→ **producto + cadena**.

Las reglas pueden aparecer combinadas.

---

# 15. Ejemplo combinado

Sea:

$$
f(x)=x^2\cos(3x)
$$

Es un producto:

$$
f(x)=
\underbrace{x^2}_{u}
\underbrace{\cos(3x)}_{v}
$$

Aplicamos:

$$
f'=u'v+uv'
$$

Tenemos:

$$
u'=2x
$$

Para $v'$ necesitamos la regla de la cadena:

$$
[\cos(3x)]'
=
-\sin(3x)\cdot3
$$

Por tanto:

$$
f'(x)
=
2x\cos(3x)
-
3x^2\sin(3x)
$$

$$
\boxed{
f'(x)
=
2x\cos(3x)
-
3x^2\sin(3x)
}
$$

---

# 16. Derivadas y unidades

En Física, las unidades ayudan a entender qué representa una derivada.

Si:

$$
x(t)
$$

se mide en metros y $t$ en segundos:

$$
\frac{dx}{dt}
$$

tiene unidades:

$$
\frac{m}{s}
$$

Es decir, velocidad.

Si volvemos a derivar:

$$
\frac{d^2x}{dt^2}
$$

las unidades son:

$$
\frac{m}{s^2}
$$

Es decir, aceleración.

Por tanto:

$$
\boxed{
x\ [m]
\xrightarrow{\frac d{dt}}
v\ [m/s]
\xrightarrow{\frac d{dt}}
a\ [m/s^2]
}
$$

---

# MAPA RÁPIDO

## Derivadas fundamentales

$$
\boxed{(k)'=0}
$$

$$
\boxed{(x^n)'=nx^{n-1}}
$$

$$
\boxed{(\sin x)'=\cos x}
$$

$$
\boxed{(\cos x)'=-\sin x}
$$

$$
\boxed{
(\sqrt{x})'=\frac{1}{2\sqrt{x}}
}
$$

---

## Reglas

### Suma

$$
\boxed{
(f+g)'=f'+g'
}
$$

### Producto

$$
\boxed{
(fg)'=f'g+fg'
}
$$

### Cociente

$$
\boxed{
\left(\frac fg\right)'
=
\frac{f'g-fg'}{g^2}
}
$$

### Cadena

$$
\boxed{
[f(g(x))]'
=
f'(g(x))g'(x)
}
$$

---

# El mapa para Física

$$
\boxed{
\text{posición}
\xrightarrow{\text{derivar}}
\text{velocidad}
\xrightarrow{\text{derivar}}
\text{aceleración}
}
$$

o matemáticamente:

$$
\boxed{
x(t)
\xrightarrow{\frac d{dt}}
v(t)
\xrightarrow{\frac d{dt}}
a(t)
}
$$

con:

$$
\boxed{
v(t)=\frac{dx}{dt}
}
$$

$$
\boxed{
a(t)=\frac{dv}{dt}
=\frac{d^2x}{dt^2}
}
$$

---

# Antes de derivar

1. **Simplifica la expresión si puedes.**
2. Identifica si hay una **suma, producto, cociente o composición**.
3. Si hay una función dentro de otra → piensa en **regla de la cadena**.
4. Deriva paso a paso.
5. Simplifica el resultado al final.
6. Si es un problema de Física → **comprueba las unidades y qué representa la derivada**.
