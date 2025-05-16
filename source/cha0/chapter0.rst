
.. sphinx math documentation master file, created by
   sphinx-quickstart on Fri May 16 00:27:32 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.




映射与函数
====================

映射
-----------------

映射的概念
^^^^^^^^^^^^^^^^^^^^^

.. admonition:: 定义

   设X Y 是两非空集合,如果存在一个法则f,使得对X中每个元素x,按法则f,在Y中唯一确定的元素y与之对应,那么称f为从X到Y的映射记作

   .. math::
      :label: eq-long-formula1

      f\cdot X\rightarrow Y


函数
-----------------

函数的概念
^^^^^^^^^^^^^^^^^^^^^

.. admonition:: 定义
   
   设数集 :math:`D\subset R` ,则称映射 :math:`f:D\rightarrow R` 为定义在D上的函数,通常简记为
   
   .. math::
      :label: eq-long-formula2
      
      y=f(x),x\in D

   其中x称为自变量,y称为因变量,D称为定义域,记作 :math:`D_f` 即 :math:`D_f=D`  


函数的几种特性
^^^^^^^^^^^^^^^^^^^^^

(1)函数的有界性
   :math:`y = \frac {x}{1-x},(-\infty,1)` 可以变形为

   :math:`y = -1+ \frac {1}{1-x}`  
   证,设 :math:`x_1 < x_2 < 1` 因为 :math:`f(x_2) = f(x_1) = \frac {1}{1-x_2}- \frac{1}{1-x_1} = \frac{x_2-x_1}{(1-x_1)(1-x_2)}>0,`  所以 :math:`f(x_2)>f(x_1),即f(x)在(-\infty,1)` 内单调增加

(2)函数的单调性

(3)函数的奇偶性

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
 

(4)函数的周期性

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