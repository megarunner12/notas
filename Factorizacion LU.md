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
## Resolver Sistemas de Ecuaciones usando Factorización LU

Podemos usar la factorización LU para resolver sistemas ecuaciones de la siguiente forma:

