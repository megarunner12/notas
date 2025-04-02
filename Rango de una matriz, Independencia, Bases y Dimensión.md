## Rango de una matriz

Podemos definir el Rango de una matriz como la cantidad de variables pivote existentes una vez llevada la matriz a su forma escalonada reducida:

> $$
A=
\left[
\begin{array}{cc}
1 &3 &2 \\
2 &0 &1 \\
3 &-5 &1
\end{array}
\right]
$$
al llevar a su forma escalonada reducida tenemos que:
> $$
\left[
\begin{array}{cc}
1 &3 &2 \\
0 &1 &\frac{1}{2} \\
0 &0 &0
\end{array}
\right]
$$
con lo que llegamos a que la matriz $A$ tiene rango 2.

## Independencia Lineal

Las columnas de una matriz A son linealmente independientes cuando para $AX = 0$ la única solución es $X = 0$, en otras palabras, A es linealmente independiente si si espacio nulo es igual a cero.

Podemos ver vectores independientes como vectores que no hacen parte del mismo plano, de no ser así, los consideraremos linealmente dependientes.

## Espacio Generado

El espacio generado corresponde al conjunto formado por todas las combinaciones lineales de V

> los vectores $(1,0,0),(0,1,0)$ y $(0,0,1)$ generan el espacio $\mathbb{R}^3$ 

