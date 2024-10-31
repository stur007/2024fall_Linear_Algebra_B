## 线性代数B 期中复习

### 求解线性方程组

![image-20241027144519003](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027144519003.png)

用简化的方法处理，注意题目给的提示条件，不一定要全部化成阶梯型矩阵处理。大致就和小时候求解线性方程组差不多，注意到所有未知数的和可以方便的求出，进而可以快速得到答案。

### 求解行列式

![image-20241027162311605](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027162311605.png)

刚刚学会加一行加一列计算，发现还是挺方便的，但是直接用第一行加加减减还是很快能够搞定的。
$$
\matrix{1 & x_1 & x_2 & ... &x_n\\
0\\
.\\
.\\
.\\
0}
$$
![image-20241027163249210](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027163249210.png)

元素比较少，还是建议展开然后递推比较方便。

![image-20241027163807354](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027163807354.png)

题目不难，注意讨论$a=0$,$b=0$的情形。

==遇到组合数，想组合数的性质！==
$$
C_n^l = C_{n-1}^{l-1}+C_{n-1}^{l}
$$
![image-20241027164407453](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027164407453.png)

可以很好的加深对行列式展开的理解。

![image-20241027164747422](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027164747422.png)

用==倍角公式==展开，然后发现和上一题一致。

![image-20241027165114551](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027165114551.png)

注意到题目下边的提示，感觉还是挺刁钻的。

![image-20241027171221548](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027171221548.png)

个人感觉是，如果整理不成因式分解的形式，就直接写上那个展开的多项式应该也没有问题。

![image-20241027173018669](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027173018669.png)

进行一次行行相减之后，注意到每行之和均为0，可以简化运算。

![image-20241027173453454](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027173453454.png)

==注意对称性展开==

![image-20241027175724989](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027175724989.png)这个题目还是挺重要的，而且思考起来有一定难度，可以注意一下。

![image-20241027200449309](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20241027200449309.png)用解集的结构说明这个问题。

