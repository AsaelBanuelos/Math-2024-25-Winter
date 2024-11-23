## 1. Basic Operations on Matrices

For the following matrices:

$$
\mathbf{A}=
\begin{pmatrix}
1 & 2 \\ 
3 & 4
\end{pmatrix}
\qquad
\mathbf{B}=
\begin{pmatrix}
5 & 6 \\ 
7 & 8
\end{pmatrix}
\qquad
\mathbf{C}=
\begin{pmatrix}
-1 & 2 \\ 
3 & 0
\end{pmatrix}
\qquad
\mathbf{D}=
\begin{pmatrix}
-1 & 2 & 3 \\ 
4 & 0 & 6
\end{pmatrix}
\qquad
\mathbf{E}=
\begin{pmatrix}
1 & 2 \\ 
4 & 5 \\ 
7 & 8
\end{pmatrix}
$$

## Solutions 1:
1. Calculate: $\mathbf{A}+\mathbf{B}$; $\mathbf{B}-\mathbf{A}$; $\mathbf{A}+\mathbf{C}$; $\mathbf{D}+\mathbf{E}$.
### Operations:

#### 1.1.1:
$$
\begin{pmatrix} 
1 & 2 \\ 
3 & 4 
\end{pmatrix}
+
\begin{pmatrix} 
5 & 6 \\ 
7 & 8 
\end{pmatrix}
=
\begin{pmatrix} 
1 + 5 & 2 + 6 \\ 
3 + 7 & 4 + 8 
\end{pmatrix}
=
\begin{pmatrix} 
6 & 8 \\ 
10 & 12 
\end{pmatrix}.
$$



#### 1.1.2:
$$
\begin{pmatrix} 
5 & 6 \\ 
7 & 8 
\end{pmatrix}
-
\begin{pmatrix} 
1 & 2 \\ 
3 & 4 
\end{pmatrix}
=
\begin{pmatrix} 
5 - 1 & 6 - 2 \\ 
7 - 3 & 8 - 4 
\end{pmatrix}
=
\begin{pmatrix} 
4 & 4 \\ 
4 & 4 
\end{pmatrix}.
$$



#### 1.1.3:
$$
\begin{pmatrix} 
1 & 2 \\ 
3 & 4 
\end{pmatrix}
+
\begin{pmatrix} 
-1 & 2 \\ 
3 & 0 
\end{pmatrix}
=
\begin{pmatrix} 
1 + (-1) & 2 + 2 \\ 
3 + 3 & 4 + 0 
\end{pmatrix}
=
\begin{pmatrix} 
0 & 4 \\ 
6 & 4 
\end{pmatrix}.
$$



#### 1.1.4:
$$
\begin{pmatrix} 
-1 & 2 & 3 \\ 
4 & 0 & 6 
\end{pmatrix}
+
\begin{pmatrix} 
1 & 2 \\ 
4 & 5 \\ 
7 & 8 
\end{pmatrix}
=
\text{(dimensions do not match)}.
$$

<br>

---
---
---
<br>

## Solutions 2:
2. Calculate $\frac{1}{2}\mathbf{A}$, $2\mathbf{B}$, $-3\mathbf{C}$, and $4\mathbf{D}$.

### Scalar Multiplication Operations:
#### 1.2.1
$$
\frac{1}{2} \cdot 
\begin{pmatrix} 
1 & 2 \\ 
3 & 4 
\end{pmatrix}
=
\begin{pmatrix} 
\frac{1}{2} \cdot 1 & \frac{1}{2} \cdot 2 \\ 
\frac{1}{2} \cdot 3 & \frac{1}{2} \cdot 4 
\end{pmatrix}
=
\begin{pmatrix} 
\frac{1}{2} & 1 \\ 
\frac{3}{2} & 2 
\end{pmatrix}.
$$
#### 1.2.2
$$
2 \cdot 
\begin{pmatrix} 
5 & 6 \\ 
7 & 8 
\end{pmatrix}
=
\begin{pmatrix} 
2 \cdot 5 & 2 \cdot 6 \\ 
2 \cdot 7 & 2 \cdot 8 
\end{pmatrix}
=
\begin{pmatrix} 
10 & 12 \\ 
14 & 16 
\end{pmatrix}.
$$
#### 1.2.3
$$
-3 \cdot 
\begin{pmatrix} 
-1 & 2 \\ 
3 & 0 
\end{pmatrix}
=
\begin{pmatrix} 
-3 \cdot (-1) & -3 \cdot 2 \\ 
-3 \cdot 3 & -3 \cdot 0 
\end{pmatrix}
=
\begin{pmatrix} 
3 & -6 \\ 
-9 & 0 
\end{pmatrix}.
$$
#### 1.2.4
$$
4 \cdot 
\begin{pmatrix} 
-1 & 2 & 3 \\ 
4 & 0 & 6 
\end{pmatrix}
=
\begin{pmatrix} 
4 \cdot (-1) & 4 \cdot 2 & 4 \cdot 3 \\ 
4 \cdot 4 & 4 \cdot 0 & 4 \cdot 6 
\end{pmatrix}
=
\begin{pmatrix} 
-4 & 8 & 12 \\ 
16 & 0 & 24 
\end{pmatrix}.
$$


<br>

---
---
---

<br>

### 2. Matrix Multiplication Operations:
## Solutions 3:
3. Calculate the products $\mathbf{A}\cdot \mathbf{B}$; $\mathbf{B}\cdot \mathbf{A}$; $\mathbf{A}\cdot \mathbf{D}$; $\mathbf{D}\cdot \mathbf{E}$.


#### 1.3.1
$$
\begin{pmatrix} 
1 & 2 \\ 
3 & 4 
\end{pmatrix}
\cdot
\begin{pmatrix} 
5 & 6 \\ 
7 & 8 
\end{pmatrix}
=
\begin{pmatrix} 
(1 \cdot 5 + 2 \cdot 7) & (1 \cdot 6 + 2 \cdot 8) \\ 
(3 \cdot 5 + 4 \cdot 7) & (3 \cdot 6 + 4 \cdot 8) 
\end{pmatrix}
=
\begin{pmatrix} 
19 & 22 \\ 
43 & 50 
\end{pmatrix}.
$$

---

#### 1.3.2
$$
\begin{pmatrix} 
5 & 6 \\ 
7 & 8 
\end{pmatrix}
\cdot
\begin{pmatrix} 
1 & 2 \\ 
3 & 4 
\end{pmatrix}
=
\begin{pmatrix} 
(5 \cdot 1 + 6 \cdot 3) & (5 \cdot 2 + 6 \cdot 4) \\ 
(7 \cdot 1 + 8 \cdot 3) & (7 \cdot 2 + 8 \cdot 4) 
\end{pmatrix}
=
\begin{pmatrix} 
23 & 34 \\ 
31 & 46 
\end{pmatrix}.
$$

---

#### 1.3.3
$$
\begin{pmatrix} 
1 & 2 \\ 
3 & 4 
\end{pmatrix}
\cdot
\begin{pmatrix} 
-1 & 2 & 3 \\ 
4 & 0 & 6 
\end{pmatrix}
=
\begin{pmatrix} 
(1 \cdot -1 + 2 \cdot 4) & (1 \cdot 2 + 2 \cdot 0) & (1 \cdot 3 + 2 \cdot 6) \\ 
(3 \cdot -1 + 4 \cdot 4) & (3 \cdot 2 + 4 \cdot 0) & (3 \cdot 3 + 4 \cdot 6) 
\end{pmatrix}
=
\begin{pmatrix} 
7 & 2 & 15 \\ 
13 & 6 & 33 
\end{pmatrix}.
$$


#### 1.3.4
$$
\begin{pmatrix} 
-1 & 2 & 3 \\ 
4 & 0 & 6 
\end{pmatrix}
\cdot
\begin{pmatrix} 
1 & 2 \\ 
4 & 5 \\ 
7 & 8 
\end{pmatrix}
=
\begin{pmatrix} 
(-1 \cdot 1 + 2 \cdot 4 + 3 \cdot 7) & (-1 \cdot 2 + 2 \cdot 5 + 3 \cdot 8) \\ 
(4 \cdot 1 + 0 \cdot 4 + 6 \cdot 7) & (4 \cdot 2 + 0 \cdot 5 + 6 \cdot 8) 
\end{pmatrix}
=
\begin{pmatrix} 
28 & 32 \\ 
46 & 56 
\end{pmatrix}.
$$

<br>

---
---
---

<br>

## 2. Determinants 2x2 and 3x3

Calculate the determinants for the 2x2 and 3x3 matrices given below:

## Solutions 2x2 Matrices: 
$$
\mathbf{A}=
\begin{pmatrix}
2 & 3 \\ 
1 & 4
\end{pmatrix}
\qquad
\mathbf{B}=
\begin{pmatrix}
5 & 6 \\ 
7 & 8
\end{pmatrix}
\qquad
\mathbf{C}=
\begin{pmatrix}
1 & 2 \\ 
3 & 0
\end{pmatrix}
$$

#### 2.1.1:
$$
A = 
\begin{pmatrix} 
2 & 3 \\ 
1 & 4 
\end{pmatrix}.
$$
$$
\text{Det}(A) = (2 \cdot 4) - (3 \cdot 1) = 8 - 3 = 5.
$$

---

#### 2.1.2:
$$
B = 
\begin{pmatrix} 
5 & 6 \\ 
7 & 8 
\end{pmatrix}.
$$

$$
\text{Det}(B) = (5 \cdot 8) - (6 \cdot 7) = 40 - 42 = -2.
$$

---

#### 2.1.3:
$$
C = 
\begin{pmatrix} 
1 & 2 \\ 
3 & 0 
\end{pmatrix}.
$$

$$
\text{Det}(C) = (1 \cdot 0) - (2 \cdot 3) = 0 - 6 = -6.
$$

<br>

<br>

## Solution 3x3 Matrices:
$$
\mathbf{D}=
\begin{pmatrix}
1 & 0 & 2 \\ 
-1 & 3 & 1 \\ 
2 & 4 & -2
\end{pmatrix}
\qquad
\mathbf{E}=
\begin{pmatrix}
3 & 1 & -1 \\ 
0 & 2 & 4 \\ 
5 & 3 & 2
\end{pmatrix}
\qquad
\mathbf{F}=
\begin{pmatrix}
2 & -3 & 1 \\ 
1 & 4 & -2 \\ 
1 & 5 & 3
\end{pmatrix}
$$

### 2.1.1:
$$
\text{Det}(D) = 
\begin{pmatrix}
1 & 0 & 2 \\ 
-1 & 3 & 1 \\ 
2 & 4 & -2
\end{pmatrix}
=
1 \cdot
\begin{vmatrix}
3 & 1 \\ 
4 & -2
\end{vmatrix}
- 0 \cdot
\begin{vmatrix}
-1 & 1 \\ 
2 & -2
\end{vmatrix}
+ 2 \cdot
\begin{vmatrix}
-1 & 3 \\ 
2 & 4
\end{vmatrix}
$$

$$
=
1 \cdot (-10) + 0 \cdot (0) + 2 \cdot (-10) = -10 + 0 - 20 = -30
$$
---
### 2.1.2:
$$
\text{Det}(E) = 
\begin{pmatrix}
3 & 1 & -1 \\ 
0 & 2 & 4 \\ 
5 & 3 & 2
\end{pmatrix}
=
3 \cdot
\begin{vmatrix}
2 & 4 \\ 
3 & 2
\end{vmatrix}
- 1 \cdot
\begin{vmatrix}
0 & 4 \\ 
5 & 2
\end{vmatrix}
+ (-1) \cdot
\begin{vmatrix}
0 & 2 \\ 
5 & 3
\end{vmatrix}
$$

$$
=
3 \cdot (-8) - 1 \cdot (-20) + (-1) \cdot (-10)
= -24 + 20 + 10 = 6
$$
---
###  2.1.3:
$$
\text{Det}(F) = 
\begin{pmatrix}
2 & -3 & 1 \\ 
1 & 4 & -2 \\ 
1 & 5 & 3
\end{pmatrix}
=
2 \cdot
\begin{vmatrix}
4 & -2 \\ 
5 & 3
\end{vmatrix}
- (-3) \cdot
\begin{vmatrix}
1 & -2 \\ 
1 & 3
\end{vmatrix}
+ 1 \cdot
\begin{vmatrix}
1 & 4 \\ 
1 & 5
\end{vmatrix}
$$

$$
=
2 \cdot 22 - (-3) \cdot 5 + 1 \cdot 1
= 44 + 15 + 1 = 60
$$

<br>

---
---
---

<br>


# 3. Determinants using Laplace's Expansion
Calculate the determinants of the following matrices:

$$
A = 
\begin{pmatrix} 
2 & 3 & 1 \\ 
1 & 4 & 0 \\ 
3 & 2 & 1 
\end{pmatrix}, \quad
B = 
\begin{pmatrix} 
2 & 3 & 1 \\ 
1 & 4 & 0 \\ 
3 & 2 & 0 
\end{pmatrix}, \quad
C = 
\begin{pmatrix} 
2 & 3 & 1 & 4 \\ 
1 & 0 & 0 & 6 \\ 
3 & 2 & 1 & 5 \\ 
2 & 1 & 4 & 0 
\end{pmatrix}, \quad
D = 
\begin{pmatrix} 
2 & 3 & 1 & 4 & 5 \\ 
1 & 4 & 0 & 0 & 7 \\ 
3 & 0 & 0 & 0 & 0 \\ 
2 & 1 & 4 & 3 & 2 \\ 
1 & 2 & 3 & 4 & 5 
\end{pmatrix}.
$$

## Solutions Laplace's E.

#### 3.1.1:
$$
\text{Det}(A) = 
\begin{vmatrix}
2 & 3 & 1 \\ 
1 & 4 & 0 \\ 
3 & 2 & 1
\end{vmatrix}
=
2 \cdot 
\begin{vmatrix}
4 & 0 \\ 
2 & 1
\end{vmatrix}
- 3 \cdot 
\begin{vmatrix}
1 & 0 \\ 
3 & 1
\end{vmatrix}
+ 1 \cdot 
\begin{vmatrix}
1 & 4 \\ 
3 & 2
\end{vmatrix}.
$$
$$
\begin{vmatrix}
4 & 0 \\ 
2 & 1
\end{vmatrix}
= (4)(1) - (0)(2) = 4.
$$
$$
\begin{vmatrix}
1 & 0 \\ 
3 & 1
\end{vmatrix}
= (1)(1) - (0)(3) = 1.
$$
$$
\begin{vmatrix}
1 & 4 \\ 
3 & 2
\end{vmatrix}
= (1)(2) - (4)(3) = 2 - 12 = -10.
$$
$$
\text{Det}(A) = 2(4) - 3(1) + 1(-10) = 8 - 3 - 10 = -5.
$$
$$
\text{Det}(A) = -5
$$

---

#### 3.1.2:
$$
\text{Det}(B) = 
\begin{vmatrix}
2 & 3 & 1 \\ 
1 & 4 & 0 \\ 
3 & 2 & 0
\end{vmatrix}
=
2 \cdot 
\begin{vmatrix}
4 & 0 \\ 
2 & 0
\end{vmatrix}
- 3 \cdot 
\begin{vmatrix}
1 & 0 \\ 
3 & 0
\end{vmatrix}
+ 1 \cdot 
\begin{vmatrix}
1 & 4 \\ 
3 & 2
\end{vmatrix}.
$$
$$
\begin{vmatrix}
4 & 0 \\ 
2 & 0
\end{vmatrix}
= (4)(0) - (0)(2) = 0.
$$
$$
\begin{vmatrix}
1 & 0 \\ 
3 & 0
\end{vmatrix}
= (1)(0) - (0)(3) = 0.
$$
$$
\begin{vmatrix}
1 & 4 \\ 
3 & 2
\end{vmatrix}
= (1)(2) - (4)(3) = 2 - 12 = -10.
$$
$$
\text{Det}(B) = 2(0) - 3(0) + 1(-10) = -10.
$$

$$
\text{Det}(B) = -10
$$

---

#### 3.1.3:
$$
\text{Det}(C) = 
\begin{vmatrix}
2 & 3 & 1 & 4 \\ 
1 & 0 & 0 & 6 \\ 
3 & 2 & 1 & 5 \\ 
2 & 1 & 4 & 0
\end{vmatrix}.
$$

Expand along the second row:
$$
\text{Det}(C) = 1 \cdot 
\begin{vmatrix}
3 & 1 & 4 \\ 
2 & 1 & 5 \\ 
1 & 4 & 0
\end{vmatrix}
+ 6 \cdot 
\begin{vmatrix}
2 & 3 & 1 \\ 
3 & 2 & 1 \\ 
2 & 1 & 4
\end{vmatrix}.
$$
$$
\text{Minor of 1} = 
\begin{vmatrix}
3 & 1 & 4 \\ 
2 & 1 & 5 \\ 
1 & 4 & 0
\end{vmatrix}.
$$
1. **Minor of \(1\):**
$$
\text{Minor of 1} = 3 \cdot 
\begin{vmatrix}
1 & 5 \\ 
4 & 0
\end{vmatrix}
- 1 \cdot 
\begin{vmatrix}
2 & 5 \\ 
1 & 0
\end{vmatrix}
+ 4 \cdot 
\begin{vmatrix}
2 & 1 \\ 
1 & 4
\end{vmatrix}.
$$

$$
\begin{vmatrix}
1 & 5 \\ 
4 & 0
\end{vmatrix} = (1 \cdot 0 - 5 \cdot 4) = -20,
$$
$$
\begin{vmatrix}
2 & 5 \\ 
1 & 0
\end{vmatrix} = (2 \cdot 0 - 5 \cdot 1) = -5,
$$
$$
\begin{vmatrix}
2 & 1 \\ 
1 & 4
\end{vmatrix} = (2 \cdot 4 - 1 \cdot 1) = 7.
$$
$$
\text{Minor of 1} = 3(-20) - 1(-5) + 4(7) = -60 + 5 + 28 = -27.
$$
1. **Minor of \(6\):**
$$
\text{Minor of 6} = 
\begin{vmatrix}
2 & 3 & 1 \\ 
3 & 2 & 1 \\ 
2 & 1 & 4
\end{vmatrix}.
$$
$$
\text{Minor of 6} = 2 \cdot 
\begin{vmatrix}
2 & 1 \\ 
1 & 4
\end{vmatrix}
- 3 \cdot 
\begin{vmatrix}
3 & 1 \\ 
2 & 4
\end{vmatrix}
+ 1 \cdot 
\begin{vmatrix}
3 & 2 \\ 
2 & 1
\end{vmatrix}.
$$
$$
\begin{vmatrix}
2 & 1 \\ 
1 & 4
\end{vmatrix} = (2 \cdot 4 - 1 \cdot 1) = 7,
$$
$$
\begin{vmatrix}
3 & 1 \\ 
2 & 4
\end{vmatrix} = (3 \cdot 4 - 1 \cdot 2) = 10,
$$
$$
\begin{vmatrix}
3 & 2 \\ 
2 & 1
\end{vmatrix} = (3 \cdot 1 - 2 \cdot 2) = -1.
$$
Substitute back:
$$
\text{Minor of 6} = 2(7) - 3(10) + 1(-1) = 14 - 30 - 1 = -17.
$$
$$
\text{Det}(C) = 1(-27) + 6(-17).
$$
$$
\text{Det}(C) = -27 - 102 = -129.
$$

$$
\text{Det}(C) = -129
$$
---

### 3.1.4
$$
D =
\begin{pmatrix}
2 & 3 & 1 & 4 & 5 \\
1 & 4 & 0 & 0 & 7 \\
3 & 0 & 0 & 0 & 0 \\
2 & 1 & 4 & 3 & 2 \\
1 & 2 & 3 & 4 & 5
\end{pmatrix}.
$$
#### Expand Along the Third Row
$$
\text{Minor of } 3 =
\begin{pmatrix}
3 & 1 & 4 & 5 \\
4 & 0 & 0 & 7 \\
1 & 4 & 3 & 2 \\
2 & 3 & 4 & 5
\end{pmatrix}.
$$
1. **Minor of \(4\):**
   $$
   \text{Minor of } 4 =
   \begin{pmatrix}
   1 & 4 & 5 \\
   4 & 3 & 2 \\
   3 & 4 & 5
   \end{pmatrix}.
   $$

2. **Minor of \(7\):**
   $$
   \text{Minor of } 7 =
   \begin{pmatrix}
   3 & 1 & 4 \\
   1 & 4 & 3 \\
   2 & 3 & 4
   \end{pmatrix}.
   $$

<br>
<br>

   $$
   \text{det} =
   1 \cdot \begin{vmatrix}
   3 & 2 \\
   4 & 5
   \end{vmatrix}
   - 4 \cdot \begin{vmatrix}
   4 & 2 \\
   3 & 5
   \end{vmatrix}
   + 5 \cdot \begin{vmatrix}
   4 & 3 \\
   3 & 4
   \end{vmatrix}.
   $$
   $$
   \text{det}(\text{minor of } 4) = 1(7) - 4(14) + 5(7) = 7 - 56 + 35 = -14.
   $$


   $$
   \text{det} =
   3 \cdot \begin{vmatrix}
   4 & 3 \\
   3 & 4
   \end{vmatrix}
   - 1 \cdot \begin{vmatrix}
   1 & 3 \\
   2 & 4
   \end{vmatrix}
   + 4 \cdot \begin{vmatrix}
   1 & 4 \\
   2 & 3
   \end{vmatrix}.
   $$
   $$
   \text{det}(\text{minor of } 7) = 3(7) - 1(-2) + 4(-5) = 21 + 2 - 20 = 3.
   $$

Substitute:
$$
\text{det} =
4 \cdot \text{det}(\text{minor of } 4) + 7 \cdot \text{det}(\text{minor of } 7),
$$
$$
\text{det} = 4(-14) + 7(3),
$$
$$
\text{det} = -56 + 21 = -35.
$$
$$
\text{det}(D) = 3 \cdot -35 = -105.
$$
$$
\text{det}(D) = -105
$$

<br>

---
---
---

<br>

# Determinants from the Gauss Method and Triangular Matrices
Perform row and column operations to reduce the following matrices to an upper triangular form and calculate their determinants by taking the product of the diagonal elements.

$$
\mathbf{A}=
\begin{bmatrix}
12 & 3 \\ 
-18 & -4
\end{bmatrix}
\qquad
\mathbf{B}=
\begin{bmatrix}
1 & 2 & 3 \\ 
4 & 5 & 6 \\ 
7 & 8 & 9
\end{bmatrix}.
$$
## Solutions Gauss Method: 

### 4.1.1
$$
A =
\begin{bmatrix}
12 & 3 \\
-18 & -4
\end{bmatrix}.
$$
$$
R_2 \rightarrow R_2 + \frac{3}{2} \cdot R_1.
$$
$$
\frac{3}{2} \cdot R_1 =
\begin{bmatrix}
18 & 4.5
\end{bmatrix}.
$$
$$
\begin{bmatrix}
-18 & -4
\end{bmatrix}
+ 
\begin{bmatrix}
18 & 4.5
\end{bmatrix}
=
\begin{bmatrix}
0 & 0.5
\end{bmatrix}.
$$

### Diagonal Matrix
$$
A =
\begin{bmatrix}
12 & 3 \\
0 & 0.5
\end{bmatrix}.
$$
$$
\text{Det}(A) = 12 \cdot 0.5 = 6.
$$
###  Result:
$$
\text{Det}(A) = 6.
$$

---

### 4.1.2
The initial matrix is:
$$
B =
\begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{bmatrix}.
$$
$$
R_2 \rightarrow R_2 - 4 \cdot R_1.
$$
$$
R_2 = 
\begin{bmatrix}
4 & 5 & 6
\end{bmatrix}
-
4 \cdot 
\begin{bmatrix}
1 & 2 & 3
\end{bmatrix}
=
\begin{bmatrix}
0 & -3 & -6
\end{bmatrix}.
$$
$$
R_3 \rightarrow R_3 - 7 \cdot R_1.
$$
$$
R_3 =
\begin{bmatrix}
7 & 8 & 9
\end{bmatrix}
-
7 \cdot
\begin{bmatrix}
1 & 2 & 3
\end{bmatrix}
=
\begin{bmatrix}
0 & -6 & -12
\end{bmatrix}.
$$
$$
B =
\begin{bmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & -6 & -12
\end{bmatrix}.
$$
$$
R_3 \rightarrow R_3 - 2 \cdot R_2.
$$
$$
2 \cdot R_2 =
\begin{bmatrix}
0 & -6 & -12
\end{bmatrix}.
$$
$$
\begin{bmatrix}
0 & -6 & -12
\end{bmatrix}
-
\begin{bmatrix}
0 & -6 & -12
\end{bmatrix}
=
\begin{bmatrix}
0 & 0 & 0
\end{bmatrix}.
$$
### Diagonal matrix: 
$$
B =
\begin{bmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 0 & 0
\end{bmatrix}.
$$
$$
\text{Det}(B) = 1 \cdot (-3) \cdot 0 = 0.
$$

### **Final Result:**
$$
\text{Det}(B) = 0.
$$

