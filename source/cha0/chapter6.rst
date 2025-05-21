

无穷小的比较
===========================

定义1 （无穷小量）

    若 :math:`\lim_{x\rightarrow x_0}{f(x)}=0` ,则称f(x)为当 :math:`x\rightarrow x_0`  时的无穷小量

定义2 (无穷小的比较)

(1) 若 :math:`\lim{\frac{\beta}{\alpha}}=0` ,那么就说 :math:`\beta` 是比 :math:`\alpha`  高阶的无穷小，记为 :math:`\beta=o(\alpha)`  

(2) 若 :math:`\lim{\frac{\beta}{\alpha}}=\infty` ,那么就说 :math:`\beta` 是比 :math:`\alpha`  低阶的无穷小
 
(3) 若 :math:`\lim{\frac{\beta}{\alpha}}=c\neq 0` , 那么就说 :math:`\beta` 与 :math:`\alpha`  是同阶无穷小

(4) 若 :math:`\lim{\frac{\beta}{{\alpha}^k}}=c\neq 0 ,k > 0` , 那么就说 :math:`\beta` 是关于 :math:`\alpha`  的k阶无穷小
 
(5) 若 :math:`\lim{\frac{\beta}{\alpha}}=1` ,那么就说 :math:`\beta` 与 :math:`\alpha`  是等价无穷小，记作 :math:`\beta` ~ :math:`\alpha` 


定理1 

    :math:`\beta 与 \alpha` 是等价的充分必要条件是 :math:`\beta=\alpha +o(\alpha)`  

定理2

    .. math::

        \alpha \sim \widetilde{\alpha} 的意思是: \lim{\frac{\alpha}{\widetilde{\alpha}}}=1

        \\

        \alpha \sim \widetilde{\alpha}, \beta \sim \widetilde{\beta},且 \lim{\frac{\widetilde{\beta}}{\widetilde{\alpha}}},则

        \\
        \lim{\frac{\beta}{\alpha}}=\lim{\frac{\widetilde{\beta}}{\widetilde{\alpha}}}


常见初等函数的等价无穷小(当 :math:`x \rightarrow 0` )
-----------------------------------------------------------

======================================  ============================  ========================
     表达式                              等价无穷小形式                   备注
======================================  ============================  ========================
:math:`\sin{x}`                         :math:`x`                     :math:`\sin{x}  \sim x`  
:math:`\tan{x}`                         :math:`x`                     :math:`\tan{x} \sim x`  
:math:`\arcsin{x}`                      :math:`x`                     :math:`\arcsin{x} \sim x`  
:math:`\arctan{x}`                      :math:`x`                     :math:`\arctan{x} \sim x`  
:math:`\ln{1 + x}`                      :math:`x`                     :math:`\ln{1 + x} \sim x`  
:math:`e^x - 1`                         :math:`x`                     :math:`e^x - 1 \sim x`  
:math:`1 - \cos{x}`                     :math:`(\frac{1}{2})x^2`      :math:`1 - \cos{x}  \sim (\frac{1}{2})x^2`  
:math:`\sqrt{1 + x}`                    :math:`\frac{1}{2}x`          :math:`\sqrt{1 + x} - 1 \sim (\frac{1}{2})x`  
:math:`a^x - 1`                         :math:`x\ln{a}`               :math:`a^x - 1 \sim x\ln{a}`  
:math:`(1 + x)^r - 1`                   :math:`rx`                    :math:`r ∈ R, x \rightarrow 0`  
:math:`\ln{1 + x} - x`                  :math:`(\frac{1}{2})x^2`      二阶无穷小
:math:`\tan{x} - x`                     :math:`(\frac{1}{3})x^3`      三阶无穷小
:math:`\sin{x} - x`                     :math:`(\frac{1}{6})x^3`      三阶无穷小
:math:`e^x - 1 - x`                     :math:`(\frac{1}{2})x^2`      二阶无穷小
======================================  ============================  ========================
