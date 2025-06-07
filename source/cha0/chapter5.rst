极限存在的法则 两重要极限
===============================

如何判定极限存在？


1) 夹逼准则

    从某个N项以后满足这个关系
    数列
    准则：如果数列 :math:`\{x_n\},\{y_n\} 及\{z_n\}` 满足下列条件

    (1) 从某项起，即 :math:`\exists n_0\in N_+ 当 n > n_0 时,有` :math:`y_n \leq x_n  \leq z_n;` 
        
    (2) :math:`\lim_{n\rightarrow \infty}{y_n}=a,\lim_{n\rightarrow \infty}{z_n}=a` ,那么数列 :math:`\{x_n\}` 的极限存在，且 :math:`,\lim_{n\rightarrow \infty}{x_n}=a` 

2) 单调有界准则

    准则 单调有界数列必有极限

    即单调递增（减）有上（下）界的数列必有极限

    因为单增数列的第一项就是最小值，因为减增数列的第一项就是最大值

    设函数f(x) 在点 :math:`x_0` 的某个在左领域内单调并且有界,则f(x) 在 :math:`x_0` 的左极限 :math:`f(x_0^-)` 必定存在

柯西极限存在准则

    数列 :math:`{x_n}` 收敛的充分必要条件是:对于任意给定的正数 :math:`\varepsilon` ,存在正整数N ,使得当 m > N,n> N 时，有 :math:`|x_n-x_m|<\varepsilon`  




两个重要极限(真重要)
--------------------------

(1) :math:`\lim_{x\rightarrow 0}{\frac{\sin x}{x}=1},\quad \lim_{\Delta \rightarrow 0}{\frac{\sin \Delta}{\Delta}=1},(\Delta \neq 0)`  

(2) :math:`\lim_{x\rightarrow \infty}{(1+ {\frac{1}{x})}^x}=e \quad  \lim_{x\rightarrow 0}{(1+x)^{\frac{1}{x}}}=e \quad \lim_{\Delta \rightarrow 0}{(1+ \Delta)^{\frac{1}{\Delta}}=e},(\Delta \neq 0)` 


极限公式

    :math:`\lim_{x\rightarrow 0}{\frac{1-\cos{x}}{x^2}}=\frac{1}{2}` 

    