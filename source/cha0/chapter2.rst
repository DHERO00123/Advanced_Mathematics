

函数的极限
=====================
    在自变量的某个变化过程中，如果对应的函数值无限接近于某个确定的数，那么这个确定的数就叫做在这一变化过程中函数的极限

    函数f(x)的极限，主要研究两种情形:

函数极限的定义
------------------------

    (1)自变量x任意地接近于有限值 :math:`x_0`  或者说趋于有限值 :math:`x_0`  (记作 :math:`x\rightarrow x_0` )时,对应的函数值f(x)的变化情形；

    (2)自变量x的绝对值|x|无限增大即趋于无穷大(记作 :math:`x\rightarrow \infty` ),对应的函数值f(x)的变化情形.


自变量趋于有限值时函数的极限
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

    现在考虑自变量x的变化过程为 :math:`x\rightarrow x_0`  如果在 :math:`x\rightarrow x_0` 的过程中,对应的函数值f(x)无限接近于确定的数值A,那么就说A是函数f(x)当 :math:`x\rightarrow x_0` 时的极限在 :math:`x\rightarrow x_0`  的过程中,对应的函数值f(x)无限接近于A,就是|f(x)-A|能任意小

定义1

    设函数f(x)在点 :math:`x_0`  的某一去心邻域内有定义,如果存在常数A,对于任意给定的正数 :math:`\epsilon` （不论它多么小），总存在正数 :math:`\delta`  ,使得当x满足不等式 :math:`0<|x-x_0|<\delta` 时,对应的函数值f(x)均都满足不等式 :math:`|f(x)-A|<\epsilon`  那么常数A就叫做函数f(x)当 :math:`x\rightarrow x_0`  时的极限，记作 :math:`\lim_{x\rightarrow x_0}f(x)=A` 

定义1可以简单地表述为

    :math:`\lim_{x\rightarrow x_0}f(x)=A \Leftrightarrow \forall \epsilon >0,\exists \delta > 0` ,当 :math:`0<|x-x_0|<\delta`   时，有 :math:`|f(x)-A|<\epsilon`  

自变量趋于无穷大时函数的极限
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

定义2
    设函数f(x)当大于某一正数时有定义.如果存在常数A，对于任意给定的正数 :math:`\epsilon` 不论它多么小,总存在着正数X,使得当x满足不等式 :math:`|x|>X` 时,对应的函数值f(x)都满足不等式 :math:`|f(x)-A|<\epsilon`   那么常数A就叫做函数f(x)当 :math:`x\rightarrow \infty`  时的极限，记作 :math:`\lim_{x \rightarrow \infty}{f(x)}=A \quad`  或 :math:`\quad f(x) \rightarrow A` (当x :math:`\rightarrow \infty`  )

定义2可简单地表达为
    :math:`\lim_{x\rightarrow \infty}f(x)=A \Leftrightarrow \forall \epsilon >0,\exists X>0` ,当|x|>X 时，有 :math:`|f(x)-A|<\epsilon`  

.. note::

    如果x>0且无限增大(记作 :math:`x \rightarrow + \infty` )，那么只要把上面定义中的|x|>X改为x>X，就可得 :math:`\lim_{x\rightarrow +\infty}{f(x)}=A`  的定义.
    
    同样,如果x<0且|x|无限增大(记作 :math:`x\rightarrow -\infty` )，那么只要把|x|>X改为x<-X,便得 :math:`\lim_{x\rightarrow -\infty}{f(x)}=A`  的定义.


函数极限的性质
----------------------

定理1 函数极限的唯一性
    如果 :math:`\lim_{x\rightarrow x_0}{f(x)}`  存在，那么这极限唯一.

定理2 函数极限的局部有界性
    如果 :math:`\lim_{x\rightarrow x_0}{f(x)}=A` ,那么存在常数M>0和 :math:`\delta>0` ,使得,当 :math:`0<|x-x_0|<\delta时，有|f(x)|\leq M`  

定理3 函数极限的局部保号性 
    如果 :math:`\lim_{x\rightarrow x_0}{f(x)}=A` 且A>0 (或A<0)那么存在常数 :math:`\delta>0` ,使得当 :math:`0<|x-x_0|<\delta`  时,有f(x)>0(或f(x)<0)

推论   
    如果 :math:`x_0` 在的某去心邻域内 :math:`f(x)\geq0（或f(x)\leq 0` ,而且 :math:`\lim_{x\rightarrow x_0}{f(x)}=A` , 那么 :math:`A\geq` (或 :math:`A\leq 0` )