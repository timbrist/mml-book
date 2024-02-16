# Exercise 2.4

Compute the floowing matrix products, if possible:

## [Matrix Multiplication](https://en.wikipedia.org/wiki/Matrix_multiplication)

\[
\begin{bmatrix}
a_{11} & a_{12} & \dots & a_{1n}\\
a_{21} & a_{22} & \dots & a_{2n}\\
\vdots & \vdots & \ddots & \vdots\\
a_{m1} & a_{m2} & \dots & a_{3n}\\
\end{bmatrix} \begin{bmatrix}
b_{11} & b_{12} & \dots & b_{1p}\\
b_{21} & b_{22} & \dots & b_{2p}\\
\vdots & \vdots & \ddots & \vdots\\
b_{n1} & b_{n2} & \dots & b_{3p}\\
\end{bmatrix} = \begin{bmatrix}
\sum_{i}^{n}a_{1i}b_{i1} &\sum_{i}^{n}a_{1i}b_{i2}  & \dots & \sum_{i}^{n}a_{1i}b_{ip} \\
\sum_{i}^{n}a_{2i}b_{i1}&\sum_{i}^{n}a_{2i}b_{i2} & \dots & \sum_{i}^{n}a_{2i}b_{ip} \\
\vdots & \vdots & \ddots & \vdots\\
\sum_{i}^{n}a_{mi}b_{i1} &\sum_{i}^{n}a_{mi}b_{i2}& \dots &\sum_{i}^{n}a_{mi}b_{ip}\\
\end{bmatrix}
\]
memorization trick: The row dot each column in row.

## solution a:
\[
\begin{bmatrix}
1&2 \\
4&5 \\
7&8\\
\end{bmatrix} 
\begin{bmatrix}
1 & 1& 0 \\
0 & 1& 1\\
1 & 0& 1 \\
\end{bmatrix}
\]
Wrong format, the number of column in first matrix doesn't equal to the number of row in second matrix.

## solution b:
\[
\begin{bmatrix}
1&2&3 \\
4&5&6 \\
7&8&9\\
\end{bmatrix} 
\begin{bmatrix}
1 & 1& 0 \\
0 & 1& 1\\
1 & 0& 1 \\
\end{bmatrix} = \begin{bmatrix}
1\cdot1+2\cdot 0+3\cdot1 & 1\cdot1+2\cdot1+3\cdot0 & 1\cdot0+2\cdot1+3\cdot1 \\
4\cdot1+5\cdot 0+6\cdot1 & 4\cdot1+5\cdot1+6\cdot0 & 4\cdot0+5\cdot1+6\cdot1 \\
7\cdot1+8\cdot 0+9\cdot1 & 7\cdot1+8\cdot1+9\cdot0 & 7\cdot0+8\cdot1+9\cdot1 \\
\end{bmatrix}
\]
\[
=\begin{bmatrix}
4&3&5 \\
10&9&11 \\
16&15&17\\
\end{bmatrix} 
\]