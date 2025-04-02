la Factorización LU permite descomponer una matriz A **reversible** como producto de la multiplicación de dos matrices.
$$
A=
\biggl[
\begin{array}{cc}
a &b \\
c &d
\end{array}
\biggl]
= LU

$$
La matriz ***L*** es una matriz triangular inferior y la matriz ***U*** es una matriz triangular superior.

$$
\biggl[
\begin{array}{cc}
a &b \\
c &d
\end{array}
\biggl]
= LU = 
\biggl[
\begin{array}{cc}
1 &0 \\
L_2 &1
\end{array}
\biggl]

\biggl[
\begin{array}{cc}
1 &U_1 \\
0 &1
\end{array}
\biggl]
$$
Para poder hallar las matrices $L$ y $U$ debemos hacer los siguiente:

1. Tomamos la matriz A y la llevamos a su forma triangular superior, solo podemos realizar sumas y restas, esta matriz va a ser la matriz $U$.
$$
\begin{Bmatrix}
2 &3 &-1 \\
2 &5 &4 \\
0 &2 &-3
\end{Bmatrix} - 1F_1 + F_2 $$
$$
=\begin{Bmatrix}
2 &3 &-1 \\
0 &2 &5 \\
0 &2 &-3
\end{Bmatrix} - 1F_2 + F_3 $$
$$
=\begin{Bmatrix}
2 &3 &-1 \\
0 &2 &5 \\
0 &0 &-6
\end{Bmatrix}$$
	Luego de esto realizamos la matriz de eliminación $L$, donde vamos a colocar todas los coeficientes de las operaciones que realizamos sobre la matriz $A$ en las posiciones donde creamos los ceros de la matriz triangular superior.
	$$L=\begin{Bmatrix}
1 &0 &0 \\
-1 &1 &0 \\
0 &-1 &1
\end{Bmatrix}$$
con esto habremos llegado a la factorización LU de la matriz A.
## Resolver Sistemas de Ecuaciones usando Factorización LU

Podemos usar la factorización LU para resolver sistemas ecuaciones de la siguiente forma:

>dada la ecuación de matrices

$$
Ax = LUx = b
$$
> donde hay un A y un b determinados

resolvemos:
$$ Ly = b $$ para ***y***, luego
$$ Ux = y $$
para ***x***.

