
.. sphinx math documentation master file, created by
   sphinx-quickstart on Fri May 16 00:27:32 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

   ..  这里被注释了
   .. .. math::
   ..    :label: eq-long-formula2


映射与函数
====================

映射
-----------------

映射的概念
^^^^^^^^^^^^^^^^^^^^^

.. important:: 定义

   设X Y 是两非空集合,如果存在一个法则f,使得对X中每个元素x,按法则f,在Y中唯一确定的元素y与之对应,那么称f为从X到Y的映射记作

   :math:`f\cdot X\rightarrow Y` 


函数
-----------------

函数的概念
^^^^^^^^^^^^^^^^^^^^^

.. important:: 定义
   
   设数集 :math:`D\subset R` ,则称映射 :math:`f:D\rightarrow R` 为定义在D上的函数,通常简记为

   :math:`y=f(x),x\in D` 
   
   其中x称为自变量,y称为因变量,D称为定义域,记作 :math:`D_f` 即 :math:`D_f=D`  


.. note:: 自己的理解

   其实函数就是映射,映射就是函数,本质上完全一样

   在不同的数学领域,使用的术语不同而已

   映射的说法更加强调集合之间的关系，更适用于抽象代数、集合论等高层次数学讨论




函数的几种特性
^^^^^^^^^^^^^^^^^^^^^

**函数是实数集到实数集的映射，其值域总在R**

因此构成函数的要素是：

   **定义域** :math:`D_f` **及对应法则f.如果两个函数的定义域相同，对应法则也相同，那么这两个函数是相同的，否则就是不相同** 

函数的定义域
^^^^^^^^^^^^^^^^^^^^

函数的定义域通常有两种情况来确定，一种是有实际背景的函数，也就是有给定好的条件限制(说人话就是题目给出).

另一种是抽象的用算式表达的函数，通常约定这种函数的定义域是 **使得算式有意义的一切实数组成的集合** ，这种定义域成为 **自然定义域**



**(1) 函数的有界性**
   :math:`y = \frac {x}{1-x},(-\infty,1)` 可以变形为

   :math:`y = -1+ \frac {1}{1-x}`  
   证,设 :math:`x_1 < x_2 < 1` 因为 :math:`f(x_2) = f(x_1) = \frac {1}{1-x_2}- \frac{1}{1-x_1} = \frac{x_2-x_1}{(1-x_1)(1-x_2)}>0,`  所以 :math:`f(x_2)>f(x_1),即f(x)在(-\infty,1)` 内单调增加


**(2) 函数的单调性**

**(3) 函数的奇偶性**

   两个偶函数的和是偶函数，两个奇函数的和是奇函数

   两个偶函数的乘积是偶函数，两个奇函数的乘积是偶函数，偶函数与奇函数的乘积是奇函数

   偶函数
      设 :math:`f_1(x),f_2(x)` 均为偶函数，则 :math:`f_1(-x)=f_1(x),f_2(-x)=f_2` 

      令 :math:`F(x)=f_1(x)+f_2(x)` 
       
      于是 :math:`F(-x)=f_1(-x)+f_2(-x) = f_1(x)+f_2(x)=F(x)`
      
      故F(x) 为偶函数

   奇函数
      设 :math:`g_1(x),g_2(x)`  均为奇函数，则 :math:`g_1(-x)=-g_1(x),g_2(-x)=-g_2(x)`  
      
      令 :math:`G(x)= g_1(x)+g_2(x),`  
      
      于是 :math:`G(-x)=g_1(-x)+g_2(-x)=-g_1(x)-g_2(x)=-G(x)` 
 

**(4) 函数的周期性**

反函数与复合函数
^^^^^^^^^^^^^^^^^^^^^^^
   函数f存在反函数的前提条件为 :math:`f:D\rightarrow f(D)` 是单射


函数的运算
^^^^^^^^^^^^^^^^^^^^^
和(差) :math:`f\pm g` 

   :math:`(f\pm g(x)=f(x)\pm g(x), x\in D)` 

积 :math:`f \cdot g`
   
   :math:`(f \cdot g)=f(x) \cdot g(x), x\in D` 


商 :math:`\frac{f}{g}`

   :math:`(\frac{f}{g})(x)=\frac{f(x)}{g(x)},x\in D \{x|g(x)=0,x\in D\}`

初等函数
^^^^^^^^^^^^^^^^^^^^^^

幂函数 :math:`y=x^{\mu}` 

指数函数 :math:`y=a^x` 

对数函数 :math:`y=log_{a}x` 

三角函数 :math:`y=\sin{x}, y=\cos{x}, y=\tan{x}` 

反三角函数 :math:`y=\arcsin{x}, y=\arccos{x}, y=\arctan{x}` 

以上五类函数统称为基本初等函数



常见函数的自然定义域汇总表（实数范围内）
----------------------------------------

.. list-table::
   :widths: 30 35 35
   :header-rows: 1

   * - 函数表达式 f(x)
     - 条件限制
     - 自然定义域（实数范围）

   * - f(x) = ax + b
     - 无
     - :math:`\mathbb{R}` 

   * - :math:`f(x)=ax^2+bx+c`
     - 无
     - :math:`\mathbb{R}`

   * - :math:`f(x)=\sqrt {x}`
     - 被开方数 x ≥ 0
     - [0, +∞)

   * - :math:`f(x)=\sqrt {x-a}`
     - x ≥ a
     - [a, +∞)

   * -  :math:`f(x)=\sqrt [n] {x}` (n 为奇数)
     - 奇次根可开负数
     - :math:`\mathbb{R}`

   * - f(x) = 1 / x
     - x ≠ 0
     - :math:`\mathbb{R}` \\ {0}

   * - f(x) = 1 / (x - a)
     - x ≠ a
     - :math:`\mathbb{R}` \\ {a}

   * - :math:`f(x)= \frac{1}{\sqrt {x}}`
     - x > 0
     - (0, +∞)

   * - f(x) = ln x
     - x > 0
     - (0, +∞)

   * - f(x) = ln(x - a)
     - x > a
     - (a, +∞)

   * - f(x) = :math:`log_b{x}`  (b > 0 且 b ≠ 1)
     - x > 0
     - (0, +∞)

   * - f(x) = sin x, cos x
     - 三角函数对所有实数有定义
     - :math:`\mathbb{R}`

   * - f(x) = tan x
     - x ≠ π/2 + kπ
     - :math:`\mathbb{R}` \\ {π/2 + kπ | k ∈ :math:`\mathbb{Z}` }

   * - f(x) = arcsin x
     - -1 ≤ x ≤ 1
     - [-1, 1]

   * - f(x) = arccos x
     - -1 ≤ x ≤ 1
     - [-1, 1]

   * - f(x) = arctan x
     - 无
     - :math:`\mathbb{R}`

   * - f(x) = :math:`e^x`  
     - 无
     - :math:`\mathbb{R}`

   * - f(x) = :math:`a^x` (a > 0)
     - 无
     - :math:`\mathbb{R}`
