When doing Partial Pivoting with Guassian Elimination:

Step 1: Look for the column with the greatest absolute value and switch to the first row.
Step 2: Reduce all the columns below the first row to zero.
Step 3: Repeat Step 1 & 2 until only pivots are left.

For example:

$$
\begin{bmatrix}
0.002&1.0&1.0\\
1.0&1.0&2.0\\
2.0&1.0&1.0
\end{bmatrix}
\begin{bmatrix}
2.0\\
4.0\\
5.0 
\end{bmatrix}
$$

We can see that for the 1st column 2.0 is the biggest.

Swap R3 <-> R1


$$
\begin{bmatrix}
2.0&1.0&1.0\\
1.0&1.0&2.0\\
0.002&1.0&1.0
\end{bmatrix}
\begin{bmatrix}
5.0\\
4.0\\
2.0
\end{bmatrix}
$$
