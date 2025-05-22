

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

.. important:: 理解

    在上面的计算法则中最重要的不是怎么去拆分计算，而是在于这两个函数的极限存在，只有 **两个函数的极限都存在** 才可以进行拆分计算。

    极限不存在，不能拆分计算
    
    三类极限不存在
    1) 左极限不等于右极限
    2) 趋向于无穷
    3) :math:`x\rightarrow \sin{\frac{1}{x}}` 震荡不存在

    .. image:: ../images/jixianyunsuan1.png
        :alt: 函数运算极限图1
        :width: 600px
        :align: center

    如果只知道f(x) 极限存在，那这个式子也能拆，因为无论 g(x) 是不是存在，最终整体（图中最右边为整体）只有两种结果，就是

    存在 + 存在 = 存在
    
    存在 + 不存在 = 不存在

    为什么图中上面两个可以这这样计算，因为这样既不会改变结果，也不会改变原来的类型，还能判断整体的情况

    为什么图中第三个式子不行，因为 **不存在 + 不存在 = 不一定** 就算拆出来两个不存在的，原来是多少完全不知道

    所以综上所述，在加减运算当中只要保证一部分存在就能拆

    .. image:: ../images/jixianyunsuan2.png
        :alt: 函数运算极限图2
        :width: 600px
        :align: center

    这个是极限的运算规律，而极限的运算规律，是基于我们所有以极限为定义的基础，未来那些知识点是以极限为定义的？

    连续跟间断，导数，积分，偏导数，全微分，无穷级数敛散性 这些一切以极限为定义的概念全都满足这个法则

    在上图推论中，推论3,当 :math:`\lim{\frac{f(x)}{g(x)}}` 极限存在，且 :math:`\lim{g(x)=0}` 只有  :math:`\lim{f(x)=0}` 整体极限才存在

    推论4,如果极限存在不等于0,并且分子的极限是0,那么可以推出分母的极限也是0，可以使用倒数，回到推论3使用

    .. image:: ../images/jixianyunsuan3.png
        :alt: 函数运算极限图3
        :width: 600px
        :align: center

    非零因子可单独取极限


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


七类未定式
^^^^^^^^^^^^^^^^^^^^^^^^^^

    基础的四则运算法则计算不了的极限类型，称为未定式，主要有以下七类

    :math:`\frac{0}{0}, \frac{\infty}{\infty},\infty - \infty, 0\cdot \infty, 1^{\infty}, 0^0, \infty^0` 