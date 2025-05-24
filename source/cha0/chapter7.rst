
函数的连续性与间断点
=============================


增量的概念(为了更好引出函数连续的定义)
-------------------------------------

    设变量u从它的一个初值 :math:`u_1` 变到最终值 :math:`u_2` ，终值与初值的差 :math:`u_2-u_1` 就较变量的 **增量** 记作 :math:`\Delta u`  即 ， :math:`\Delta u = u_2-u_1` 

    曾量可以是正的也可以是负的。为正的情形，变量u从 :math:`u_1` 变到 :math:`u_2=u_1 + \Delta u` 时是增大的，当  :math:`\Delta u` 为负时，变量 u 是减小的

    .. image:: ../images/lx2.png
        :alt: 函数连续图
        :width: 600px
        :align: center

    现在假定函数 y=f(x) 在点 :math:`x_0` 的某个领域内有定义，当自变量x在这个领域内从 :math:`x_0 变到 x_0 + \Delta x` 时，函数值或因变量f(x)相应的从 :math:`f(x_0) 变化到 f(x_0 + \Delta x)` ,因此函数值或因变量f(x)的对应增量为 :math:`\Delta y = f(x_0+\Delta x) - f(x_0)` ,习惯上也称 :math:`\Delta y`  是函数的增量。如上图所示

定义(连续)
------------------

如果，当 :math:`\Delta x` 趋于0时，函数对应增量 :math:`\Delta y` 也趋于0 ，

即 :math:`\lim_{\Delta x \rightarrow 0}{\Delta y}=0` 或 :math:`\lim_{\Delta x \rightarrow 0}{[f(x_0+\Delta x) - f(x_0)]}=0`,那就有下述定义


设函数 y=f(x)在点 :math:`x_0` 的某一领域内有定义，若 :math:`\lim_{\Delta \rightarrow 0}\Delta y=0` 或 :math:`\lim_{x \rightarrow x_0}f(x)=f(x_0)` 那么就称这个函数f(x)在点 :math:`x_0` 处是连续的

一个函数 :math:`f(x)` 在点 :math:`x = a` 处连续，当满足以下三个条件：


   1. 极限存在，即：

   :math:`\lim_{x \to a} f(x) \text{ 存在}` 

   2. 函数值存在(函数在a点有定义)，即：

   :math:`f(a) \text{ 有定义}` 

   3. 极限等于函数值：

   :math:`\lim_{x \to a} f(x) = f(a)` 


**左连续**
^^^^^^^^^^^^^^^^^^^^

    函数 :math:`f(x)` 在 :math:`x = a` 处左连续，若满足：

    .. math::

        \lim_{x \to a^-} f(x) = f(a)

**右连续**
^^^^^^^^^^^^^^^^^^^^^

    函数 :math:`f(x)` 在 :math:`x = a` 处右连续，若满足：

    .. math::

        \lim_{x \to a^+} f(x) = f(a)

.. attention::
    
    函数连续 :math:`\Leftrightarrow` 左连续且右连续

f(x)在区间上连续
    对于开区间(a,b)要求在这个区间内所有的点都连续

    对于开闭区间[a,b]要求在这个区间内,内部的点都连续,而对于左端点要求右连续,右端点要求左连续

和差化积公式

    :math:`\sin{A} + \sin{B} = 2\sin({\frac{A+B}{2})\cos({\frac{A-B}{2}}})`

    :math:`\sin{A}-\sin{B}=2\cos({\frac{A+B}{2}})\sin({\frac{A-B}{2}})`  

.. admonition:: 例子

    试证: :math:`\sin{x}` 在区间 ( :math:`-\infty, +\infty` )上连续  

    根据上述定理,只要证明在这个区间的每一点都连续

    [证] :math:`\lim_{x \rightarrow x_0}{\sin{x}}=\sin{x_0}, \forall x_0 \in R` 

    :math:`\lim_{x\rightarrow 0}{\frac{\sin{x}}{x}}=1`   

    设 :math:`x \rightarrow x_0` ,我们令 :math:`h=x-x_0` ,即 :math:`x=x_0+h` ,当 :math:`x\rightarrow x_0` 时 :math:`h \rightarrow 0`    

    :math:`\lim_{x\rightarrow x_0}{\sin{x}}=\lim_{x\rightarrow 0}sin{(x_0+h)}` ,用和角公式展开

    :math:`\sin{(x_0+h)}=\sin{x_0}\cos{h}+\cos{x_0}\sin{h}` ,所以有

    :math:`\lim_{h\rightarrow 0}{\sin{(x_0+h)}}=\lim_{h\rightarrow 0}(\sin{x_0}\cos{h}+\cos{x_0}\sin{h})` 

    :math:`\lim_{h\rightarrow 0}\cos{h}=1`

    :math:`\lim_{h\rightarrow 0}\sin{h}=0` , 代入

    :math:`\lim_{x\rightarrow x_0}{\sin{x}}=\sin{x_0}\cdot 1+\cos{x}\cdot 0`

    :math:`\lim_{x\rightarrow x_0}{\sin{x}}=\sin{x_0}` ,得证


函数的间断点
-----------------------------


函数f(x)在 :math:`x_0` 处连续有这三个条件：

    1) f(x) 在点 :math:`x_0` 有定义 
    2) :math:`\lim_{x\rightarrow x_0}{f(x_0)}` 存在 
    3) :math:`\lim_{x\rightarrow x_0}{f(x_0)}=f(x_0)`

**如果这三个条件中有一点不成立则是间断点**
    1) f(x) 在 :math:`x_0` 无有定义 
    2) f(x) 在点 :math:`x_0` 有定义，但  :math:`\lim_{x\rightarrow x_0}{f(x_0)}` 极限不存在 
    3) f(x) 在点 :math:`x_0` 有定义，但  :math:`\lim_{x\rightarrow x_0}{f(x_0)}\neq f(x_0)` 极限值不等于函数数值

间断点分类
^^^^^^^^^^^^^^
    第一类间断点:(左 右极限都存在)
        1) 可去间断点 :math:`f(x_0-0)=f(x_0+0)` 左右极限相等但是这一点没有定义
        2) 跳跃间断点 :math:`f(x_0-0) \neq f(x_0+0)` 左右极限不相等

    第二类间断点(左 右极限至少有一个不存在)
        1) 无穷间断点
        2) 震荡间断点

震荡间断点
""""""""""""""

如果函数 :math:`f(x)` 在 :math:`x = a` 的邻域内有定义，但 :math:`\lim_{x \to a} f(x)` 不存在，
且原因是函数在 :math:`x \to a` 时无限震荡（即反复变化，没有趋向稳定值），
那么 :math:`x = a` 被称为一个震荡间断点。

典型例子
""""""""""""""""

1. :math:`f(x) = \sin \frac{1}{x}`

   在 :math:`x \to 0` 时上下震荡，极限不存在。

   .. math::

      \lim_{x \to 0} \sin \frac{1}{x} \text{ 不存在}
    
当 :math:`x\rightarrow 0 时，\frac{1}{x}\rightarrow \infty`   输入值越接近0的时候，:math:`\frac{1}{x}`  就越接近（正无穷大或者负无穷大）

而 :math:`\sin{(\cdot)}`   是一个周期函数，周期是2 :math:`\pi` ，所以当输入值越大时，:math:`\sin{\frac{1}{x}}`  就会在[-1,1]之间不断震荡，所以就是震荡不存在。


2. :math:`f(x) = x \sin \frac{1}{x}`

   在 :math:`x \to 0` 时虽然震荡，但极限存在：

   .. math::

      \lim_{x \to 0} x \sin \frac{1}{x} = 0

   所以在 :math:`x = 0` 连续，不是震荡间断点。

.. attention::

    在讨论分段函数的连续性时，在函数的分段点处，必须分别考虑函数的左
    连续性和右连续性，只有函数在该点既左连续，又右连续，才能得出函数在该点连续.