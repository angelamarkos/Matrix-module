# Matrix-module

Create Matrix class with following methods:

1. __init__(self, 2d_array) must get 2d array in argument
1.1. befor creating Matrix shuld be checked if matrix
   . has anly numerical items
   . rows have same length
if not raise Exception with corresponding message

2. __add__(self, other_matrix) method should add current instance to matrix instanse that pass as argument
3. __sub__(self, other_matrix) method should subtract from current instance a matrix instanse that pass as argument
4. __mul__(self, other_matrix) method should multiply current instance with matrix instanse that pass as argument
5. __str__(self, other_matrix) method shuld return string of matrix as follows:

⌈ 1.60  3.1 42.34 ⌉
|  4.0 5.00   6.9 |
⌊ 43.0  2.4  3.99 ⌋

6. determinant() calculates determinant of matrix
7. inverse() calculate inverse of matrix
8. same_dimention_with(other_matrix) makes sure other matrix has the same dimension as instance matrix
9. is_square() check if matrix is square
10. random_matrix() static method returns instance of Matrix by 

https://en.wikipedia.org/wiki/Matrix_(mathematics)
