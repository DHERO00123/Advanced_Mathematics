

极限的运算法则
=======================

**定理1 ：两个无穷小的和是无穷小（有限个无穷小之和也是无穷小）**

**定理2： 有界函数与无穷小的乘积是无穷小**

    **推论1：常数与无穷小的乘积是无穷小.**

    **推论2：有限个无穷小的乘积是无穷小.**

**定理3**

如果 :math:`lim{f(x)=A}, lim{g(x)}=B` 那么

    (1) :math:`\lim[f(x)\pm g(x)]=\lim{f(x)} \pm \lim{g(x)}=A\pm B` 

    (2) :math:`\lim[f(x)\cdot g(x)]=\lim{f(x)} \cdot \lim{g(x)} = A \cdot B`  
        
    (3) 若又有 :math:`B\neq 0` ,则 :math:`\lim{\frac{f((x)}{g(x)}}=\frac{\lim{f((x)}}{\lim{g(x)}}=\frac{A}{B}` 


    **推论1** 如果 :math:`\lim{f(x)}` 存在，而c为常数，那么 :math:`\lim{[cf(x)]}=c\lim{f(x)}`   

    **推论2** 如果 :math:`\lim{f(x)}` 存在，而n是正整数，那么 :math:`\lim{[f(x)]^n}=[\lim{f(x)}]^n` 

**定理4**

    设有数列 :math:`{x_n}` 和 :math:`{y_n}` 如果 :math:`\lim_{n \rightarrow \infty}{x_n}=A`  ，  :math:`\lim_{n \rightarrow \infty}{y_n}=B` 那么

    1)  :math:`\lim_{n \rightarrow \infty}{x_n \pm y_n}=A \pm B`
    2)  :math:`\lim_{n \rightarrow \infty}{x_n \cdot y_n}=A \cdot B`
    3)  当 :math:`y_n \neq 0 (n=1,2...)` 且 :math:`B \neq 0` 时，:math:`lim_{n\rightarrow \infty}{\frac{x_n}{y_n}}=\frac{A}{B}`  

**定理5**

    如果 :math:`f(x) \geq g(x)`, 而 :math:`\lim{f(x)}=A,lim{g(x)}=B, 那么 A \geq B` 


**定理6(复合函数的极限运算法则)**

    设函数 :math:`y=f[g(x)]` 是由函数 :math:`u=g(x)` 与函数 :math:`y=f(u)` 复合而成 :math:`f[g(x)]` 在点 :math:`x_0` 的某去心领域内有定义，若 :math:`lim_{x\rightarrow x_0}{g(x)}=u_0, lim_{u\rightarrow u_0}{f(u)}=A` ,且存在 :math:`\delta_0 > 0` , 当 :math:`x\in  \mathring{U}(x_0,\delta_0) 时，有g(x)\neq u_0` ,则

    .. math::
        \lim_{x\rightarrow x_0}{f[g(x)]}=\lim_{u\rightarrow u_0}{f(u)}=A



.. note::  计算例子

    求 

    .. math::
        \lim_{x\rightarrow \infty}{\frac{3x^3+4x^2+2}{7x^3+5x^2-3}} 

    解， 先用 :math:`x^3` 去除分母和分子，然后求极限，得

    .. math::
        lim_{x\rightarrow \infty}{\frac{3x^3+4x^2+2}{7x^3+5x^2-3}}= \lim_{x\rightarrow \infty}{\frac{3+\frac{4}{x}+\frac{2}{x^2}}{7+\frac{5}{x}-\frac{3}{x^3}}}=\frac{3}{7}

    这是因为 

    .. math::
        \lim_{x\rightarrow \infty}{\frac{a}{x^n}}=a\lim_{x\rightarrow \infty}{\frac{1}{x^n}}=a(lim_{x\rightarrow \infty}{\frac{1}{x}})^n=0 


.. tip:: 一般情形下的特例

    例题是一般情形下的特例，即当 :math:`a_0 \neq 0, b_0 \neq 0` ,m 和 n 为非负整数时，有

    .. math::
        \lim_{x\rightarrow \infty}{\frac{a_0x^m+a_1x^{m-1}+...+a_m}{b_0x^n+b_1x^{n-1}+...+b_n}} 

        =

        0, 当 n > m,

        \frac{a_0}{b_0},当 n = m,

        \infty, 当 n < m


