## base运算

- $A^n$
    - >A不能化简；D中对角线性质也不能用
    - 参
        - $\alpha \beta^T$
        - use结合律，构造 前单**行**后单**列**is数
            - 前单列后单行is i阶矩阵(逆向则可作矩阵分解
    - 具体型:number
        - 多个1
            - 拆为$E+B$
                - ${E+B}^n$
                    - $E^n$+$nE^{n-1}B$+$\frac{n(n-1)}{2!}E^{n-2}B^2$+$\frac{n(n-1)(n-2)}{3!}E^{n-3}B^3$+...+$B^n$
                        - $B^k=O,(k \ge 3$←$B$为上三角
       - 先算$A^2$，checkif can得E'倍数
            - written as 4E
                - 分n=2k，2k+1 discuss
                    - $4^{2k/2}E$
                    - $4^kE*A$=$4^kA$
---
- 正交 
    - ..单位vector: ${\mathbf\beta}^o$
        - 与$\alpha_1$、$\alpha_2$都正交
            - 设${\mathbf\beta}$与$\alpha$同形
                - ${\mathbf\beta}=[x_1,x_2,x_3]$
            -list方程，求具体element←分别点乘=0
                - $({\mathbf\alpha_1},{\mathbf\beta})=0$
                - $({\mathbf\alpha_2},{\mathbf\beta})=0$
            - ${\mathbf\beta}^o=\frac{±\mathbf\beta}{||\mathbf\beta||}$
        - 施密特
            - 标准正交向量组
                - 令${\mathbf\beta_1}=\mathbf\alpha_1$
                    - 求$\mathbf\beta_2$
                        
        
## $A^{-1}$
- num
    - $A^{-1}=\frac{1}{|A|}A*$
        - >阶<3适用；验证|A|≠0
        - 代数余子式contain符号：$A_{ij}({-1})^{i+j}M_{i+j}$
            - 区别：D按行/列展开
                - $a_{ij}*A_{ij}$
        - $A*$内部 余子式行列互换
            - 每一步count写尽(包括2阶D计算
    - $[\begin{array}{c:c} A&E \end{array}]$→$[\begin{array}{c:c} E&A \end{array}]$
        - >no need check |A|
            - 化简时，先写确定行
                - E行跟着走
            - 自验：$AA^{-1}=E$
                - (左右乘可换
- 抽象
    - $AA^{-1}=E$
        - utilize已知条件，变形为要求表达式
            - 即xB=E
                - 等式2sides同 +$E$，构造定义式
    - $A_{-1}=C_{-1}B_{-1}$ （$A=BC$
        - 分解为若干可逆矩阵'乘积
            - $(A+B)^{-1}$
                - >$A^{-1}+B^{-1}$可逆
                - $A+B=A(B^{-1}+A^{-1})B$
                    - ↑$\color{gray}A(E+A^{-1}B)$
                - ∴$(A+B)^{-1}=A^{-1}(B^{-1}+A^{-1})^{-1}B^{-1}$
                    
- 分块
    - num
        - 主
            - 对应${-1}$
        - 副
            - 分块位置对换${-1}$
    - 抽象
        - prove可逆
            - >内部分块矩阵可逆
            -  $|A|$≠0
        - 求逆
            - $AA^{-1}=E$
                - 设$A^{-1}= \begin{bmatrix} X & Y \\ Z & W \end{bmatrix}$
                - 带入condition等式，求$A^{-1}$中参数
## $A*$


---
---
## 初等A

## A方程

---
---
## $r(A)$
