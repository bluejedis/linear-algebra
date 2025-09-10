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
                    - $E^n+nE^{n-1}B+\frac{n(n-1)}{2!}E^{n-2}B^2+\frac{n(n-1)(n-2)}{3!}E^{n-3}B^3$+...+$B^n$  _←倒写_
                        - $B^k=O,(k \ge 3$←$B$为上三角
       - 先算$A^2$，checkif can得E'倍数
            - written as 4E
                - 分n=2k，2k+1 discuss
                    - $4^{2k/2}E$
                    - $4^kE*A$=$4^kA$
    ---
- 正交 
    - ..单位vector: ${\mathbf\beta}^o$
        - 与 $\alpha_1$ 、 $\alpha_2$都正交
            - ①设 ${\mathbf\beta}$与$\alpha$同形
                - ${\mathbf\beta}=[x_1,x_2,x_3]$
            - ②list方程，求具体element←分别点乘=0
                -  $({\mathbf\alpha_1},{\mathbf\beta})=0$
                -  $({\mathbf\alpha_2},{\mathbf\beta})=0$
                    - 3未知数，2方程← 设其中一个已知，取比例为k
            - ③单位化$\mathbf\beta$
                - ${\mathbf\beta}^o=\frac{±\mathbf\beta}{||\mathbf\beta||}$
        - 施密特
            - 标准正交向量组
                - ①令 ${\mathbf\beta_1}=\mathbf\alpha_1$
                - ②求 $\mathbf\beta_2$
                    - $={\mathbf\alpha_2}-\frac{({\mathbf\alpha_2,\beta_1})}{({\mathbf\beta_1,\beta_1})}{\mathbf\beta_1}$
                - ③单位化 $\mathbf\beta_1$$\mathbf\beta_2$
    ---
- prove
    - 对称
        - $A=A^T$
            - $(E-2\xi\xi^T)^T=E^T-2\xi^T\xi$
                - ↑based on $(A+B)^T=A^T+B^T$
    - $A^2=E$
        - use结合律
    - 正交
        - $AA^T=E$

## $A^{-1}$
- num
- 抽象
- 分块
## $A*$


---
---
## 初等A

## A方程

---
---
## $r(A)$
