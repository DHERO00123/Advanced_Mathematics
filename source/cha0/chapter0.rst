
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


函数的定义域
^^^^^^^^^^^^^^^^^^^^

**函数是实数集到实数集的映射，其值域总在R**

因此构成函数的要素是：

   **定义域** :math:`D_f` **及对应法则f.如果两个函数的定义域相同，对应法则也相同，那么这两个函数是相同的，否则就是不相同** 

函数的定义域通常有两种情况来确定，一种是有实际背景的函数，也就是有给定好的条件限制(说人话就是题目给出).

另一种是抽象的用算式表达的函数，通常约定这种函数的定义域是 **使得算式有意义的一切实数组成的集合** ，这种定义域成为 **自然定义域**


函数的几种特性
^^^^^^^^^^^^^^^^^^^^^

**(1) 函数的有界性**

   设函数f(x) 的定义域为D,数集 :math:`X\subset D` 如果存在数 :math:`K_1` 使得 :math:`f(x)\leq K_1`  

   对于任一 :math:`x\in X` 都成立,那么称函数有 **上界** 而 :math:`K_1` 称为函数在X上的一个上界.

   如果存在数 :math:`K_2` 使得  :math:`f(x)\geq K_2` ,对任一 :math:`x\in X` 都成立，那么称函数f(x) 有 **下界** 而 :math:`K_2` 称为函数f(x)在X上的一个下界。


**(2) 函数的单调性**

   :math:`y = \frac {x}{1-x},(-\infty,1)` 可以变形为

   :math:`y = -1+ \frac {1}{1-x}`  
   证,设 :math:`x_1 < x_2 < 1` 因为 :math:`f(x_2) = f(x_1) = \frac {1}{1-x_2}- \frac{1}{1-x_1} = \frac{x_2-x_1}{(1-x_1)(1-x_2)}>0,`  所以 :math:`f(x_2)>f(x_1),即f(x)在(-\infty,1)` 内单调增加



**(3) 函数的奇偶性**

   两个偶函数的和是偶函数，两个奇函数的和是奇函数

   两个偶函数的乘积是偶函数，两个奇函数的乘积是偶函数，偶函数与奇函数的乘积是奇函数

   设函数f(x)的定义域D关于原点对称,如果对任一 :math:`x\in D` 
   
   :math:`f(-x)=f(x)`  恒成立,那么f(x)为 **偶函数**,如果对于任一 :math:`x\in D` 

   :math:`f(-x)=-f(x)`  恒成立,那么f(x)为 **奇函数**
 

**(4) 函数的周期性**

反函数与复合函数
^^^^^^^^^^^^^^^^^^^^^^^
  函数f存在反函数的前提条件为 :math:`f:D\rightarrow f(D)` 是单射

.. important:: 重要的个人理解

  复合函数,其实也就是多层映射关系,内层函数的输出是外层函数的输入
  
  复合函数f(g(x))要有意义,必须满足

  1) x必须在内层函数g(x)的定义域内，否则g(x)无法计算
  2) g(x)的输出结果(即g(x)的值域)必须落在外层函数f(x)的定义域中，否则f(g(x))没法计算

主要是求出符合函数的定义域，主要做不等式的计算

.. tip:: 一些不等式计算

  :math:`x^2\leq a \Rightarrow x\in [-\sqrt{a},\sqrt{a}]`

  :math:`0\leq x+a \leq 1 \Rightarrow  -a\leq x \leq 1-a`  每个位置同时运算 





函数的运算
^^^^^^^^^^^^^^^^^^^^^
和(差) :math:`f\pm g` 

   :math:`(f\pm g(x)=f(x)\pm g(x), x\in D)` 

积 :math:`f \cdot g`
   
   :math:`(f \cdot g)=f(x) \cdot g(x), x\in D` 


商 :math:`\frac{f}{g}`

   :math:`(\frac{f}{g})(x)=\frac{f(x)}{g(x)},x\in D \{x|g(x)=0,x\in D\}`

.. tip:: 求一个函数的反函数步骤

  1) 交换x和y的位置 x=f(y)
  2) 解出这个方程,求出y表示成x的表达式  :math:`y=f^{-1}(x)` 
  3) 写出反函数 :math:`f^(-1)=....` 

**例子**

  f(x)=2x+3
  
  第一步 交换x和y
  
  x=2y+3
  
  第二步 解出y
  
  :math:`y=\frac{x-3}{2}` 

  最后一步 写出反函数 所以反函数是

  :math:`f^{-1}(x)=\frac{x-3}{2}`


**三角函数例子**

  :math:`y=2\sin{3x},(-\frac{\pi}{6}\leq x \leq \frac{\pi}{6})`

  交换x和y

  :math:`x=2\sin{3y}`

  解方程，求出y表示成x， 两边同时除以2：

  :math:`\frac{x}{2}=\sin{3y}`

  两边取反正弦

  :math:`3y=\arcsin{\frac{x}{2}}`

  最后解出y

  :math:`y=\frac{1}{3}\arcsin{x}{2}`     

**复杂式例子**

  :math:`y=\frac{2^x}{2^x+1}` 
  
  交换x和y

  :math:`x=\frac{2^y}{2^y+1}`

  令 :math:`a=2^y` 则原式等于

  :math:`x=\frac{a}{a+1}`

  两边乘以(a+1)

  x(a+1)=a 
  
  xa+x=a

  移项合并解出a

  :math:`a=\frac{-x}{x-1}`

  然后代入 :math:`a=2^y`

  然后两边取以2为低的对数得

  :math:`y=\log_2{(\frac{-x}{x-1})}`    

.. tip::
   
   如果在计算中包含y的式子比较复杂可以先用某一字母代替，化简到最后再把代替的部分代入到化简的式子



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


常见角度的三角函数值（弧度制）
-------------------------------------

.. list-table:: 常见角度的三角函数值（弧度制）
   :widths: 15 25 25 25
   :header-rows: 1

   * - 弧度 \(x\)
     - :math:`\sin x` 
     - :math:`\cos x` 
     - :math:`\tan x` 
   * - 0 
     - 0 
     - 1 
     - 0 
   * - :math:`\frac{\pi}{6}` 
     - :math:`\frac{1}{2}` 
     - :math:`\frac{\sqrt{3}}{2}` 
     - :math:`\frac{\sqrt{3}}{3}` 
   * - :math:`\frac{\pi}{4}` 
     - :math:`\frac{\sqrt{2}}{2}` 
     - :math:`\frac{\sqrt{2}}{2}` 
     - 1 
   * - :math:`\frac{\pi}{3}` 
     - :math:`\frac{\sqrt{3}}{2}` 
     - :math:`\frac{1}{2}` 
     - :math:`\sqrt{3}` 
   * - :math:`\frac{\pi}{2}` 
     - 1 
     - 0 
     - 无定义
   * - :math:`\pi` 
     - 0
     - -1
     - 0
   * - :math:`\frac{3\pi}{2}` 
     - -1
     - 0
     - 无定义
   * - :math:`2\pi` 
     - 0
     - 1
     - 0

.. tip:: 记忆技巧
   
   :math:`\sin{\Theta}=\cos(90^{\circ}-\Theta)` 
   :math:`\tan{\Theta} = \frac{\sin{\Theta}}{\cos{\Theta}}`
   :math:`\sin{-x}=-\sin{x}, \cos{-x}=\cos{x}, \tan{-x}=-\tan{x}` 

