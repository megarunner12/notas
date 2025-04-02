
Podemos definir el espacio columna de una matriz de la siguiente forma:
> $$
C(A)=
\left[
\begin{array}{cc}
a &b &c\\
d &e &f\\
g &h &i
\end{array}
\Bigg|
\begin{array}{cc}
 &X &\\
&Y \\
 &Z
\end{array}
\right]
$$
con lo que podemos formar un sistema de ecuaciones, para obtener los valores de (X,Y,Z).

De manera similar, definimos un espacio nulo como un sistema de ecuaciones homogéneas:
> $$
N(A)=
\left[
\begin{array}{cc}
a &b &c\\
d &e &f\\
g &h &i
\end{array}
\Bigg|
\begin{array}{cc}
 &0 &\\
&0 \\
 &0
\end{array}
\right]
$$

en este caso, las variables corresponden una a cada columna de la matriz.

Junto a estos espacios tenemos al espacio fila y el espacio nulo izquierdo, los cuales corresponden al espacio columna y al espacio nulo de la matriz traspuesta, respectivamente.

> $$
C(A^t)=
\left[
\begin{array}{cc}
a &d &g\\
b &e &h\\
c &f &i
\end{array}
\Bigg|
\begin{array}{cc}
 &X &\\
&Y \\
 &Z
\end{array}
\right]
$$
>$$N(A^t)=
\left[
\begin{array}{cc}
a &d &g\\
b &e &h\\
c &f &i
\end{array}
\Bigg|
\begin{array}{cc}
 &0 &\\
&0 \\
 &0
\end{array}
\right]$$

**Siguiente tema: [[Rango de una matriz]]**