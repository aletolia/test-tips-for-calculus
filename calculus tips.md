讨论二元函数的连续性，方法之一

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624202045095.png" alt="image-20210624202045095" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624202104888.png" alt="image-20210624202104888" style="zoom:67%;" />

求偏导数时的注意事项

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624202305899.png" alt="image-20210624202305899" style="zoom:67%;" />

这与在单变量函数求导时的情况十分相似

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624202527272.png" alt="image-20210624202527272" style="zoom:67%;" />

当用公式求出的偏导数在所给点处无意义而恰好又要求所给点处的偏导数时，应使用定义计算

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624202630718.png" alt="image-20210624202630718" style="zoom:67%;" />

注意自变量的位置，当我们确定其中一个量为自变量时，剩下的所谓“变量”都会变为常数，例如

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624202944311.png" alt="image-20210624202944311" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624203058718.png" alt="image-20210624203058718" style="zoom:67%;" />

一道反过来求偏导数的题目

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624203300382.png" alt="image-20210624203300382" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624203319169.png" alt="image-20210624203319169" style="zoom:67%;" />

上题中，我们相当于要从显函数 $x(u,v)$ 找出隐函数 $u(x,y)$ 和 $v(x,y)$

一个由欧拉发现的齐次定理

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624204511917.png" alt="image-20210624204511917" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624204537381.png" alt="image-20210624204537381" style="zoom:67%;" />

这类题目的解题技巧主要在于先用变量替换，然后在两侧对 $t$ 求导，在这里仍然需要强调的是，当我们在对一个自变量求导时，其他的自变量都会被视作是常数。



隐函数的求导法则，两个公式

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624204919550.png" alt="image-20210624204919550" style="zoom:67%;" />

隐函数存在性的讨论

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624205119811.png" alt="image-20210624205119811" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624205250516.png" alt="image-20210624205250516" style="zoom:67%;" />

求两平面交线在 $xOy$ 平面上投影和求其偏导数的方法异曲同工，都是联立方程以后消去 $z$ 得到平面方程，在下面的例子中，由于直线需要三个参数，因此我们取其中一个参数为 $x$ 来计算曲线的各项偏导数

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624205931944.png" alt="image-20210624205931944" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624214032607.png" alt="image-20210624214032607" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624214051026.png" alt="image-20210624214051026" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624214224307.png" alt="image-20210624214224307" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624214346125.png" alt="image-20210624214346125" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624214735291.png" alt="image-20210624214735291" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624215127577.png" alt="image-20210624215127577"  />

注意平面束方程的应用

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624215945848.png" alt="image-20210624215945848" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624220045167.png" alt="image-20210624220045167" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624220220858.png" alt="image-20210624220220858" style="zoom:67%;" />

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210624220252113.png" alt="image-20210624220252113"  />

面积分时，复杂函数的处理对策

1.变量替换，例如
$$
\frac{xdy-ydx}{x^2+xy+y^2}\\\\x^2+y^2=R^2
$$
可以使用参数方程（三角代换）来化简
$$
\begin{cases} x=Rcost& \\y=Rsint& \end{cases}
$$
代入并化简，得到
$$
\frac{R^2cos^2t+R^2sin^2t}{(R^2+R^2sintcost)^2}dt=\frac1{R^2}\frac{dt}{(1+\frac12sin2t)^2}
$$
2.利用轮换对称性和函数自身的奇偶性（对称性），此外还要注意，如果题目给出的是
$$
\int \!\!\! \int_D pdydz+qdxdz+rdxdy
$$
形式的式子，那么实际上题设就已经给出了 $\vec{n}ds$ 的表达式

在球面 $x^2+y^2+z^2=1$ 上计算向量场 $\frac{2}{xcos^2x}\vec{i}+\frac1{cos^2y}\vec{j}-\frac{1}{zcos^2z}\vec{k}$ 的面积分

首先由于球面的轮换对称性，我们可以得到原式等于
$$
\int \!\!\! \int_D(\frac{2}{zcos^2z}\vec{i}+\frac1{cos^2z}\vec{j}-\frac{1}{zcos^2z}\vec{k})\cdot \vec{n} ds
$$
方法一：采用向量场内积法向量的方式，我们可以得到原式等于
$$
\int \!\!\! \int_D (\frac{2}{cos^2x}+\frac y{cos^2y}-\frac{1}{cos^2z})\frac1{z}dA\\ =\int \!\!\! \int_D (\frac{2}{zcos^2x}+\frac y{zcos^2y}-\frac{1}{zcos^2z})dA
$$
由于球面存在轮换对称性，我们可以把上面的

方法二：

上面的式子也可以写成
$$
\int \!\!\! \int_D \frac{2}{xcos^2x}dydz+\frac1{cos^2y}dxdz-\frac{1}{zcos^2z}dxdy
$$
的形式，基于轮换对称性，有
$$
\int \!\!\! \int_D(\frac{2}{zcos^2z}dydz+\frac1{cos^2z}dxdz-\frac{1}{zcos^2z}dxdy)
$$
即
$$
\int \!\!\! \int_D(\frac{1}{zcos^2z}dxdy+\frac1{cos^2z}dxdy)
$$
根据函数的对称性不难得到
$$
\int \!\!\! \int_D\frac1{cos^2z}dxdy=0
$$
因此原式等于
$$
\int \!\!\! \int_D\frac{1}{zcos^2z}dxdy
$$
正项级数的审敛法则存在适用范围，请注意这一点

对于收敛的正项级数 $u_n$ ,我们可以给其第 $n$ 项界定一个范围，比如 $0<u_n<M$ 其中 $M$ 可以是任意小的正数，然后我们可以用 $M$ 来代替 $u_n$ 放到式子里去

在比较审敛法中，注意基本不等式的使用，两个包含平方的级数相加，往往可以通过基本不等式来得到绝对收敛或是其他性质

比较审敛法注意等价无穷小的意义

题设中只有两个抽象级数，但证明收敛性时出现具体数值（比如 n 这类参数），一种方法是考虑给其中一个抽象级数赋予具体的值来判断审敛性，或者构造一个级数来辅助解题，例如：已知级数 $\Sigma{u_n^2}$ 收敛，试证明 $\Sigma\frac{u_n}{n}$ 也收敛。解决方法是构造一个级数 $\Sigma v_n^2$ 并假设其收敛，不难得到 $\Sigma|u_nv_n|$ 收敛（绝对收敛），因此令 $v_n=\frac1n$ ，有 $u_nv_n=\frac{u_n}{n}$ ，因此命题得证

注意 $sinx<x$ 和 $sinx<1$ 的合理代换 (对于 $cos$ 同理)

一个结论：假如正项级数 $\Sigma a_n$ 收敛，且 $lim b_n\rightarrow k$ ，则级数 $\Sigma a_nb_n$ 和 $\Sigma(-1)^na_nb_n)$ 均收敛

$cosnx=(-1)^n$ $sin(n\pi+t)=(-1)^nsint$

判断一个交错项级数是条件收敛还是绝对收敛时，先套上绝对值变为正项级数判断其收敛性，再用莱布尼茨判别法判断其交错项级数是否收敛

注意 $a_{2n-1}-a_{2n}=(a_1-a_2)+(a_3-a_4)……$ 和 $(-1)^na_n=a_1-a_2+a_3-a_4……$ 之间的联系

![img](https://bkimg.cdn.bcebos.com/pic/c2cec3fdfc0392458b10a49e8794a4c27c1e25fd?x-bce-process=image/watermark,image_d2F0ZXIvYmFpa2UxMTY=,g_7,xp_5,yp_5/format,f_auto)



$$
∫tanx（secx）^2xdx=∫tanxd（tanx）
=tanxtanx-∫tanxd（tanx）=tan^2x-∫tanx（secx）^2dx
$$


![image-20210626094628760](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626094628760.png)

![image-20210626094716391](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626094716391.png)

![image-20210626094757112](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626094757112.png)

求解幂级数和函数的典型例题

1.直接求导+放入变限积分中积分求解

![image-20210626095241431](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626095241431.png)

2.直接求导行不通时，通过增减指数，系数配方至可以求导，再放入变限积分中求解（注意在提出系数时，$x$  不能为 $0$ ，因此要单独讨论）

![image-20210626100840536](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626100840536.png)

![image-20210626101250378](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626101250378.png)

![image-20210626101640745](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626101640745.png)

<img src="C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626101808195.png" alt="image-20210626101808195" style="zoom:67%;" />



等比数列求和是求前$n$项的和。 等比级数求和是求所有项的和。 如果令项数$n$趋于无穷，那两者是一样的。 前$n$项和为： $S_n=a_1(1-q^n)/(1-q)$ 在$|q|<1$的情况下，$q^n$是趋于0的。

![image-20210626102712708](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626102712708.png)

![img](https://iknow-pic.cdn.bcebos.com/79f0f736afc3793185d3e948fbc4b74543a91113?x-bce-process%3Dimage%2Fresize%2Cm_lfit%2Cw_600%2Ch_800%2Climit_1%2Fquality%2Cq_85%2Fformat%2Cf_jpg)

![image-20210626102958953](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20210626102958953.png)



![img](https://img-blog.csdn.net/20180707110841574?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3RhbnRpYW82NjY=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![img](https://pic3.zhimg.com/80/v2-3da1fbfe79c2beefb6d0c4e4cbe18dee_720w.jpg)



有隐函数组：

![img](https://pic3.zhimg.com/80/v2-6309b7adf50668fc68628c45e677d3c6_720w.jpg)

则：

![img](https://pic3.zhimg.com/80/v2-6846a1dafd9ddbf121277cffb11b52f6_720w.jpg)

两边对于x求导

![img](https://pic1.zhimg.com/80/v2-39cef8adfe6cb4d2c55b9a50d5154814_720w.jpg)































