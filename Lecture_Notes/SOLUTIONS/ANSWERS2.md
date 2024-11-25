![alt text](image-1.png)

### Solution 1

#### Given Matrix

$$
\mathbf{A} =
\begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix}
$$

---

### Step 1: Compute the Determinant of \(\mathbf{A}\)

The determinant of a \(3 \times 3\) matrix is given by:

$$
\text{det}(\mathbf{A}) = a_{11}
\begin{vmatrix}
a_{22} & a_{23} \\
a_{32} & a_{33}
\end{vmatrix}
- a_{12}
\begin{vmatrix}
a_{21} & a_{23} \\
a_{31} & a_{33}
\end{vmatrix}
+ a_{13}
\begin{vmatrix}
a_{21} & a_{22} \\
a_{31} & a_{32}
\end{vmatrix}
$$

Substituting the elements of \(\mathbf{A}\):

$$
\text{det}(\mathbf{A}) = 2
\begin{vmatrix}
1 & 0 \\
2 & 0
\end{vmatrix}
- 0
\begin{vmatrix}
0 & 1 \\
1 & 2
\end{vmatrix}
+ 1
\begin{vmatrix}
0 & 1 \\
1 & 2
\end{vmatrix}
$$

Compute the minors:

1.  $$
    \begin{vmatrix}
    1 & 0 \\
    2 & 0
    \end{vmatrix} = (1)(0) - (0)(2) = 0
    $$

2.  $$
    \begin{vmatrix}
    0 & 1 \\
    1 & 2
    \end{vmatrix} = (0)(2) - (1)(1) = -1
    $$

Substitute back:

$$
\text{det}(\mathbf{A}) = 2(0) - 0(-1) + 1(-1) = -1
$$

Thus:

$$
\text{det}(\mathbf{A}) = -1
$$

---

### Step 2: Compute All Cofactors

The cofactor for an element \(a\_{ij}\) is given by:

$$
C_{ij} = (-1)^{i+j}
\begin{vmatrix}
\text{minor matrix of } a_{ij}
\end{vmatrix}
$$

$$
\mathbf{A} =
\begin{pmatrix}
2 & 0 & 1 \\
0 & 1 & 0 \\
1 & 2 & 0
\end{pmatrix}
$$

#### Cofactor \(C\_{11}\):

$$
C_{11} = (-1)^{1+1}
\begin{vmatrix}
1 & 0 \\
2 & 0
\end{vmatrix} = 1 \cdot 0 = 0
$$

#### Cofactor \(C\_{12}\):

$$
C_{12} = (-1)^{1+2}
\begin{vmatrix}
0 & 0 \\
1 & 0
\end{vmatrix} = -1 \cdot (0 - 0) = 0
$$

#### Cofactor \(C\_{13}\):

$$
C_{13} = (-1)^{1+3}
\begin{vmatrix}
0 & 1 \\
1 & 2
\end{vmatrix} = 1 \cdot (-1) = -1
$$

#### Cofactor \(C\_{21}\):

$$
C_{21} = (-1)^{2+1}
\begin{vmatrix}
0 & 1 \\
2 & 0
\end{vmatrix} = -1 \cdot (0 - 2) = 2
$$

#### Cofactor \(C\_{22}\):

$$
C_{22} = (-1)^{2+2}
\begin{vmatrix}
2 & 1 \\
1 & 0
\end{vmatrix} = 1 \cdot (2(0) - 1(1)) = -1
$$

#### Cofactor \(C\_{23}\):

$$
C_{23} = (-1)^{2+3}
\begin{vmatrix}
2 & 0 \\
1 & 2
\end{vmatrix} = -1 \cdot (2(2) - 1(0)) = -4
$$

#### Cofactor \(C\_{31}\):

$$
C_{31} = (-1)^{3+1}
\begin{vmatrix}
0 & 1 \\
1 & 0
\end{vmatrix} = 1 \cdot (0 - 1) = -1
$$

#### Cofactor \(C\_{32}\):

$$
C_{32} = (-1)^{3+2}
\begin{vmatrix}
2 & 1 \\
1 & 0
\end{vmatrix} = -1 \cdot (2(0) - 1(1)) = 1
$$

#### Cofactor \(C\_{33}\):

$$
C_{33} = (-1)^{3+3}
\begin{vmatrix}
2 & 0 \\
0 & 1
\end{vmatrix} = 1 \cdot (2(1) - 0(0)) = 2
$$

---

### Step 3: Write the Cofactor Matrix

The cofactor matrix is:

$$
\mathbf{C} =
\begin{pmatrix}
0 & 0 & -1 \\
2 & -1 & -4 \\
-1 & 1 & 2
\end{pmatrix}
$$

---

## 6. Inverse of a Matrix using the Gauss Method

Find the inverse matrices using the Gauss method:

$$
\mathbf{A} =
\begin{pmatrix}
1 & 2\\
3 & 4
\end{pmatrix}
, \qquad
\mathbf{B} =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 1 \\
2 & 3 & 2
\end{pmatrix}
,\qquad
\mathbf{C} =
\begin{pmatrix}
0 & 0 & 1\\
0 & 1 & 0\\
1 & 0 & 0
\end{pmatrix}
$$
