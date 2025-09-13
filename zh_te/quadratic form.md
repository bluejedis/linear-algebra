# 标准形
>only 二次
- 配方法
    - 化为规范形
    >系数only±1,0
- 正交变换
    - >only can化规范
    - 写 矩阵(对称
        - >勿漏项
    - ①求$\lambda$ $\xi$ ← 标准形即 $\lambda_1y_1^2 + \lambda_2y_2^2 + \lambda_3y_3^2+...$
    - ②求$\eta_i°$
        - 标准正交化(施密特)
            - ${\mathbf\eta_1}={\mathbf\xi_1}$
            - ${\mathbf\eta_2}={\mathbf\xi_2}-\frac{({\mathbf\xi_2,\eta_1})}{({\mathbf\eta_1,\eta_1})}{\mathbf\eta_1}$
                - ？为什么题中直接$\xi_3=\eta_3$ ← 施密特正交的适用条件是什么？
                    - ![Screenshot_2025-09-13-11-44-06-356_com](https://bluejedis.github.io/picx-images-hosting/linear/Screenshot_2025-09-13-11-44-06-356_com.microsoft.emmx.canary-edit.77dwv22wc7.jpg)
                    - ![Screenshot_2025-09-13-10-52-35-047_com](https://bluejedis.github.io/picx-images-hosting/linear/Screenshot_2025-09-13-10-52-35-047_com.microsoft.emmx.canary-edit.7axisrvz4n.jpg)
        - 单位化
            - ${\mathbf\eta_i°}=\frac{{\mathbf\eta_1}}{ \lvert\lvert{\mathbf\eta_1}\rvert\rvert}$
    - ③写Q,正交变换为$x=Qy$
        - ![IMG_20250913_120527](https://bluejedis.github.io/picx-images-hosting/linear/IMG_20250913_120527.7eh4qier68.jpg)
# 合同
>$C^TAC=B$
- 判定
    - >惯性定理
        - **标准**/规范形下
            - 正项p，负项q不变 ← r=p+q
    - >合同充要condition
        - p、q相同 ← or r同，p or q同
        - ↑ 直接看 算出来的$\lambda$ 
# 正定
$x^TAx ＞ 0$
- 具体
    - 看$\lambda$
        - 求解$|\lambda E-A|$
        - all $\lambda$＞ 0
  
     - or: 各阶顺序主子式 ← <span style="color:lightgray">选择题can看排</span> 求 参数取值use
        - whether全＞0
        - ？<span style="color:lightgray">正定二次型中，矩阵元素一定不为负吗？不一定吧？书上说法不准确吧？← 好像一定？$x^TAx ＞ 0$，就是A＞0？</span>
            - ![Screenshot_2025-09-13-12-26-33-140_com](https://bluejedis.github.io/picx-images-hosting/linear/Screenshot_2025-09-13-12-26-33-140_com.microsoft.emmx.canary-edit.361xgpfm7m.jpg)
- 抽象
    - A正定的充要条件( A实对称
        - $A^{-1}$正定
