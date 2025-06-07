
.. sphinx math documentation master file, created by
   sphinx-quickstart on Fri May 16 00:27:32 2025.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

   ..  这里被注释了
   .. .. math::
   ..    :label: eq-long-formula2


基础数学知识&需要背的公式
=================================

初等函数
---------------------------

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



三角函数相关
-----------------

一、基本三角恒等式
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::
   :widths: 100
   :header-rows: 0

   * - :math:`\sin(2x) = 2 \sin x \cos x`
   * - :math:`\cos(2x) = \cos^2 x - \sin^2 x = 1 - 2 \sin^2 x = 2 \cos^2 x - 1`
   * - :math:`\tan(2x) = \frac{2 \tan x}{1 - \tan^2 x}` (当 :math:`\tan x \ne \pm 1` )

五、半角公式
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::
   :widths: 100
   :header-rows: 0

   * - :math:`\sin^2 \frac{x}{2} = \frac{1 - \cos x}{2}`
   * - :math:`\cos^2 \frac{x}{2} = \frac{1 + \cos x}{2}`
   * - :math:`\tan \frac{x}{2} = \frac{\sin x}{1 + \cos x} = \frac{1 - \cos x}{\sin x}`

六、常见角度三角函数值
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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
  

极限&积分相关公式
-------------------------

常用函数的麦克劳林展开
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

以下是常用初等函数在 x = 0 处的泰勒展开（即麦克劳林公式），适用于极限计算、近似计算、微积分证明等：

.. list-table:: 常用函数的麦克劳林展开 :math:`(x \rightarrow 0)`
   :widths: 25 60 25
   :header-rows: 1

   * - 函数 f(x)
     - 麦克劳林展开式
     - 收敛区间
   * - :math:`e^x`  
     - :math:`1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \cdots+\frac{x^n}{n!}+o(x^n)`  
     - :math:`(-\infty, +\infty)`  
   * - :math:`\ln(1+x)`  
     - :math:`x - \frac{x^2}{2} + \frac{x^3}{3} - \frac{x^4}{4}+o(x^4)`  
     - :math:`(-1, 1]`  
   * - :math:`\frac{1}{1 - x}`  
     - :math:`1 + x + x^2 + x^3 + \cdots`  
     - :math:`|x| < 1`  
   * - :math:`\frac{1}{1 + x}`  
     - :math:`1 - x + x^2 - x^3 + \cdots`  
     - :math:`|x| < 1`  
   * - :math:`\sin x`  
     - :math:`x - \frac{x^3}{3!} + \frac{x^5}{5!} - \frac{x^7}{7!} + \cdots`  
     - :math:`(-\infty, +\infty)`
   * - :math:`\cos x`  
     - :math:`1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \cdots`  
     - :math:`(-\infty, +\infty)`  
   * - :math:`\tan x`  
     - :math:`x + \frac{x^3}{3} + \frac{2x^5}{15} + \cdots`  
     - :math:`\left(-\frac{\pi}{2}, \frac{\pi}{2}\right)`
   * - :math:`\arcsin x`  
     - :math:`x + \frac{x^3}{6} + \frac{3x^5}{40} + \cdots`  
     - :math:`|x| \leq 1`  
   * - :math:`\arctan x`  
     - :math:`x - \frac{x^3}{3} + \frac{x^5}{5} - \cdots`  
     - :math:`|x| \leq 1`  
   * - :math:`(1 + x)^a`  
     - :math:`1 + ax + \frac{a(a-1)}{2!}x^2 + \frac{a(a-1)(a-2)}{3!}x^3 + \cdots`  
     - :math:`|x| < 1`
   * - :math:`ln(x+\sqrt{x^2+1})`  
     - :math:`x- \frac{1}{6}x^3 +\frac{3}{40}x^5 - \frac{5}{112}x^7 + \cdots`  
     - :math:`|x| \leq 1`

.. tip:: 记忆技巧 & 如何食用

    记忆技巧：
    
    :math:`e^x`  ：全部为正，分母是阶乘

    :math:`\sin x`  ：奇数次幂、正负交替

    :math:`\cos x`  ：偶数次幂、正负交替

    :math:`\ln(1+x)`  ：交替项，分母是自然数

    :math:`\arctan x`  ：奇次幂，正负交替

    :math:`(1+x)^a`  ：二项展开的一般形式

    使用方法：
    
    取前几项作为近似值；高阶项可视为 :math:`o(x^n)`   无穷小，常用于极限计算。

    在计算中，幂函数留下，不是幂函数展开成幂函数

    到底精确到几次方？
    
    :math:`\frac{A}{B}` 型 看分母几次，就展开到几次

    :math:`A-B` 型 最低次幂消不掉为止



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


