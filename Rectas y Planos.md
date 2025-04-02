# Rectas
Dados 2 puntos en el espacio, por ellos pasa una recta determinada, para el caso de $\mathbb{R}^2$ esta ecuación es: $y = mx +b$, también puede escribirse de la forma general $ax + by = c$.

Las rectas de cualquier espacio $\mathbb{R}^n$ se definen como:
> Sea P punto de $\mathbb{R}^n$ y sea A un vector no nulo. Definimos la recta que pasa por P y es paralela el vector A como aquel conjunto que satisface que:
> $$ x(t) =P + tA$$
> Donde A nos da la dirección de la recta.

## Ecuaciones Paramétricas de la Recta
Dado un punto $P = (p,q,r)$ que está sobre una recta $L$ y sea $A = (a,b,c)$ el vector dirección de la recta, tenemos que:
>$(x,y,z) = (p,q,r) +t(a,b,c)$
>$(x,y,z) = (p+ta,q+tb,r+tc)$
>con lo que se tiene que:
>$$ \begin{array}{cc}
x = p+ta \\
y = q+tb\\
z = r+tc
\end{array}$$
Estas denominan las ecuaciones paramétricas de la recta.
## Ecuaciones Simétricas de la Recta
Tomando como base las ecuaciones paramétricas, podemos escribir las ecuaciones simétricas de las siguiente forma:
>$\begin{align} t = \frac{x-p}{a} \end{align}$
>$\begin{align}t = \frac{y-q}{b}\end{align}$
>$\begin{align}t = \frac{z-r}{c}\end{align}$
>$$\frac{x-p}{a}=\frac{y-q}{b}=\frac{z-r}{c}$$

# Planos
un plano se define como un conjunto de puntos $Q$, tal que dado un punto $P$ y un vector $N$ distinto de cero, se tiene que:

> $$\overrightarrow{PQ} \cdot N = 0 $$

Si $P$ es un punto conocido del plano cuyo vector normal es $N$ es el vector normal del plano, y dado $Q$ un punto cualquiera del plano entonces:

$$\overrightarrow{PQ} = (x - x_0)i + (y-y_0)j + (z-z_0)k $$
retomando la idea de que $\overrightarrow{PQ} \cdot N = 0$ tenemos que:
$$(x - x_0,y-y_0,z-z_0)\cdot(a,b,c) = 0  $$
con lo que llegamos a que:
$$ ax + by + cz = ax_0 + by_0 + cz_0 $$
la parte derecha de la ecuación es constante con lo que podemos reemplazarla por el término d y expresar la ecuación del plano como:
$$ ax + by + cz = d $$

# Intersección entre Planos y Rectas

Para determinar si una recta y un plano se intersectan en el espacio tridimensional, podemos seguir estos pasos:

- Un **plano** se expresa en la forma general: $Ax + By + Cz + D = 0$ donde A,B,CA, B, C son los coeficientes normales del plano y D es el término independiente.
    Una **recta** puede expresarse en su forma paramétrica:
    
    $$\begin{Bmatrix} x = x_0 + at \\ y = y_0 + bt \\ z = z_0 + ct \end{Bmatrix}$$
    
    donde ($x_0$,$y_0$,$z_0$) es un punto de la recta y (a, b, c) es su dirección.
    

### **Cálculo de la Intersección**

1. Sustituimos las ecuaciones paramétricas de la recta en la ecuación del plano:
    
    $$A(x_0 + at) + B(y_0 + bt) + C(z_0 + ct) + D = 0$$
2. Resolvemos para $t$:
    
    $$t = \frac{-Ax_0 - By_0 - Cz_0 - D}{Aa + Bb + Cc}$$
     Si el denominador es **cero** $(Aa + Bb + Cc = 0)$, la recta es **paralela** al plano.
        
     Si el denominador es **distinto de cero**, calculamos $t$ y sustituimos en las ecuaciones de la recta para obtener el punto de intersección.

**Siguiente tema: [[Espacio Nulo y Columna]]**