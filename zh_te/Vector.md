# ..==表出==，线性相关 //left 互推与证明
- >表出：$k_1\alpha_1+k_2\alpha_2+...+k_s\alpha_s=\beta$
    - 相关：$..=0$ ($k$不全为0
        - ↑ make相关不成立 ←无关
- 相关、表出、无关 ← 互推
    - 相关&表出
        - 不一定 任意均能其余线性表出
            - ![ ](https://bluejedis.github.io/picx-images-hosting/linear/Screenshot_2025-09-12-11-36-28-930_com.microsoft.emmx.canary-edit.491mq45j1k.jpg)
            - ![ ](https://bluejedis.github.io/picx-images-hosting/linear/IMG_20250912_113755.8dx8282zlm.jpg)
    - ..&无关

？一个向量能由other向量线性表出，那么other向量must线性无关的吧？

# 极大线性无关,r
- r
    - >极大线性无关组 中 向量'个数
    - r＜s ($\alpha_1+\alpha_2+...+\alpha_s$)
        - at least 一个由r个vector组成的部分组 linear无关
            - any r个 linear无关vector..与 origin是等价向量组
                - <span style="color:lightgray">同维，不同个</span>
        - any r+1'部分组 all线性无关
   ---
- 求 极大线性无关组/r/..表出
    - num
        - 极大/r
            - ①将各向量组incorporate→矩阵A
                - 初等行变换
            - ② 阶梯形
                - 看哪些组 不能线性表出or |A|≠0
                    - ![ ](https://bluejedis.github.io/picx-images-hosting/linear/Screenshot_2025-09-12-12-41-45-844_com.microsoft.emmx.canary-edit.8s3nt5l9t0.jpg)
                        - 主元：
                            - <span style="color:lightgray">阶梯形matrix中，每一行第一个非0元</span>
           ---
         - ..表出
             - fouded on the before，化为 最简阶梯形
                 - ①prior主元所在列 构成 极大线性无关组
                 - ②count表出'系数
                     - ![image](https://github.com/bluejedis/picx-images-hosting/raw/master/linear/image.86u06v6evg.png)
                     - ![image](https://github.com/bluejedis/picx-images-hosting/raw/master/linear/image.102itj8ftj.png)
                    
# r 证明//left r(A*) & q

- inequation
    - $r(AB) \le \min\\{r(A)r(B)\\}$
        - >分别证$r(AB) \le r(B)$ ..r(A)
        - 设$A_{m×n}B_{n×1}=C$ (B按行分块
            - list elements
            - ↑ AB行向量 均可由B行 ..表出
                - ∴$r(AB) \le r(B)$
                    - ？为什么是≤，能线性表出，不就是等价向量组，r不应该相等吗？
                        - ↑？向量组中any 向量，can被另一向量组线性表出，则$r≤r_{另一}$ ？结论怎么来的
                            - ![IMG_20250912_134001](https://github.com/bluejedis/picx-images-hosting/raw/master/linear/IMG_20250912_134001.5c1c14gfjp.jpg)
        ---
    - $r(A+B) \le r([A,B]) \le r(A)+r(B)$
        - 按列分块
            - l inequations
                - A+B可由[A,B]线性表出
                    - 由上知：$r(A+B) \le r([A,B])$
            - r .. :
                - ?怎么显然出来的
                    - ![IMG_20250912_135331](https://bluejedis.github.io/picx-images-hosting/linear/IMG_20250912_135331.8vn9qxy6ei.jpg)
    - --
- A*
    - r(A*)
        - 从A变换 angle
        - 解向量
---
# 
# 等价向量组，等价矩阵 //left：2题 back再看一下
- vector组 等价
    - >can线性表出 each other(同维，not necessarily同个数
    - 抽象
    - 具体
    ---
- 等价matrix
    - >同型；can初等变换到another
        - discuss parameter取何值，A B等价
            - ？为什么要写为增广matrix，再化为阶梯形？why 这样 
            - 用两个增广matrix的r 
                - 分类讨论

---
# vector space
- 求过渡矩阵
    - 谁→谁
        - 就是 谁'逆矩*谁的矩
        - ![Screenshot_2025-09-12-14-32-18-457_com](https://bluejedis.github.io/picx-images-hosting/linear/Screenshot_2025-09-12-14-32-18-457_com.microsoft.emmx.canary-edit.1apcms5273.jpg)
        - --
- 求 新基下'ordinate
    - 设为x
        - ![Screenshot_2025-09-12-14-35-54-140_com](https://bluejedis.github.io/picx-images-hosting/linear/Screenshot_2025-09-12-14-35-54-140_com.microsoft.emmx.canary-edit.5j4jwm4269.jpg)=  ![Screenshot_2025-09-12-14-35-28-904_com](https://bluejedis.github.io/picx-images-hosting/linear/Screenshot_2025-09-12-14-35-28-904_com.microsoft.emmx.canary-edit.8dx82ej90p.jpg)
    - 解x
        - 左乘$A^{-1}$
      

//left: 整理 抽象 表达式/相关性
- 设参
- 等价
思路
