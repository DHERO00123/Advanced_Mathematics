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



三角函数公式汇总
---------------------

一、基本三角恒等式
^^^^^^^^^^^^^^^^^^^^^

.. list-table:: 基本恒等式
   :widths: 20 80
   :header-rows: 1

   * - 名称
     - 公式
   * - 倒数关系
     - :math:`\sin x = \frac{1}{\csc x} \quad \cos x = \frac{1}{\sec x} \quad \tan x = \frac{1}{\cot x}`
   * - 商数关系
     - :math:`\tan x = \frac{\sin x}{\cos x} \quad \cot x = \frac{\cos x}{\sin x}`
   * - 勾股恒等式
     - :math:`\sin^2 x + \cos^2 x = 1 \quad 1 + \tan^2 x = \sec^2 x \quad 1 + \cot^2 x = \csc^2 x`

二、诱导公式
^^^^^^^^^^^^^^^^^^^^

.. list-table:: 诱导公式（奇偶性与周期性）
   :widths: 50 50
   :header-rows: 1

   * - 形式
     - 关系
   * - :math:`\sin(-x)`
     - :math:`- \sin x (奇函数)`
   * - :math:`\cos(-x)`
     - :math:`\cos x (偶函数)`
   * - :math:`\tan(-x)`
     - :math:`- \tan x (奇函数)`
   * - :math:`\sin(\pi - x)`
     - :math:`\sin x`
   * - :math:`\cos(\pi - x)`
     - :math:`- \cos x`
   * - :math:`\tan(\pi - x)`
     - :math:`- \tan x`
   * - :math:`\sin(\pi + x)`
     - :math:`- \sin x`
   * - :math:`\cos(\pi + x)`
     - :math:`- \cos x`
   * - :math:`\tan(\pi + x)`
     - :math:`\tan x`
   * - :math:`\sin(\frac{\pi}{2} - x)`
     - :math:`\cos x`
   * - :math:`\cos(\frac{\pi}{2} - x)`
     - :math:`\sin x`
   * - :math:`\tan(\frac{\pi}{2} - x)`
     - :math:`\cot x`

三、和差角公式
^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table:: 和差化积
   :widths: 100
   :header-rows: 0

   * - :math:`\sin A \pm \sin B = 2 \sin \frac{A \pm B}{2} \cos \frac{A \mp B}{2}`
   * - :math:`\cos A + \cos B = 2 \cos \frac{A + B}{2} \cos \frac{A - B}{2}`
   * - :math:`\cos A - \cos B = -2 \sin \frac{A + B}{2} \sin \frac{A - B}{2}`

.. list-table:: 积化和差
   :widths: 100
   :header-rows: 0

   * - :math:`\sin A \sin B = \frac{1}{2}[\cos(A - B) - \cos(A + B)]`
   * - :math:`\cos A \cos B = \frac{1}{2}[\cos(A - B) + \cos(A + B)]`
   * - :math:`\sin A \cos B = \frac{1}{2}[\sin(A + B) + \sin(A - B)]`

.. list-table:: 和差角展开
   :widths: 100
   :header-rows: 0

   * - :math:`\sin(A \pm B) = \sin A \cos B \pm \cos A \sin B`
   * - :math:`\cos(A \pm B) = \cos A \cos B \mp \sin A \sin B`
   * - :math:`\tan(A \pm B) = \frac{\tan A \pm \tan B}{1 \mp \tan A \tan B}`

四、倍角公式
^^^^^^^^^^^^^^^^^^^^^

.. list-table::
   :widths: 100
   :header-rows: 0

   * - :math:`\sin(2x) = 2 \sin x \cos x`
   * - :math:`\cos(2x) = \cos^2 x - \sin^2 x = 1 - 2 \sin^2 x = 2 \cos^2 x - 1`
   * - :math:`\tan(2x) = \frac{2 \tan x}{1 - \tan^2 x}` (当 :math:`\tan x \ne \pm 1` )

五、半角公式
^^^^^^^^^^^^^^^^^^^

.. list-table::
   :widths: 100
   :header-rows: 0

   * - :math:`\sin^2 \frac{x}{2} = \frac{1 - \cos x}{2}`
   * - :math:`\cos^2 \frac{x}{2} = \frac{1 + \cos x}{2}`
   * - :math:`\tan \frac{x}{2} = \frac{\sin x}{1 + \cos x} = \frac{1 - \cos x}{\sin x}`

六、常见角度三角函数值
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table:: 常见角度值
   :widths: 20 25 25 30
   :header-rows: 1

   * - 角度
     - :math:`\sin \theta`
     - :math:`\cos \theta`
     - :math:`\tan \theta`
   * - :math:`0^\circ / 0`
     - 0
     - 1
     - 0
   * - :math:`30^\circ / \frac{\pi}{6}`
     - :math:`\frac{1}{2}`
     - :math:`\frac{\sqrt{3}}{2}`
     - :math:`\frac{1}{\sqrt{3}}`
   * - :math:`45^\circ / \frac{\pi}{4}`
     - :math:`\frac{\sqrt{2}}{2}`
     - :math:`\frac{\sqrt{2}}{2}`
     - 1
   * - :math:`60^\circ / \frac{\pi}{3}`
     - :math:`\frac{\sqrt{3}}{2}`
     - :math:`\frac{1}{2}`
     - :math:`\sqrt{3}`
   * - :math:`90^\circ / \frac{\pi}{2}`
     - 1
     - 0
     - 无定义



.. tip:: 记忆技巧

  倒数关系

    正弦对余割、余弦对正割、正切对余切。口诀：“正对余，余对正”。


  和差化积公式

    正加正，正在前。正减正，余在前
    
    余加余，余并肩。余减余，负正弦

  积化和差

    积化和差得和差，余弦在后要相加；

    异号函数取正弦，正弦相乘取负号。

  倍角公式记忆方法

    :math:`\sin(2x) = 2\sin x \cos x`

    👉 想成是 sin 和 cos 的“合作”

    :math:`\cos(2x)` 有三种形式：
    :math:`\cos^2 x - \sin^2 x、1 - 2\sin^2 x、2\cos^2 x - 1`

    👉 口诀：“一个三合一”。


.. tip:: 诱导公式

  .. image:: ../images/sanjiao1.png
   :alt: 三角函数角度在各个象限正负情况
   :width: 600px
   :align: center
   
       
  全 正 正 (第一象限:三角函数都为正)

  正 负 负 (第二象限:sin正,其余负)

  负 负 正 (第三象限:tan正,其余负)
  
  负 正 负 (第四象限:cos正,其余负)

  “全(第一象限)正，正(第二象限)切，三(第三象限)正切，四(第四象限)余”

  诱导公式记忆口诀  “奇变偶不变，符号看象限” 

  奇变”：若角是奇数倍的 :math:`\frac{\pi}{2}`  ，函数名称要变（sin↔cos，tan↔cot）

  “偶不变”：角是偶数倍的 :math:`\pi` ，函数名称不变；

  “符号看象限”：结果前面的符号由角所在的象限决定。
  
    