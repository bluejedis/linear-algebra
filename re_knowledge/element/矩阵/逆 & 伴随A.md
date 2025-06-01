<div style="float: left; width: 64%; padding: 1%;">

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
</div>
<div style="float: right; width: 26%; padding: 1%;">

</div>
<div style="clear: both;"></div>
