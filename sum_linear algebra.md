# **01** <span style="color:#75c940;">**行列式**</span>

<ul>

## **0 行列式的<span style="background-color:#ffff26;">定义</span>与<span style="background-color:#ffff26;">性质**</span>

<ul>

### **(1)**<span style="color:#75c940;"> </span><span style="color:#ffaf38;">**本质**</span>**定义（第一种定义）**

<ul>

- n维向量所围成的 <span style="color:#797ec9;">V</span>

</ul>

### <span style="color:#3da8f5;">**性质**</span>

<ul>

1.  拆、提
    - 拆<span style="color:#797ec9;">a+b</span>
    - 提<span style="color:#797ec9;">k</span>
2.  <span style="color:#3da8f5;">值</span>
    - \- (反号)
        - a line/column  ←→ b line/column
    - = (不变)
        - A = $A^T$​​​
        - △b line += K \* a line (K可取 正、负、0)//行列式化简常用
    - |A| = 0
        - | 0 0 0| or $| 0 0 0|^T$​​​​​​​​​​
        - a line /column = K \* b line/column

</ul>

### **(2)**<span style="color:#3da8f5;">**逆序数法**</span>**定义（第二种定义）**

<ul>

1.  A.<span style="color:#797ec9;">逆序</span>：
    - <span style="color:#797ec9;">一个</span>逆序：
        - $a,...,b$​​​​​​​
        - $a>b$​​​
        - 则 a,b 这两个数构成一个 ~
    - 例
        ![](https://api2.mubu.com/v3/document_image/af77239c-f040-4685-a0ee-834a6f9e6f7f-15201174.jpg)
2.  B.<span style="color:#797ec9;">排列</span>：
    - <span style="color:#3da8f5;">有序</span><span style="background-color:#ffff26;">数组</span>
        - ![](https://api2.mubu.com/v3/document_image/4841fcdc-ea2f-41fd-af74-d87b969a58ba-15201174.jpg)

</ul>

#### **(3)**<span style="color:#75c940;">**展开定理**</span>**（第三种定义）**

<ul>

1.  A.<span style="color:#3da8f5;">余子式</span>$M_{ij}$​​​​​​
    - <span style="color:#75c940;">去掉</span>$a_{ij}$​​​​​​ 所在的 第i行，第j列元素
    - 剩下的元素按 原 位与序组，成<span style="color:#3da8f5;">n-1</span>阶行列式
    - 称为元素$a_{ij}$​​​​​​的余子式，记作$M_{ij}$​​​​​​
2.  B.<span style="background-color:#ffff26;">代数</span><span style="color:#3da8f5;">余子式</span>$A_{ij}$​​​​​​
    - //带有符号 的余子式
    - $A_{ij}$=<span style="color:#3da8f5;">$(-1)^{i+j}$</span>​​​​​​​​​​ $M_{ij}$​​​​​​
3.  C.按行/列展开 $|A|$​​​
    - //<u>某 行/列</u> 元素$a_{ij}$​​​​​​ 分别<span style="background-color:#ffff26;">乘以</span> 其$A_{ij}$​​​​​​ 再<span style="color:#3da8f5;">累加</span>
    - $|A|$​​​
        - ![](https://api2.mubu.com/v3/document_image/b1cdd50c-32c5-4846-81b7-94de2286fe14-15201174.jpg)
    - <span style="color:#3da8f5;">性质</span>
        - $i$​行/$j$​列元素 乘以 $i+k$​​​/$j+k$​​​ (k≠0)元素 再求和 = 0

</ul>

### **△4类重要的行列式**

<ul>

#### **A.**<span style="background-color:#ffff26;">**对角**</span>**线：**

<ul>

##### **1)**<span style="color:#797ec9;">**主**</span><span style="background-color:#ffff26;">**对角**</span>**线 行列式**

<ul>

- ![](https://api2.mubu.com/v3/document_image/789dffb0-d59a-41fd-a0af-4d5919f0c677-15201174.jpg)
- ![](https://api2.mubu.com/v3/document_image/5e69bf10-7f38-4601-89c0-496ca98394e8-15201174.jpg)
- ![](https://api2.mubu.com/v3/document_image/751b19d1-446e-40be-9f59-5e1397722d33-15201174.jpg)
- 取值都等于
    - ![](https://api2.mubu.com/v3/document_image/1db695ed-77f5-484d-b1f0-e0b765b727c2-15201174.jpg)

</ul>

##### **2)**<span style="color:#3da8f5;">**副**</span>**对角线 行列式**

<ul>

- ![](https://api2.mubu.com/v3/document_image/a4fd60f9-973b-4d58-b7b3-b243ec2dc854-15201174.jpg)
- ![](https://api2.mubu.com/v3/document_image/9d84fedc-97ff-4e46-935a-4c9cf8a6e864-15201174.jpg)
- ![](https://api2.mubu.com/v3/document_image/cf5d337b-a2d5-43fe-82ef-fcac8088275b-15201174.jpg)
- 值都等于 <span style="color:#3da8f5;">$(-1)^\frac{n(n-1)}{2}$</span>​​​​​​​​​​​​​​​​​​​​​<span style="color:#3da8f5;"> </span>副对角线元素 <span style="background-color:#ffff26;">累乘</span>

</ul>

</ul>

### **B.**<span style="color:#3da8f5;">**拉普拉斯**</span>** **<u>展开式</u>**

<ul>

- $A$​为m阶矩阵，$B$​为n阶矩阵

#### **1)**<span style="background-color:#ffff26;">**主**</span>**对角线**

<ul>

- ![](https://api2.mubu.com/v3/document_image/a8f07bb7-1ae8-4bc5-8d74-116eac3ab8b7-15201174.jpg)
- ![](https://api2.mubu.com/v3/document_image/41a2d53c-d62d-4c4b-b5f9-38b758ba7362-15201174.jpg)
- ![](https://api2.mubu.com/v3/document_image/e8f9ea76-6aaa-4438-9089-0fc8432ffaa4-15201174.jpg)
- 值都等于 $|A||B|$​​​​​​

</ul>

#### **2)**<span style="color:#3da8f5;">**副**</span>**对角线**

<ul>

- ![](https://api2.mubu.com/v3/document_image/020cdb9e-fe64-45a0-ad32-757fa3ae3a6f-15201174.jpg)
- ![](https://api2.mubu.com/v3/document_image/87044573-46f7-4f03-9808-4e06d98e6ca4-15201174.jpg)
- ![](https://api2.mubu.com/v3/document_image/6f8efbae-2929-40ed-a0c8-423cb41a7c62-15201174.jpg)
- 值都等于<span style="color:#3da8f5;">$(-1)^{mn}$</span>​​​​​​​​​ $|A||B|$​​​​​​

</ul>

#### **C.**<span style="color:#75c940;">**范德蒙德**</span>** 行列式**

<ul>

- 形如
    - ![](https://api2.mubu.com/v3/document_image/5e5dc993-49e5-480e-bca8-69042f3cf6c1-15201174.jpg)
    - 元素升幂 排列
- 值= 一次幂 行向量中 相邻元素作差 的<span style="background-color:#ffff26;">累乘</span>
    - ![](https://api2.mubu.com/v3/document_image/25aae829-4bba-46a7-9658-10a9698439be-15201174.jpg)

</ul>

</ul>

</ul>

## **1 行列式的** *<u>计算</u>*

<ul>

1.  具体型
    - 化为基本形
    - 递推法
    - 行列式表示的函数和方程
2.  抽象型
    - 用性质
    - 用公式IABI=IAIIBI

</ul>

## **2 余子式与代数余子式的** *<u>计算</u>*

<ul>

</ul>

</ul>

# **02** <span style="color:#3da8f5;">**矩阵**</span>

<ul>

## **0 矩阵的<span style="background-color:#ffff26;">定义</span>及其<u>基本</u><span style="color:#3da8f5;"><u>运算</u></span>**

<ul>

### **(1) <span style="background-color:#ffff26;">定义</span>**

<ul>

#### **A.矩阵**

<ul>

1.  1)基本定义
    - 形如
        - ![](https://api2.mubu.com/v3/document_image/502d1d89-9c3f-4ef8-95b0-242bbb1bfb19-15201174.jpg)
    - 矩阵 由 若干 行/列向量组成
2.  2)n阶方阵
    - m=n
3.  3)同型矩阵
    - 行 列对应相等

</ul>

#### **B.矩阵的<span style="color:#75c940;">秩</span>$r(A)$**

<ul>

1.  **1)定义**
    - a.$A_{m×n}$​​​​​​​ 的 <u>最高阶</u>**非零**<span style="color:#3da8f5;">子式</span> 的<span style="background-color:#ffff26;">阶数</span><span style="background-color:#ffff26;"> </span>=矩阵$A$​ 的秩
        - 记为$r(A)$​​​​
        - <u>最高阶</u>**非零**<span style="color:#3da8f5;">子式</span>
            - a.理解
                - 子式：从矩阵中任意选取一部分元素组成的方阵
                - 非零子式：行列式值不为0的式子
                - 最高阶：行数 和 列数 最高
            - b.求法
                - 将矩阵 化简为 最简 阶梯型
    - b.存在k阶子式 ≠零，任意k+1阶子式=0 → $r(A)=k$​​​​​​
        - 且$r(A_{n×n})=n$​​​​​​​​​​​​ ←→|A|≠0 ←→ $A$​可逆
    - c.本质是 组成该矩阵的<span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">无关</span>的向量的个数
2.  **2)性质**
    - a.初等变换 不改变 $A$​ 的 <span style="color:#75c940;">r</span>
        - $A$​是m×n矩阵，$P,Q$​​​ 分别为m阶、n阶可逆矩阵
        - $r(A_{m×n})$​​​​​​​​​​=$r(P_{m×m}A_{m×n})$​​​​​​​​​​​​​​​​​=$r(A_{m×n}Q_{n×n})$​​​​​​​​​​​​​​​​​ =$r(P_{m×m}A_{m×n}Q_{n×n})$​​​​​​​​​​​​​​​​​​​​​​​​
    - b. $A$​是m×n矩阵，$B$​ 是满足相关要求的矩阵
        - ①单$A$​
            - ![](https://api2.mubu.com/v3/document_image/d0792895-af6b-4d3e-a4a5-649314e14cdd-15201174.jpg)
            - ![](https://api2.mubu.com/v3/document_image/46036767-49a0-4c5e-afda-380e3f50b50f-15201174.jpg)
            - ![](https://api2.mubu.com/v3/document_image/a023cb81-247a-465b-8850-50bc15c5dc18-15201174.jpg)
        - ②$A$​与$B$​
            - ![](https://api2.mubu.com/v3/document_image/be1654ce-0c2b-41e1-958a-f0ee15a75f01-15201174.jpg)
            - ![](https://api2.mubu.com/v3/document_image/001afb7e-9a9b-4478-85ee-8aadb0670b0b-15201174.jpg)

</ul>

</ul>

### **(2) <u>基本</u><span style="color:#3da8f5;"><u>运算</u></span>**

<ul>

#### **O.basic**

<ul>

1.  相等
    - 同型矩阵，且 对应元素都相等
        - ![](https://api2.mubu.com/v3/document_image/9c08f6fb-6b96-4e2e-b896-8c9d52f994bc-15201174.jpg)
            - 需
                ![](https://api2.mubu.com/v3/document_image/c6718612-33a3-425e-a28b-56e67cc75ea5-15201174.jpg)
2.  加法
    - 两矩阵为 <u>同型矩阵</u>时 ，对应元素进行相加
    - 矩阵 加法的 交换 结合律
        - ![](https://api2.mubu.com/v3/document_image/c79fac54-c861-4f9a-b944-054a632116e4-15201174.jpg)

</ul>

#### **A. 数乘 | 矩阵乘法 | **$A^T$** **

<ul>

1.  <span style="color:#3da8f5;">数</span><span style="color:#75c940;">乘</span>矩阵
    - $A$​的每个元素 都乘以k
    - △数乘 和 加法 统称为矩阵的 <span style="background-color:#ffff26;">线性</span>运算
        - 数乘 满足 数的 分配、结合律
            - 分配
                ![](https://api2.mubu.com/v3/document_image/77bebe0a-0fdf-4e33-8b89-cd0406b78fd8-15201174.jpg)
            - 结合
                ![](https://api2.mubu.com/v3/document_image/450a50ed-2d59-4b03-9662-6d184108a181-15201174.jpg)
                - k l为任意常数
            - ![](https://api2.mubu.com/v3/document_image/8737cf9f-a439-48ae-86b0-eb4d0b29ba70-15201174.jpg)
    - △用n阶方阵$A$​ 计算行列式 时，记为$|A|$​​​
        - $|kA|=k^n|A|$​​​​​​​​​​​
2.  矩阵的<span style="color:#75c940;">乘</span>法
    - 前行×后all列
    - 规律
        - 结合
            ![](https://api2.mubu.com/v3/document_image/cbac6cff-29ea-4bcb-8414-80490dbe5f5e-15201174.jpg)
        - 分配
            ![](https://api2.mubu.com/v3/document_image/327dc63c-60d9-41cc-b2b4-bc34f16c2b81-15201174.jpg)
        - 两 矩阵 一般不满足 交换律，因为左右乘 值 与 含义不同
3.  转置矩阵**$A^T$**
    - $A_{m×n}$​​​​​​​ 转置为 $A_{n×m}$​​​​​​​ //行列互换
    - <span style="background-color:#ffff26;">规律</span>
        - $A$​ 本身
            - $(A^T)^T=A$​​​​​​​​​
            - $(kA)^T=kA^T$​​​​​​​​​​​
            - ![](https://api2.mubu.com/v3/document_image/8a3ea687-02c3-440f-a155-2fabef2740e2-15201174.jpg)
                - 行列式 行列互换 值不变
        - $A$​和$B$​
            - $(A+B)^T$​​​​​​​ = $A^T+B^T$​​​​​​​
            - <span style="color:#3da8f5;">$(AB)^T$</span>​​​​​​<span style="color:#3da8f5;"> =</span><span style="color:#3da8f5;">$B^TA^T$</span>​​​​​​
                ![](https://api2.mubu.com/v3/document_image/e174cc1d-3855-4231-8997-5a6c81dd36e3-15201174.jpg)

</ul>

#### **B.△<u>向量</u>的 <span style="background-color:#ffff26;">内积</span>与<span style="color:#75c940;">正交</span> | <span style="color:#3da8f5;">施密特</span><span style="color:#75c940;">正交化</span>**

<ul>

1.  1)向量的<span style="background-color:#ffff26;">内积</span>与<span style="color:#75c940;">正交</span>
    - a.内积
    - b.正交
2.  2)<span style="color:#3da8f5;">施密特</span><span style="color:#75c940;">正交化</span>

</ul>

#### **C.矩阵的<span style="background-color:#ffff26;">幂 </span>| 方阵乘积 的<u>行列式</u>**

<ul>

1.  矩阵的<span style="background-color:#ffff26;">幂</span>
    - $A^m$​​​ (m个$A$​ 相乘)
    - 规律(不可交换)
        - $(AB)^m$​​​​​​ =$(AB)(AB)…(AB)$​​​​​​​​​​​​​ ≠$A$​ $B$​ 的分别幂//不可交换
        - ![](https://api2.mubu.com/v3/document_image/d2473e89-f3b2-4b58-8505-389c1cb6ae07-15201174.jpg)
        - ![](https://api2.mubu.com/v3/document_image/5603ae83-f3d2-4637-a8af-a87e2d60520a-15201174.jpg)
        - ![](https://api2.mubu.com/v3/document_image/61db6187-a382-4914-9d30-2521ab0ca4e2-15201174.jpg)
2.  若 $f(x)=a_0+a_1x+…+a_mx_m$​​​​​​​​​​​​​​​​​​​​​​
    - 则 $f(x)=a_0E+a_1A+…+a_mA_m$​​​​​​​​​​​​​​​​​​​​​​​
3.  方阵乘积的**行列式**
    - $A,B$​​​ 是同阶方阵
    - 则 $|AB|$​​​​=$|A|$​​​ $|B|$​​​

</ul>

</ul>

### **△.<span style="color:#3da8f5;">特殊</span>矩阵**

<ul>

#### **1)<span style="background-color:#ffff26;">basic</span>**

<ul>

- $O$​
- $E$​
- $kE$​​
- $Λ$​

</ul>

#### **2)<span style="background-color:#ffff26;">对称</span> | <span style="color:#75c940;">正交</span>**

<ul>

- $A^T=A$​​​​​
- $A^T=-A$​​​​​​
    - <span style="color:#75c940;">反</span>对称矩阵
- $A^TA=E$​​​​​​
    - 正交矩阵
        - $A$​是由 两两正交的单位向量组(规范正交基) 组成
        - ![](https://api2.mubu.com/v3/document_image/705f5598-1df0-4834-9af3-550cf0d1f0bb-15201174.jpg)
        - ![](https://api2.mubu.com/v3/document_image/7c7ba9e4-d393-4d1d-a0a5-ef3d846fd7f1-15201174.jpg)
        - ![](https://api2.mubu.com/v3/document_image/2270fd79-e911-4d31-a851-c5b5a271f7fb-15201174.jpg)

</ul>

#### **3)<span style="background-color:#ffff26;">分块</span>矩阵**

<ul>

1.  a.定义
    - 将矩阵分成若干小块
    - 每一块称为原矩阵的<span style="color:#3da8f5;">子块</span>
    - 将子块看作原矩阵的一个元素
2.  b.基本运算(以2×2为例)
    - 按照一般矩阵运算规则进行运算即可
        - ![](https://api2.mubu.com/v3/document_image/12800c7c-7769-4090-8fea-6499ede64859-15201174.jpg)
        - 对于 乘法，子块内部 矩阵不变 //由外到内
        - 分块对角矩阵的幂
            - ![](https://api2.mubu.com/v3/document_image/018dc37f-9d32-4fe2-8d9f-e65d2b05e406-15201174.jpg)

</ul>

</ul>

</ul>

## **1 矩阵的<span style="color:#75c940;">逆</span>$A^{-1}$​​ |  <span style="color:#3da8f5;">伴随</span>矩阵$A^{*}$​​​**

<ul>

### **(1)矩阵的<span style="color:#75c940;">逆</span>$A^{-1}$​​​​​​**

<ul>

1.  A.<span style="background-color:#ffff26;">定义</span>
    - 1)<u>基本</u>定义
        - $A,B$​​​是n阶方阵，E是n阶单位矩阵
        - <span style="color:#3da8f5;">$AB=BA=E$</span>​​​​​​​
        - 称
            - $A$​ 是可逆矩阵
            - <span style="color:#3da8f5;">$B$</span>​是$A$​的<span style="color:#75c940;">逆</span><span style="color:#3da8f5;">矩阵</span>
                - 逆矩阵是唯一的
                    - 记为
                        - $A^{-1}$​​​​​​
    - 2)$A$​可逆的<span style="background-color:#ffff26;">充要</span><span style="color:#3da8f5;">条件</span>
        - <span style="color:#3da8f5;">$|A|≠0$</span>​​​​​
            - 此时 $A$​可逆 ，且
            - $A^{-1}$​​​​​​=
                - ![](https://api2.mubu.com/v3/document_image/d776502d-a91b-48a9-82b8-7f293090acdd-15201174.jpg)
2.  B.<span style="background-color:#ffff26;">性质</span>与<span style="color:#3da8f5;">公式</span>
    - 设 $A,B$​​​是同阶可逆矩阵
        - 1)单$A$​
            - ![](https://api2.mubu.com/v3/document_image/2a56624d-249b-4cd3-8e6e-75b12614eae5-15201174.jpg)
            - ![](https://api2.mubu.com/v3/document_image/1b615d1b-f240-4f51-b40c-1d5906085b5c-15201174.jpg)
                - 穿衣原则：无论哪件衣服在外，都是那个人
            - ？行列式 还能求逆？
                ![](https://api2.mubu.com/v3/document_image/825123f1-7499-41b6-ade8-d6060dca3a67-15201174.jpg)
        - 2)$A$​与$B$​
            - ![](https://api2.mubu.com/v3/document_image/ac1dc179-eedd-4691-8874-dbdb43928e66-15201174.jpg)
                - A+B不一定可逆
                    - ![](https://api2.mubu.com/v3/document_image/b4186341-9b80-49c5-8437-8d8cd10af763-15201174.jpg)
3.  C.用定义<u>求</u>逆矩阵$A^{-1}$​​​​​​
    - 1)<u>直接</u>求$A^{-1}$​​​​​​
        - 令$AA^{-1}=E$​​​​​​​​​
    - 2)分解为 若干个可逆矩阵 的<span style="color:#75c940;">积</span>
        - 令$A=BC$​​​​
        - ![](https://api2.mubu.com/v3/document_image/8d0350cc-5f9b-418c-a1b9-1b1a22eb858f-15201174.jpg)
    - 3)<span style="background-color:#ffff26;">分块</span>矩阵的逆
        - ![](https://api2.mubu.com/v3/document_image/f1328def-c616-4fff-92da-129b12de2b2a-15201174.jpg)

</ul>

### (2)<span style="color:#3da8f5;">伴随</span>矩阵$A^*$​​​

<ul>

1.  A.<span style="background-color:#ffff26;">定义</span>
    - 将$n^2$​​​个元素的代数余子式 按次序排列成矩阵
        - ![](https://api2.mubu.com/v3/document_image/a89f8f76-2f55-4084-861c-55e2d765c85a-15201174.jpg)
    - 称为$A$​的伴随矩阵
        - 注意：
            - 定义矩阵A是**方阵**。
            - **余子式**：伴随矩阵的每个元素的余子式是除去当前元素行列，剩下的元素构成的行列式。
            - **代数余子式**：取行列式的值，符号由当前行标和列标的值决定（-1的i+j次幂）。
            - **位置关系**为转置
    - 有 $AA^*=A^*A=|A|E$​​​​​​​​​​​​​​
2.  B.*<span style="background-color:#ffff26;">性质</span>与<span style="color:#3da8f5;">公式</span> //待补充
3.  C.用伴随矩阵求逆矩阵
    - ![](https://api2.mubu.com/v3/document_image/6f1a8835-2b82-40fe-9b7d-0963bb7c0226-15201174.jpg)

</ul>

</ul>

## **2 <span style="background-color:#ffff26;">初等</span><span style="color:#75c940;">变换</span>与<span style="background-color:#ffff26;">初等</span><span style="color:#3da8f5;">矩阵</span>**

<ul>

1.  (1)<span style="background-color:#ffff26;">初等</span><span style="color:#75c940;">变换</span>
    - 倍乘
    - 互换
    - 倍加
2.  (2)<span style="background-color:#ffff26;">初等</span><span style="color:#3da8f5;">矩阵</span>
    - a.定义
        - i.单位矩阵<span style="color:#3da8f5;">$E$</span>​经过<span style="background-color:#ffff26;">一次</span> 初等变换 得到的矩阵
        - ii.运算
            - 倍乘~
                - ![](https://api2.mubu.com/v3/document_image/8609dd18-1e31-4760-a0c3-9f631605b94d-15201174.jpg)
            - 互换~
                - ![](https://api2.mubu.com/v3/document_image/7e26d88c-be85-4ff4-8c0f-79b995d30ccb-15201174.jpg)
            - 倍加~
                - ![](https://api2.mubu.com/v3/document_image/b9ed39b3-f373-42cc-a0a9-b36a1657bd46-15201174.jpg)
    - b.*性质与<span style="color:#3da8f5;">公式 </span> // *表示待补充
    - c.△用初等变换（初等矩阵）<span style="color:#75c940;">求</span><span style="color:#3da8f5;">逆矩阵</span>
        - ![](https://api2.mubu.com/v3/document_image/62a07e87-a56a-4478-a74a-fdfbf29e098d-15201174.jpg)

</ul>

## **3 <span style="color:#75c940;">等价</span><span style="color:#3da8f5;">矩阵</span> <span style="color:#3da8f5;">矩阵</span>的<span style="color:#75c940;">等价</span><u>标准形</u> | <span style="color:#3da8f5;">矩阵</span><span style="background-color:#ffff26;">方程</span>**

<ul>

1.  A.<span style="color:#75c940;">**等价**</span><span style="color:#3da8f5;">**矩阵**</span>
    - $A,B$​​​均是m×n矩阵 ，$P_{m×m}$​​​​​​​ ，$Q_{n×n}$​​​​​​​ 是可逆矩阵
    - 使得 $P_{m×m}A_{m×n}Q_{n×n}=B_{m×n}$​​​​​​​​​​​​​​​​​​​​​​​​​​​​​
    - 称$A,B$​​​是<span style="color:#75c940;">等价</span>矩阵
        - 记作
            ![](https://api2.mubu.com/v3/document_image/ba2a3788-963a-41ee-b1bf-eb2b2af281bf-15201174.jpg)
2.  B.<span style="color:#75c940;">**等价**</span><u>**标准形**</u>
    - 形如
        - ![](https://api2.mubu.com/v3/document_image/f0f26d91-bdce-4fb2-96e1-24c02cb37b55-15201174.jpg)
            - <span style="color:#75c940;">**等价**</span><u>**标准形**</u>唯一
            - r = r(A)
                - 即 若r(A)=r则存在可逆矩阵P,Q，使得
                    - ![](https://api2.mubu.com/v3/document_image/9f48d432-636a-4597-b579-6fc2bbd9371d-15201174.jpg)
3.  C.<span style="color:#3da8f5;">**矩阵**</span><span style="background-color:#ffff26;">**方程**</span>
    - $AX=B$​​​​
    - $XA=B$​​​​
    - $AXB=C$​​​​​

</ul>

</ul>

# **03** <span style="background-color:#ffff26;">**向量**</span>

<ul>

## **0 <span style="background-color:#ffff26;">向量</span> | <span style="background-color:#ffff26;">向量</span><span style="color:#3da8f5;">组</span>的<u>线性</u>相关性**

<ul>

### **(1)<u>概念</u>**

<ul>

#### **A.向量**

<ul>

1.  1)n维向量：
    - n个数 构成的 有序数组
2.  2)运算
    - 相等：对应元素都相等
    - 加法：
        - 对应相加即可
            - ![](https://api2.mubu.com/v3/document_image/74000468-035e-4526-9d82-36a419599322-15201174.jpg)
    - 数乘：
        - ![](https://api2.mubu.com/v3/document_image/30333a7a-97ab-49d6-9eda-c76196ccba14-15201174.jpg)

</ul>

#### **B.<span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span> 与 <span style="background-color:#ffff26;">线性</span><span style="color:#3da8f5;">相关</span>**

<ul>

1.  0)线性组合
    - 针对 一组向量组而言
        - m个n维向量$α_1,…,α_m$​​​​​​​​​，m个数$k_1,…,k_m$​​​​​​​​​
        - 形如
            - ![](https://api2.mubu.com/v3/document_image/455dbfb1-10bd-4839-9aff-18278c14cafb-15201174.jpg)
        - 称 其为 向量组 的 <span style="background-color:#ffff26;">线性</span>组合
2.  1)<span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
    - 一个向量+一组向量组
        - 向量<span style="color:#3da8f5;">$β$</span>​ 能 <span style="color:#75c940;">表示成 </span>n维向量$α_1,…,α_m$​​​​​​​​​ 的 <span style="color:#3da8f5;">线性组合</span>
        - 形如
            - ![](https://api2.mubu.com/v3/document_image/a041036f-d874-4e4a-a757-b89d4793d77b-15201174.jpg)
        - 称 向量<span style="color:#3da8f5;">$β$</span>​ 能 被<span style="color:#75c940;"> </span>n维向量$α_1,…,α_m$​​​​​​​​​ <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
3.  2)<span style="background-color:#ffff26;">线性</span><span style="color:#3da8f5;">相关</span>
    - 针对 <span style="color:#3da8f5;">一组</span>向量组而言 //拆一个 就是<span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
        - a.相关
            - m个n维向量$α_1,…,α_m$​​​​​​​​​ , 若<span style="color:#3da8f5;">存在</span>一组不全为零的数$k_1,…,k_m$​​​​​​​​​
            - 使得 线性组合为0
                - 即
                    ![](https://api2.mubu.com/v3/document_image/d5664ece-3486-4bd6-b046-08e47d1d4472-15201174.jpg)
            - 称 向量组$α_1,…,α_m$​​​​​​​​​ 线性相关
                - 含 0向量 or 成比例的 向量组必 <span style="background-color:#ffff26;">线性</span><span style="color:#3da8f5;">相关</span>
        - b.无关
            - m个n维向量$α_1,…,α_m$​​​​​​​​​ , <span style="color:#75c940;">不</span><span style="color:#3da8f5;">存在</span>一组不全为零的数$k_1,…,k_m$​​​​​​​​​
                - 使得 线性组合为0
                    - 即
                        ![](https://api2.mubu.com/v3/document_image/d5664ece-3486-4bd6-b046-08e47d1d4472-15201174.jpg)
            - 称 向量组$α_1,…,α_m$​​​​​​​​​ 线性<span style="color:#75c940;">无</span><span style="color:#3da8f5;">关</span>
                - 即 <span style="color:#75c940;">单</span>个非0向量，两个<span style="color:#75c940;">不</span><span style="color:#3da8f5;">成比例</span>的向量均 线性无关

</ul>

</ul>

### **(2)<span style="color:#75c940;">判别</span> <span style="background-color:#ffff26;">线性</span><span style="color:#3da8f5;">相关</span>**

<ul>

#### **A.单$α$​**

<ul>

1.  向量组$α_1,…,α_m$​​​​​​​​​
    - 1)<span style="background-color:#ffff26;">**线性**</span><span style="color:#3da8f5;">**相关**</span> 充要条件
        - ①向量组中 至少有一个向量 可由 <u>其余的</u> **n—1** 个向量 <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
        - ②齐次线性方程组<span style="color:#3da8f5;">$Ax=0$</span><span style="color:#3da8f5;"> </span>，有 <span style="color:#75c940;">非</span><span style="color:#797ec9;">零解</span> 。其中 $A=[α_1,…,α_m]$​​​​​​​​​​​​​
            - 同理，线性无关 的充要 即为 only<span style="color:#797ec9;">零解</span>
            - //针对m个n维向量 $α_1,…,α_m$​​​​​​​​​
                - 其中
                    - ![](https://api2.mubu.com/v3/document_image/b6f64b4c-7245-4093-8e3c-08ae7ca1a6ac-15201174.jpg)
        - ③<u>部分</u>向量 <span style="background-color:#ffff26;">**线性**</span><span style="color:#3da8f5;">**相关**</span> ，整个向量组 <span style="background-color:#ffff26;">**线性**</span><span style="color:#3da8f5;">**相关**</span>

</ul>

#### **B.$α$与$β$**

<ul>

1.  1)<span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
    - a. $β$​可由$α_1,…,α_s$​​​​​​​​​ <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span> 的 <span style="background-color:#ffff26;">充要</span>条件
        - 非齐次方程组 $α_1β_1+…+α_sβ_s=β$​​​​​​​​​​​​​​​​​ 有解
        - $r[α_1,…,α_s]$​​​​​​​​​​​​=$r[α_1,…,α_s,β]$​​​​​​​​​​​​​​
    - b.向量组$β_1,…,β_t$​​​​​​​​​ 可由$α_1,…,α_s$​​​​​​​​​ 线性表示
        - ①t≤s， $β_1,…,β_t$​​​​​​​​​ <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">无</span><span style="color:#3da8f5;">关</span>
        - ②t>s，$β_1,…,β_t$​​​​​​​​​ <span style="background-color:#ffff26;">线性</span><span style="color:#3da8f5;">相关</span>
    - c.$α_1,…,α_s$​​​​​​​​​ 线性<span style="color:#75c940;">无</span><span style="color:#3da8f5;">关 </span>，$β,α_1,…,α_s$​​​​​​​​​​​ <span style="background-color:#ffff26;">线性</span><span style="color:#3da8f5;">相关</span>
        - $β$​ 可由 $α_1,…,α_s$​​​​​​​​​，<span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>，且 表示法唯一

</ul>

</ul>

</ul>

## **1 <span style="color:#797ec9;">极大</span><span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">无</span><span style="color:#3da8f5;">关</span>组 | <u>等价</u>向量组 | 向量组的<span style="color:#75c940;">秩</span>**

<ul>

### **(1)<span style="color:#797ec9;">极大</span><span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">无</span><span style="color:#3da8f5;">关</span>组 - "<u>代表</u>"**

<ul>

#### **A.<span style="background-color:#ffff26;">定义</span>**

<ul>

1.  1)数学定义
    - ①向量组$α_1,…,α_s$​​​​​​​​​ 中存在 <span style="color:#3da8f5;">部分组</span>$α_{i_1},…,α_{i_s}$​​​​​​​​​​​​​​​​​
    - ② 向量组中的 任一向量$α_i$​​​均可由此 部分组 <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
2.  2)理解：
    - a.其 能够代表向量组中 所有成员 的一组向量(彼此<span style="background-color:#ffff26;"> 线性</span><span style="color:#75c940;">无</span><span style="color:#3da8f5;">关</span>)
        - 即 向量组 中的 任一向量都能够由其 <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
        - 线性相关 的 有一组即可
    - b.极大线性无关组 一般不唯一 (线性相关 向量 的选取 不唯一)
    - c.特殊：
        - 只由 一个<span style="color:#3da8f5;">0</span>向量 组成的 向量组 不存在~
        - 一个 <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">无</span><span style="color:#3da8f5;">关</span><u>向量组</u> 的~ 就是其本身

</ul>

#### B.求法

<ul>

</ul>

</ul>

### **(2)<span style="color:#3da8f5;">等价</span>向量组**

<ul>

#### **A.<span style="background-color:#ffff26;">定义</span>**

<ul>

1.  1)基本定义：
    - 设定：
        - 两个向量组(Ⅰ)$α_1,…,α_s$​​​​​​​​​ ，(Ⅱ)$β_1,…,β_t$​​​​​​​​​
    - 若
        - 1)$α$​中 每个向量$α_i$​​​ 均可由$β$​ 中的向量 <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
            - 称 向量组$α$​可由向量组$β$​ <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
        - 2)向量组(Ⅰ)与 向量组(Ⅱ)可相互<span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
            - 称 向量组(Ⅰ)与 向量组(Ⅱ) 是 <span style="color:#3da8f5;">等价</span> <u>向量组</u>
                - 记作
                    - ![](https://api2.mubu.com/v3/document_image/0cb57248-f192-471e-9393-8d2e7fa8f31f-15201174.jpg)
2.  2)<span style="color:#75c940;">性质</span>
    - 反身
        - ![](https://api2.mubu.com/v3/document_image/8986517c-cff8-4135-8cad-8213927bb5d2-15201174.jpg)
    - 对称
        - ![](https://api2.mubu.com/v3/document_image/a83bec86-74ce-4dc8-a5ea-1771f9b5d9fd-15201174.jpg)
    - 传递
        - ![](https://api2.mubu.com/v3/document_image/bf94c3b8-b398-4887-8393-b7c687de8ee9-15201174.jpg)
3.  3)向量组 与 其 <span style="color:#797ec9;">**极大**</span><span style="background-color:#ffff26;">**线性**</span><span style="color:#75c940;">**无**</span><span style="color:#3da8f5;">**关**</span>**组** 是 <span style="color:#3da8f5;">等价</span>向量组

</ul>

#### B.判别

<ul>

</ul>

#### C.与等价矩阵的区别

<ul>

</ul>

</ul>

### **(3)向量组的<span style="color:#75c940;">秩</span>**

<ul>

#### **A.<span style="background-color:#ffff26;">定义</span>**

<ul>

1.  向量组 的<span style="color:#797ec9;">**极大**</span><span style="background-color:#ffff26;">**线性**</span><span style="color:#75c940;">**无**</span><span style="color:#3da8f5;">**关**</span>**组**中 所含向量的个数 <span style="color:#75c940;">r</span>
    - 记作 $rank(α_1,…,α_s)$​​​​​​​​​​​​​​​​​​​​​​​​​ = r 或 $r(α_1,…,α_s)$​​​​​​​​​​​​ = r
2.  <span style="color:#3da8f5;">等价</span>向量组 具有相等的 r
    - r 相等 不一定 是等价向量组

</ul>

#### B.重要定理和公式

<ul>

1.  1)三r相等:
    - 矩阵$A$​的秩 = $A$​ 的 行/列 向量组 的秩
2.  2)若 $A$​  初等行变换 → $B$​
    - $A$​ 与$B$​
        - <u>行</u>向量组 是 <span style="color:#3da8f5;">等价</span>向量组
        - 部分<u>列</u>向量组 具有 <span style="color:#75c940;">相同</span>的 <span style="background-color:#ffff26;">线性</span><span style="color:#3da8f5;">相关性</span>
3.  3)$r(α_1,…,α_s)$​​​​​​​​​​​​≤ $r(β_1,…,β_t)$​​​​​​​​​​​​
    - 每个向量$α_i$​​​ 均可由$β$​ 中的向量 <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>

</ul>

</ul>

</ul>

## **2 <span style="background-color:#ffff26;">向量</span><span style="color:#3da8f5;">空间</span>（仅数学一要求）**

<ul>

### **(1)<span style="background-color:#ffff26;">概念</span>**

<ul>

1.  n维向量空间$R^n$​​​ 中
    - 有 <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">无关 </span>的有序向量组 $ξ_1,…,ξ_n$​​​​​​​​​
    - 任意 <span style="color:#3da8f5;">$α\in R^n$</span>​​​​​​​​ 均可由 $ξ_1,…,ξ_n$​​​​​​​​​ <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">表出</span>
        - 记为$α=a_1ξ_1,…,a_nξ_n$​​​​​​​​​​​​​​​​​
        - 称
            - 有序向量$ξ_1,…,ξ_n$​​​​​​​​​ 为$R^n$​​​的<u>一个 </u>**基**
            - <u>基向量</u> 的<u>个数</u> <span style="color:#3da8f5;">n </span>称为 向量空间的 **维数**
            - $[a_1,…,a_n]([a_1,…,a_n]^T)$​​​​​​​​​​​​​​​​​​​​​​​​​​称为向量$α$​<u>在基</u><u>$ξ$</u><u>​</u><u> 下</u>的 **坐标**
                - 或称 $α$​的 **坐标**<u>行(列)向量</u>

</ul>

### **(2)<span style="background-color:#ffff26;">基</span><span style="color:#75c940;">变换</span>与<span style="color:#3da8f5;">坐标</span><span style="color:#75c940;">变换</span>**

<ul>

1.  A.<span style="background-color:#ffff26;">基</span><span style="color:#75c940;">变换</span>
    - n维向量空间$R^n$​​​ 中
        - 两个基 为$η_1,…,η_n$​​​​​​​​​ , $ξ_1,…,ξ_n$​​​​​​​​​
        - 其 满足 $[η_1,…,η_n]$​​​​​​​​​​​ =$[ξ_1,…,ξ_n]$​​​​​​​​​​​ $C$​
            - ![](https://api2.mubu.com/v3/document_image/849a3657-67f5-4286-8ad4-b6deceb2a258-15201174.jpg)
        - 称 上式 为 由基$ξ$​ 到基$η$​  的 <span style="background-color:#ffff26;">基</span><span style="color:#75c940;">变换</span>公式
        - 称 矩阵$C$​ 为 **过渡矩阵**，且$C$​ 为可逆矩阵
            - $C$​ 的第 i 列 即 是$η_i$​​​ 在基$ξ$​下的坐标
2.  B.<span style="color:#3da8f5;">坐标</span><span style="color:#75c940;">变换</span>
    - $α$​ 在基 $ξ_1,…,ξ_n$​​​​​​​​​  和 基$η_1,…,η_n$​​​​​​​​​ 下
    - 坐标分别是 $x=[x_1,…,x_n]^T$​​​​​​​​​​​​​​​ , $y=[y_1,…,y_n]^T$​​​​​​​​​​​​​​​
        - 即 $α$​=$[ξ_1,…,ξ_n]x$​​​​​​​​​​​​= $[η_1,…,η_n]y$​​​​​​​​​​​​
        - 由 基变换公式得
        - $α=$​ $[ξ_1,…,ξ_n]$​​​​​​​​​​​ $Cy$​​
    - 得 <span style="color:#3da8f5;">$x=Cy$</span>​​​​ 或 <span style="color:#3da8f5;">$y=C^{-1}x$</span>​​​​​​​​​
        - 称 之为 坐标变换公式

</ul>

</ul>

</ul>

# **04** <span style="background-color:#ffff26;">**线性**</span><u>**方程组**</u>

<ul>

## **0 概念**

<ul>

### **basic.总述(<span style="background-color:#ffff26;">方程</span>组 与 <span style="color:#3da8f5;">向量</span>组)：**

<ul>

#### **1)<span style="background-color:#ffff26;">一般</span>的非齐次线性方程组**

<ul>

- ![](https://api2.mubu.com/v3/document_image/ad9c56e0-2bad-46c1-aeb9-6e5c3bf9d528-15201174.jpg)
    - 系数矩阵
        - 由若干个列向量拼成
            ![](https://api2.mubu.com/v3/document_image/aabc77e1-bdea-4c1b-9191-29fe86aa4574-15201174.jpg)
    - 增广矩阵
        - 系数矩阵 再加 一个列向量
            ![](https://api2.mubu.com/v3/document_image/17cbe458-8f49-4e4e-940f-f1b3b1dc41c3-15201174.jpg)

</ul>

#### **2)写成 <span style="color:#3da8f5;">向量的</span>形式**

<ul>

- 方程组中的未知数 <span style="color:#3da8f5;">x</span> 就是向量组 <u>各向量组的</u><span style="background-color:#ffff26;">系数</span>
    - ![](https://api2.mubu.com/v3/document_image/b9968747-5603-4177-b644-81915d054360-15201174.jpg)
        - 其中
            ![](https://api2.mubu.com/v3/document_image/61ea3067-3cd4-4f78-a3b9-ff270aac80b6-15201174.jpg)

</ul>

#### **3)<span style="background-color:#ffff26;">方程</span>组问题 = <span style="color:#3da8f5;">向量</span>组问题**

<ul>

- a.解**方程组** 所得到的<span style="color:#3da8f5;">解</span>$x_1,x_2,…,x_n$​​​​​​​​​​​​​ 就是 <span style="color:#75c940;">描述</span> 向量与向量间<u>关系</u>的<span style="color:#3da8f5;">系数</span>
- b.方程组 和 向量组 是 同一个问题的两种表现形式
- c.本质相同，求解方法也相同
    - i. 求解线性方程组
        - ①增广矩阵作 初等变换，化为阶梯形矩阵
        - ②求解
    - ii. 无穷 向量组 用 <span style="color:#3da8f5;">基础解系</span> 代表

</ul>

</ul>

### **A.<u><span style="background-color:#ffff26;">具体型</span></u> 线性方程组**

<ul>

### **1)<span style="background-color:#ffff26;">齐次</span>**

<ul>

1.  a.**定义**
    - i.**<span style="background-color:#ffff26;">方程</span>组**<u>形式</u>
        - ![](https://api2.mubu.com/v3/document_image/b3622ab9-ad73-4173-b965-c5e9d0fed5f1-15201174.jpg)
            - 称为 m个方程组,n个未知量的 齐次线性方程组
    - ii.<span style="color:#75c940;">**向量**</span><u>形式</u>
        - ![](https://api2.mubu.com/v3/document_image/21a846ca-27af-4928-9e36-a2d6c80bd2f6-15201174.jpg)
            - 其中
                ![](https://api2.mubu.com/v3/document_image/f9a8896d-7943-4565-a918-563a80a5b47c-15201174.jpg)
    - iii.<span style="color:#3da8f5;">**矩阵**</span><u>形式</u>
        - ![](https://api2.mubu.com/v3/document_image/b28d768c-4706-4673-ba6e-69191557dc1e-15201174.jpg)
            - 其中
                ![](https://api2.mubu.com/v3/document_image/66a41b78-53b6-4bdc-b57d-a593e2e64bc1-15201174.jpg)
2.  b.<span style="background-color:#ffff26;">性质</span>
    - 1)<u>有解</u>的<span style="color:#3da8f5;">条件</span>
        - 秩$r(A)$​​​​ 作为判断条件
            - $r(A) = n$​​​​​​​​ (n为未知量个数)
                - $α_1,α_2,…,α_n$​​​​​​​​​​​​​ <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">无关</span>
                - 方程组有 <span style="color:#797ec9;">**唯一**</span><span style="color:#797ec9;">  </span><span style="color:#3da8f5;">零解</span>
            - $r(A) =r< n$​​​​​​​​​​  (n为未知量个数)
                - 方程组有 <span style="color:#75c940;">**非零**</span><span style="color:#3da8f5;">**解**</span>
                    - 有 <span style="color:#3da8f5;">n</span>-<span style="color:#75c940;">r</span> 个 线性无关解
    - 2)解的<span style="background-color:#ffff26;">性质</span>
        - 条件:$Aξ_1 = 0$​​​​​​​​,:$Aξ_2 = 0$​​​​​​​​
        - 则 $A(k_1ξ_1+k_2ξ_2) = 0$​​​​​​​​​​​​​​​​​​​​
            - $k_1,k_2$​​​​​​​ 是任意常数
    - 3)<span style="color:#3da8f5;">基础解系</span>和<span style="background-color:#ffff26;">解</span>的<u>结构</u>
        - i.基础解系 的<span style="background-color:#ffff26;">概念</span>
            - $ξ_1 ,ξ_2,…,ξ_{n-r}$​​​​​​​​​​​​​​​​​​ **满足**
                - <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">无关</span>
                - 是 方程组$Ax=0$​​​​ 的解
                - 方程组$Ax=0$​​​​ 的任一解，均可由$ξ_1 ,ξ_2,…,ξ_{n-r}$​​​​​​​​​​​​​​​​​​ <span style="background-color:#ffff26;">线性</span><span style="color:#797ec9;">表出</span>
            - 称 <span style="color:#3da8f5;">$ξ_1 ,ξ_2,…,ξ_{n-r}$</span>​​​​​​​​​​​​​​​​​​ 为 $Ax=0$​​​​ 的 基础解系
        - ii.<span style="color:#797ec9;">**通解**</span>
            - $ξ_1 ,ξ_2,…,ξ_{n-r}$​​​​​​​​​​​​​​​​​​ 为 $Ax=0$​​​​ 的 基础解系
            - 则 <span style="color:#3da8f5;">$k_1ξ_1 +k_1ξ_2+…+k_{n-r}ξ_{n-r}$</span>​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​ 为方程组 $Ax=0$​​​​ 的 通解
                - $k_1,k_2,…,k_{n-r}$​​​​​​​​​​​​​​​​​ 是任意常数
3.  c.求解方法与步骤  //与具体例题一起
    - ① 系数矩阵$A$​ 作初等行变换 化为 梯形矩阵$B$​
    - ② 找出$r(A)$​​​​ = r的子矩阵，剩余列 位置的 未知数 设为自由变量
    - ③ 按 基础解系定义，求出<span style="color:#3da8f5;">$ξ_1 ,ξ_2,…,ξ_{n-r}$</span><span style="color:#3da8f5;"> </span>​​​​​​​​​​​​​​​​​​ ，并写出通解

</ul>

#### **2)<span style="color:#75c940;">非</span><span style="background-color:#ffff26;">齐次</span>**

<ul>

1.  a.定义
    - i.**<span style="background-color:#ffff26;">方程</span>组**<u>形式</u>
        - ![](https://api2.mubu.com/v3/document_image/7bdfc7fb-6350-4d40-af12-67887584cc0a-15201174.jpg)
            - 称为 m个方程组,n个未知量的 非齐次线性方程组
    - ii.<span style="color:#75c940;">**向量**</span><u>形式</u>
        - ![](https://api2.mubu.com/v3/document_image/13421f7b-6405-45c7-b152-7f2b7919fd50-15201174.jpg)
            - 其中
                ![](https://api2.mubu.com/v3/document_image/4db1a5a5-3a56-4d07-a6de-a79736fe9f9a-15201174.jpg)
    - iii.<span style="color:#3da8f5;">**矩阵**</span><u>形式</u>
        - ![](https://api2.mubu.com/v3/document_image/c24512b3-5e73-4c3b-ac91-4eb9e170471a-15201174.jpg)
            - 其中
                ![](https://api2.mubu.com/v3/document_image/aaebf6e7-8fcf-41d5-b4c5-01f20f06fdc8-15201174.jpg)
                - 矩阵$A$​的增广矩阵
                    - 简记为
                        - ![](https://api2.mubu.com/v3/document_image/0e4fe790-2aca-4262-b85b-0c506451d2a7-15201174.jpg)
                - ![](https://api2.mubu.com/v3/document_image/77c6d859-93ff-4419-91bb-ea6d39cdff62-15201174.jpg)
2.  b.<span style="background-color:#ffff26;">性质</span>
    - 1)<u>有解</u>的<span style="color:#3da8f5;">条件</span>
        - 秩$r(A)$​​​​ 与$r([A,b])$​​​​​​​​ 作为 判据
            - a.无解
                - $r(A)$​​​​ ≠ $r([A,b])$​​​​​​​​
                    - $b$​ 不能由$α_1,α_2,…,α_n$​​​​​​​​​​​​​   线性表出
                        - 线性表出：
                            - 向量$b$​ 被另一向量空间的 向量组$α$​ 表示
                                - ![](https://api2.mubu.com/v3/document_image/d3aa9178-6e23-4215-80f8-4e74903d79e5-15201174.jpg)
            - b.唯一解
                - $r(A)$​​​​ = $r([A,b])$​​​​​​​​ = n
                    - $α_1,α_2,…,α_n$​​​​​​​​​​​​​ 线性无关，
                    - $α_1,α_2,…,α_n$​​​​​​​​​​​​​ ,$b$​ 线性相关
            - c.无穷多解
                - $r(A)$​​​​ = $r([A,b])$​​​​​​​​ = r < n
    - 2)解的<span style="background-color:#ffff26;">性质</span>
        - 设定：
            - $η_1,η_2,η$​​​​​​​​​ 是 非齐次线性方程组$Ax=b$​​​​ 的解
            - $ξ$​ 是 对应 齐次线性方程组 $AX=0$​​​​ 的解
        - 则
            - ①$η_1-η_2$​​​​​​​ 是  $AX=0$​​​​ 的解
            - ②$kξ+η$​​​​ 是$Ax=b$​​​​ 的解
            - ③ $k_1ξ_1 +k_1ξ_2+…+k_{n-r}ξ_{n-r}+η$​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​​ 是 $Ax=b$​​​​  的通解
                - $k_1,k_2,…,k_{n-r}$​​​​​​​​​​​​​​​​​ 是任意常数
3.  c.求解<span style="color:#3da8f5;">方法</span>与步骤
    - 求出 对应 齐次 线性方程组的 通解 + 非齐次的 特解
        - ![](https://api2.mubu.com/v3/document_image/24f68b6a-756c-461f-b763-df0c2af32d92-15201174.jpg)

</ul>

</ul>

### **B.<u><span style="color:#3da8f5;">抽象型</span></u> 线性方程组**

<ul>

- 有解的条件与解的判定
- 解的结构
- 基础解系的讨论
- 系数矩阵列向量与解的关系
1.  1类型
    - 两个方程组的公共解
    - 同解方程组

</ul>

</ul>

</ul>

# **05 特征<span style="color:#3da8f5;">值</span><span style="color:#3da8f5;"> </span><span style="color:#3da8f5;">λ</span>  & <u>特征向量</u><span style="color:#3da8f5;"> </span><span style="color:#797ec9;">$ξ$</span><span style="color:#3da8f5;"> </span>  | <span style="background-color:#ffff26;">相似</span>**

<ul>

- //整章概念都是在 矩阵 基础上

## 0<span style="background-color:#ffff26;"> </span><span style="background-color:#ffff26;">**特征**</span><span style="color:#75c940;">**值**</span> <span style="color:#3da8f5;">**λ**</span>  <span style="background-color:#ffff26;">**特征**</span><span style="color:#3da8f5;">**向量**</span><span style="color:#3da8f5;"> </span><span style="color:#797ec9;">$ξ$</span>​

<ul>

### **concept**

<ul>

#### <span style="color:#3da8f5;">$λ$</span><span style="color:#797ec9;">  </span>&<span style="color:#797ec9;"> </span><span style="color:#797ec9;">$ξ$</span>​

<ul>

1.  设定:
    - $A$​ 为n阶矩阵，λ 是一个数，$ξ$​ 为n维 非零 列向量
    - 使得 $Aξ=$​​​ <span style="color:#3da8f5;">$λ$</span><span style="color:#3da8f5;"> </span><span style="color:#797ec9;"> </span><span style="color:#797ec9;">$ξ$</span>​
2.  称
    - <span style="color:#3da8f5;">λ</span> 是 $A$​ 的 <span style="background-color:#ffff26;">特征</span><span style="color:#75c940;">值</span>
    - <span style="color:#797ec9;">$ξ$</span>​  是$A$​ 对应于 特征值λ 的<span style="background-color:#ffff26;"> 特征</span><span style="color:#3da8f5;">向量</span>
    - // 特征值 和 特征向量均是相对于 矩阵$A$​ 而言的

</ul>

#### **1)** <span style="background-color:#ffff26;">**特征**</span><span style="color:#797ec9;">**方程**</span> **|** <span style="background-color:#ffff26;">**特征**</span>**矩阵**  <span style="background-color:#ffff26;">**特征**</span>**多项式**

<ul>

1.  $Aξ=λξ$​​​​​ → <span style="color:#3da8f5;">$(λE-A)ξ=0$</span>​​​​​​​​​
    - $ξ≠0$​​​
2.  称
    - ![](https://api2.mubu.com/v3/document_image/c7acb7f6-ef08-49a4-b06e-6c4a708bd5bc-15201174.jpg)
        - 上式为$A$​的 特征<span style="background-color:#ffff26;">方程</span>
            - 是未知量λ的n次方程，有n个根(重根按照重数计)
        - $λE-A$​​​​ ← ~矩阵
        - $|λE-A|$​​​​​​  ←  ~多项式

</ul>

</ul>

### **性质**

<ul>

#### <span style="color:#3da8f5;">**λ**</span>

<ul>

- ①$\sum_{i=1}^n {λ_i} \quad $​​​​​​​​​​​​​​​​​​​​​​​​​=$tr(A)$​​​​​   =    $\sum_{i=1}^n {a_{ii}} \quad $​​​​​​​​​​​​​​​​​​​​​​​​​​​​ //累加
    - tr(A) 迹：
        - 主对角线 元素 之和
- ②$\prod_{i=1}^n{λ_i} \quad$​​​​​​​​​​​​​​​​​​​​​​​​ =  $|A|$​​​   //累乘
- 推导(3阶为例)
    - 0 基本
        ![](https://api2.mubu.com/v3/document_image/338aa993-5dd5-4c17-b690-974615b78a85-15201174.jpg)
    - 1 拆开
        ![](https://api2.mubu.com/v3/document_image/664ae4a8-b258-4bc1-b337-1490b80d3823-15201174.jpg)
    - 2  设$|λE-A|$​​​​​​
        ![](https://api2.mubu.com/v3/document_image/4c574616-0ccb-447b-9974-4623f5211ff7-15201174.jpg)
    - 3 比较①②式子
        ![](https://api2.mubu.com/v3/document_image/89ad6317-46ec-441f-a303-766c643aa10c-15201174.jpg)

</ul>

#### <span style="color:#797ec9;">$ξ$</span>​

<ul>

- ![](https://api2.mubu.com/v3/document_image/41c44fc4-1456-4b79-8adc-671fe0d80bb7-15201174.jpg)

</ul>

</ul>

### C.求法

<ul>

- 具体型矩阵
- 抽象型矩阵
- <span style="color:#797ec9;">$ξ$</span>​  是$A$​ 对应于 特征值λ 的<span style="background-color:#ffff26;"> 特征</span><span style="color:#3da8f5;">向量</span>
- <span style="color:#797ec9;">$ξ$</span>​  是$A$​ 对应于 特征值λ 的<span style="background-color:#ffff26;"> 特征</span><span style="color:#3da8f5;">向量</span>

</ul>

</ul>

## **1 <span style="background-color:#ffff26;">相似</span>**

<ul>

### **A.矩阵<span style="background-color:#ffff26;">相似</span>**

<ul>

#### **1)<span style="background-color:#ffff26;">定义</span>**

<ul>

1.  设定
    - $A$​ , $B$​ 是 n阶方阵 ， $P$​ 是 n阶 <span style="background-color:#ffff26;">可逆矩阵</span>
    - <span style="color:#3da8f5;">$P^{-1}AP=B$</span>​​​​​​​​​​
2.  称A相似于B
    - 记为$A$​~$B$​

</ul>

#### **2)<u>性质</u>**

<ul>

1.  a.若$A$​~$B$​ 则有
    - r、|| 、特征多项式 同等，特征值相同
        - ![](https://api2.mubu.com/v3/document_image/dd350f3d-3384-4378-a210-4e8c0deef5a7-15201174.jpg)
    - $A^T$​​​~$B^T$​​​
    - $A^m$​​​  ~$B^m$​​​ ，$f(A)$​​​​  ~$f(B)$​​​​
2.  b.若$A$​~$B$​ ，且$A$​**可逆** 则有
    - $A^*$​​​  ~$B^*$​​​
    - $A^{-1}$​​​​​​  ~$B^{-1}$​​​​​​ ，$f(A^{-1})$​​​​​​​​​  ~$f(B^{-1})$​​​​​​​​​
        - 其中f(x)是多项式

</ul>

</ul>

### **B.矩阵的<span style="background-color:#ffff26;">相似</span><span style="color:#75c940;">对角化</span>**

<ul>

### **definition**

<ul>

- $A$​ 是 n阶方阵 ，$P$​ 是 n阶 可逆矩阵
- <span style="color:#3da8f5;">$P^{-1}AP=Λ$</span>​​​​​​​​​​
    - Λ是对角矩阵
- 称
    - $A$​ <span style="color:#75c940;">可</span><span style="background-color:#ffff26;">相似</span><span style="color:#75c940;">对角化</span>
        - 记为$A$​~$Λ$​
    - Λ是$A$​的 <span style="background-color:#ffff26;">相似</span><span style="color:#3da8f5;">标准形</span>

</ul>

### **可相似对角化的<span style="color:#3da8f5;">条件</span>**

<ul>

1.  a.推导
    - step1
        - 相似对角化 公式基础上<span style="color:#3da8f5;">$P^{-1}AP=Λ$</span>​​​​​​​​​​
        - 同时左乘$P$​
        - 有$AP=PA$​​​​​
            - 其中
                ![](https://api2.mubu.com/v3/document_image/ebdcc0ac-0bd4-4ff7-b576-a4d74cbdd48d-15201174.jpg)
    - step2
        - 即表示为
            - i
                - ![](https://api2.mubu.com/v3/document_image/655917b0-2998-4f53-aa79-72255c60421b-15201174.jpg)
            - ii
                - ![](https://api2.mubu.com/v3/document_image/22555c36-e977-4cd0-8c2f-27cafaa3e269-15201174.jpg)
        - 最终表示为<span style="color:#3da8f5;"> </span><span style="color:#3da8f5;">$Aξ_i=λ_iξ_i$</span>​​​​​​​​​​​
            - 因 $P$​可逆，$ξ_1 ,ξ_2,…,ξ_n$​​​​​​​​​​​​​​ 线性无关，上述过程可逆
2.  b.<span style="color:#3da8f5;">条件</span>
    - 对于n阶矩阵$A$​
        - 两个充要
            - 可相似对角化 ← →
                - n个 <span style="background-color:#ffff26;">线性</span><span style="color:#75c940;">无关</span>的特征向量
                - <span style="background-color:#ffff26;">对应每个</span><span style="background-color:#ffff26;">$k_i$</span>​​​<span style="background-color:#ffff26;">重特征值 都有</span><span style="background-color:#ffff26;">$k_i$</span>​​​<span style="background-color:#ffff26;"> 个线性无关的 特征向量</span>
        - 两个充分
            - n个 不同特征值
            - $A$​为实对称矩阵

</ul>

### <span style="color:#797ec9;">**步骤**</span>

<ul>

</ul>

### **application**

<ul>

#### **a.<span style="color:#75c940;">实</span><span style="color:#3da8f5;">对称矩阵</span>的相似对角化**

<ul>

1.  i.定义
    - ①对称矩阵
        - $A^T=A$​​​​​  称$A$​为对称矩阵
    - ②实对称矩阵
        - 组成$A$​的元素都是实数
    - 实对称矩阵 <span style="color:#75c940;">必可</span> 相似对角化
2.  ii.性质
    - 对于实对称矩阵$A$​
    - ①λ是实数，ξ是实向量
    - ②属于<u>不同λ</u>的<span style="color:#3da8f5;"> ξ</span>，相互正交
    - ③$A$​ <span style="color:#75c940;">必</span> 相似于 $Λ$​(对角矩阵

</ul>

#### b.反问题

<ul>

- 反求参数
- 反求A
- 求A与f(A)

</ul>

</ul>

</ul>

</ul>

</ul>

# **06 二次型**

<ul>

## **0 二次型的<span style="background-color:#ffff26;">定义</span>与矩阵表示**

<ul>

#### **(1)实二次型**

<ul>

1.  n元变量$x_1,x_2,…,x_n$​​​​​​​​​​​​​的<span style="color:#3da8f5;"> 二次</span> 齐次多项式
    - ![](https://api2.mubu.com/v3/document_image/ece79ef4-12df-4bab-a250-9b80ac582ead-15201174.jpg)
2.  考研只研究 $a_{ij}\in R$​​​​​​​​​​​  (i≤j; i,j=1,2,…,n)的情况，称此二次型f 为 **实二次型**

</ul>

#### **(2)完全<u>展开式</u> | <u>和式</u> | <span style="color:#3da8f5;">矩阵</span>**

<ul>

##### **base. 变换:**

<ul>

![](https://api2.mubu.com/v3/document_image/4b8064d1-3dd5-403b-bb2f-621fbe004edf-15201174.jpg)
- 达到补齐 矩阵的目的
- ![](https://api2.mubu.com/v3/document_image/0dacdef9-3d2a-487a-953e-1212c596cd5e-15201174.jpg)

</ul>

##### **1)完全展开式**

<ul>

- ![](https://api2.mubu.com/v3/document_image/db9b430a-6233-4d24-9f3c-0bb93daca53a-15201174.jpg)

</ul>

##### **2)和式**

<ul>

- ![](https://api2.mubu.com/v3/document_image/c8fdb1f8-1b27-4193-a355-92e04e3dcfe6-15201174.jpg)

</ul>

##### **3)<span style="color:#3da8f5;">二次型</span>f(x)的<span style="background-color:#ffff26;">矩阵</span>**

<ul>

1.  a. 二次型$f(x_1,x_2,…,x_n)$​​​​​​​​​​​​​​​​ 的 **矩阵表达式**
    - ![](https://api2.mubu.com/v3/document_image/57cb18ec-cc02-4678-9c06-5b21194143c2-15201174.jpg)
    - ![](https://api2.mubu.com/v3/document_image/78ee20da-4721-4ce9-bf55-63aef151d025-15201174.jpg)
2.  b. notice: 矩阵A 必须是一个对称矩阵
    - cause: 一个二次型可以有不同的写法，eg.三元二次型
        - 拆分系数可以有不同的形式
            ![](https://api2.mubu.com/v3/document_image/879c46ff-b5ce-41d4-8342-f9b8476c5536-15201174.jpg)
            - 自然 对应的矩阵 也有多种形式
                ![](https://api2.mubu.com/v3/document_image/690d804e-3f52-40b4-a96d-c600e1ec96f5-15201174.jpg)
3.  c. <span style="background-color:#ffff26;">**变换**</span>
    - ![](https://api2.mubu.com/v3/document_image/57763fec-5f93-46f3-afb6-6fa9feb07d0d-15201174.jpg)
        - 对称转换
            - ![](https://api2.mubu.com/v3/document_image/e2629c09-ac34-42d7-945e-62b9a0792ec5-15201174.jpg)
        - 行 和 列 相乘效果运用
            - ![](https://api2.mubu.com/v3/document_image/0418fe6f-7606-4299-81a3-6dd502e85a47-15201174.jpg)
            - ![](https://api2.mubu.com/v3/document_image/8c070dc2-b929-4885-8f7c-7e7764052b5b-15201174.jpg)

</ul>

</ul>

</ul>

### **1 化二次型为<span style="color:#3da8f5;">标准形</span>与规范形**

<ul>

### **(1)定义与<span style="background-color:#ffff26;">性质</span>**

<ul>

#### **A.<span style="background-color:#ffff26;">线性变换</span>  //换元**

<ul>

1.  1) 基本设定：
    - 对于 n元二次型$f(x_1,x_2,…,x_n)$​​​​​​​​​​​​​​​​
        - <span style="color:#75c940;">令</span>
            - ![](https://api2.mubu.com/v3/document_image/12503202-4ef6-475b-9459-1f7b19eb41d5-15201174.jpg)
        - 记
            - ![](https://api2.mubu.com/v3/document_image/480c7ce1-efb4-4611-b47e-1b8ec9d4f94c-15201174.jpg)
        - 可表示为
            - **$x=Cy$**​​​​
2.  ( * )<span style="color:#3da8f5;">式</span> 称为 从$y_i,y_2,y_3,…,y_n$​​​​​​​​​​​​​​​​​，到$x_1,x_2,x_3,…,x_n$​​​​​​​​​​​​​​​​​ 的<span style="color:#3da8f5;">线性变换</span>
    - 若 <u>系数矩阵C</u> **可逆**，即$|C|$​​​ ≠ 0，则称为 **可逆线性变换**
3.  2) 对于二次型的矩阵表示
    - **$f(x)=x^TAx$**​​​​​​​​​​  , 令 **$x=Cy$**​​​​
        - ↓
        - 则 **$f(x)=f(Cy)=(Cy)^TA(Cy)$**​​​​​​​​​​​​​​​​​​​​​​
            - ↓
            - 即 **$f(x)=y^T(C^TAC)y$**​​​​​​​​​​​​​​​​
            - 记$B=C^TAC$​​​​​​​
            - ↓
        - 得 $f(x)=y^TBy$​​​​​​​​​​  即 得到一个新二次型 $g(y)=y^TBy$​​​​​​​​​​

</ul>

#### **B.矩阵<span style="color:#75c940;">合同</span>**

<ul>

1.  1)基本定义
    - $f(x)$​​​​ 与 $g(y)$​​​​ 的系数矩阵关系：
        - <span style="color:#3da8f5;">$C^TAC=B$</span>​​​​​​​
    - 则称 $A$​与$B$​ 合同
        - 记为
            ![](https://api2.mubu.com/v3/document_image/d8e7d396-f8ae-40c6-b87c-2dd86e92161e-15201174.jpg)
    -      称对应的二次型 $f(x)$​​​​ 与 $g(y)$​​​​ 为 <span style="color:#3da8f5;">合同二次型</span>
2.  2)性质
    - a.阐述:
        - A、B 实际 表征 同一事物 在不同 参照系下 不同"形态"
            - ![](https://api2.mubu.com/v3/document_image/1cd41a7e-3ac1-4ea9-8169-3734ccb860e1-15201174.jpg)
        - A与B的<span style="color:#3da8f5;">合同 </span>就<span style="color:#75c940;">是</span>指  同一个二次型 在可逆线性变换下  两个不同状态的<span style="color:#3da8f5;">联系</span>
            - ![](https://api2.mubu.com/v3/document_image/5f29b8be-54e5-474f-9853-605851282701-15201174.jpg)
    - b.性质:
        - 1) 反身 对称 传递
            - ![](https://api2.mubu.com/v3/document_image/7367c906-41b9-447d-a8ae-7d8cbe4a3150-15201174.jpg)
        - 2) 不改变 秩
            - 若A与B合同 → r(A)=r(B)
                - 则 可逆线性变换 <u>不会改变</u> **二次型的秩**
        - 3)与 <span style="color:#3da8f5;">对称</span>$A$​<span style="color:#75c940;"> 合同</span>的 矩阵<u>也必定是</u> <span style="color:#3da8f5;">对称</span>矩阵
            - ![](https://api2.mubu.com/v3/document_image/60e69ee5-40ba-43bf-86d2-102770520ddd-15201174.jpg)
                - ![](https://api2.mubu.com/v3/document_image/dcb303a8-8fb2-4512-9ebb-92c1c2e96a0f-15201174.jpg)

</ul>

#### **C.二次型的<span style="color:#3da8f5;">标准形</span>、规范形**

<ul>

##### **1)基本<span style="background-color:#ffff26;">定义</span>**

<ul>

1.  **a.标准形**
    - 二次型 中<span style="color:#75c940;">只含</span><span style="color:#3da8f5;">平方项</span> 不含交叉项(所有交叉项的系数为0)
        - 形如
            - ![](https://api2.mubu.com/v3/document_image/5cf8f6a3-5d8c-4b93-9b72-6727e22c54be-15201174.jpg)
2.  ↓
3.  **b.规范形**
    - 标准型中，系数$d_i$​​​仅为 **1,-1,0**
        - 形如
            - ![](https://api2.mubu.com/v3/document_image/f13dbb5a-1a52-4ae8-b490-fa665ce95750-15201174.jpg)
4.  **c.<span style="color:#75c940;">合同</span> 标准形/规范形**
    - 二次型**$f(x)=x^TAx$**​​​​​​​​​​ <span style="color:#75c940;">合同于</span> 标准型$d_1x_1^2+…+d_nx_n^2$​​​​​​​​​​​​​​​​​​​ or 规范型
    - 称 该 标准型/规范型 为 二次型的合同标准型/规范型

</ul>

##### **2)性质**

<ul>

1.  **a.配方法**
    - 任何 二次型 均可通过配方法 化成标准形/标准形
    - ↓
    - 任何 实对称矩阵A，必存在可逆矩阵C，
        - <span style="color:#75c940;">使得</span>
            - ![](https://api2.mubu.com/v3/document_image/203d8864-b3b2-41ca-98ec-8facd6e8ed86-15201174.jpg)
            - 其中
            - ![](https://api2.mubu.com/v3/document_image/ec971970-1f8f-4090-8a49-b80fd1360f01-15201174.jpg)
2.  **b.<span style="background-color:#ffff26;">正交变换</span>**
    - 任何 二次型 均可通过配方法 化成标准形/标准形
    - ↓
    - 任何 <span style="color:#3da8f5;">实对称矩阵</span>A，必存在 正交矩阵Q 使得
        - ![](https://api2.mubu.com/v3/document_image/cd9135a7-f539-40f4-bc29-8f7c17ab456a-15201174.jpg)
        - 其中
            ![](https://api2.mubu.com/v3/document_image/d3401666-e4d4-4f17-89a5-e4ee45b8ee84-15201174.jpg)

</ul>

</ul>

#### **add.惯性定理**

<ul>

1.  1)基本定义
    - 在 可逆线性变换中， 正项个数p  负项个数q 始终不变
    - <span style="color:#3da8f5;">p </span>: 正惯性指数
    - <span style="color:#3da8f5;">q</span>: 负惯性指数
2.  2)性质
    - a.<span style="color:#75c940;"> r </span>= p+q
    - b.合同的充要条件：same <span style="color:#3da8f5;">p q</span>  or<span style="color:#75c940;"> r</span>

</ul>

</ul>

### **(2)方法**

<ul>

- 配方法
- 正交变换法
- 合同
- 惯性定理

</ul>

</ul>

## **2 正定二次型**

<ul>

### **(0)<span style="background-color:#ffff26;">定义</span>**

<ul>

1.  设定：
    - ![](https://api2.mubu.com/v3/document_image/73dc0fa5-e063-41b0-b2af-d22945bd02b8-15201174.jpg)
    - ![](https://api2.mubu.com/v3/document_image/d056ab85-b646-47b3-90b1-9af43c2c8063-15201174.jpg)
2.  $f$​ 为 正定二次型，$A$​ 为 正定矩阵

</ul>

### **(1)<span style="background-color:#ffff26;">充要</span><span style="color:#3da8f5;">条件</span>**

<ul>

- a.定义
- b.f 的正惯性指数
- c.$A$​
    - ①A与E合同
    - ②A的特征值$λ_i>0$​​​​​(i = 1,2,…,n)
    - ③$A$​的全部顺序主子式 均大于 0
        - A的 **顺序主子式**
            - ![](https://api2.mubu.com/v3/document_image/76a0b698-47b2-4a81-9346-aea728df2b0d-15201174.jpg)
            - ![](https://api2.mubu.com/v3/document_image/b5115cfe-4621-4943-ad43-ded2e2d504ef-15201174.jpg)
            - ![](https://api2.mubu.com/v3/document_image/c8ac37fd-4a1d-4695-9932-63125bc9c4aa-15201174.jpg)
            - ![](https://api2.mubu.com/v3/document_image/2c044f74-bbb3-482f-ae0e-ab2f422862f2-15201174.jpg)

</ul>

### **(2)<span style="color:#75c940;">必要</span><span style="color:#3da8f5;">条件</span>(结论)**

<ul>

- a. 主对角线 元素 >0
    - ![](https://api2.mubu.com/v3/document_image/ea330d34-6dcf-47b4-8863-b92436394818-15201174.jpg)
- b.$|A|$​​​ >0
- add.判定
    - 具体型二次型
    - 抽象型二次型

</ul>

</ul>

</ul>

</ul>