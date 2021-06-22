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



















