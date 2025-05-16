

无穷小的比较
===========================

定义1 （无穷小量）

    若 :math:`\lim_{x\rightarrow x_0}{f(x)}=0` ,则称f(x)为当 :math:`x\rightarrow x_0`  时的无穷小量

定义2 (无穷小的比较)
(1) 若 :math:`\lim{\frac{\alpha(x)}{\beta(x)}}=0` ,则称 :math:`\alpha(x)` 是 :math:`\beta(x)`  的高阶无穷小，记为 :math:`\alpha(x)=o(\beta(x))`  

(3) 若 :math:`\lim{\frac{\alpha(x)}{\beta(x)}}=\infty` ,则称 :math:`\alpha(x)`  是 :math:`\beta(x)`  的低阶无穷小
 
(4) 若 :math:`\lim{\frac{\alpha(x)}{\beta(x)}}=a\neq0` , 则称 :math:`\alpha(x)`  与 :math:`\beta(x)`  是同阶无穷小
 
(5) 若 :math:`\lim{\frac{\alpha(x)}{\beta(x)}}=1`  ,则称 :math:`\alpha(x)`  与 :math:`\beta(x)`  是等价无穷小，记为 :math:`\alpha(x)~\beta(x)`  


定理1 

    :math:`\alpha(x)~\beta(x)` 的充要条件是 :math:`\alpha(x)=\beta(x)+o(\beta(x))`  

定理2

    设 :math:`\alpha(x)~\alpha_1(x),\beta(x)~\beta_1(x)` ,且 :math:`\lim{\frac{\alpha_1(a)}{\beta_1(x)}}` 存在，则 :math:`\lim{\frac{\alpha(x)}{\beta(x)}}=\lim{\frac{\alpha_1(x)}{\beta_1(x)}}` 