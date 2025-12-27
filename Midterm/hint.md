---
marp: true
math: mathjax
paginate: true
style: |
  section.two-cols { display:flex; gap:16px; margin-top:12px; }
  section.two-cols img { width:50%; height:auto; }
  section.slide-small {line-height: 1.5; }
  section.slide-small :where(p, li, blockquote, pre, code, table, th, td, figcaption) {font-size: 95%;}
  section.slide-small mjx-container,
  section.slide-small .katex {
    font-size: 0.95em;
  }
  section.center h1 { text-align: center; font-size: 2.8em; }

---
# 期中考试易错点提示
### 考试加油！
> 本篇内容不能起到平替复习的作用
![bg contain right:40%](./img/emoji.jpg)

---
# 第一章 线性方程组
- 当且仅当
  $\Rightarrow$ 充分性，$\Leftarrow$ 必要性，都要证
  或者全程使用 $\Leftrightarrow$ 等价表述

- 确定的否定：线性方程组无解或者有无穷多个解

- 高斯消元法：可能存在 $0=d$ 的行

- 自由变量的取值范围
  $eg.$ $x_3=s,x_4=r$
  $s,r\in \mathbb{R}$

---
# 第二章 矩阵
- 证明子空间时，零向量存在与子集非空是等价的，只不过证明子集非空的快速方法通常是证明零向量存在（另外两个条件是加法封闭与数乘封闭）

- 如果要求证明向量空间，需要证明 $2$ 个运算封闭和教材 P20 的 $8$ 条性质（证否向量空间只需要找到一个不成立的性质的反例即可）

- 计算矩阵的秩，不一定非要化成阶梯形，可以考虑向量组的维数

- 秩的语言刻画线性方程组的解的情况

- 矩阵乘法没有交换律与消去律（没有消去律的意思是 $AB=0$ 不能推出 $A=0$ 或 $B=0$，$AB=AC$ 不能推出 $B=C$ ）

- 只有可交换的两个矩阵才有二项式定理

---
# 第二章 矩阵
- $\mathbf{v}_1,\cdots,\mathbf{v}_r$ 线性相关当且仅当其中至少有一个向量是其余向量的线性组合

  > 如果向量组线性相关，那么每一个向量都可以表示成其余向量的线性组合吗？

- 设向量组 $S$ 是向量组 $T$ 的一个子集。那么，如果 $S$ 线性相关，则 $T$ 也线性相关；反之，如果 $T$ 线性无关，则 $S$ 也线性无关
  > 如果向量组的任何不是它本身的子向量组都线性无关，那么该向量组也线性无关吗？

---
# 第二章 矩阵
- 分块矩阵的角度刻画矩阵乘法

- 计算矩阵的方幂，常用方法有归纳法，将原矩阵分解成若干个矩阵的和（往往是纯量矩阵与幂零矩阵）或积，将矩阵视为线性映射考虑标准基的像等

- 初等行/列变换（左乘/右乘可逆矩阵）不改变矩阵的秩

- $\operatorname{rank}(AB)\leq \min(\operatorname{rank}A,\operatorname{rank}B)$

-  $\operatorname{rank}(A^TA)=\operatorname{rank}(AA^T)=\operatorname{rank}A$

- 分块初等矩阵（左行右列法则，注意左/右有双重含义）

- 二阶准三角方阵的逆

- 沙漠岛公式（尽量看懂猜的思路）

---
# 第二章 矩阵
- 秩零化度定理：$\operatorname{nullity}A(\dim S)+\operatorname{rank}A=\dim(\operatorname{ker}(\varphi_A))+\dim(\operatorname{im}(\varphi_A))=n$，其中 $n$ 为 $A$ 的列数（即未知元的数量，或者线性映射 $\varphi_A$ 定义域的维数）

- 解空间的结构：对于非齐次线性方程组 $A\mathbf{x}=\mathbf{b}$ ，如果相容，
非齐次线性方程组的通解 = 非齐次线性方程组的一个特解 + 相伴的齐次线性方程组 $A\mathbf{x}=\mathbf{0}$ 的非平凡解（若不存在非平凡解则非齐次线性方程组只有唯一解）
> 注意求相伴的齐次线性方程组基础解系的正确方式（非齐次线性方程组通解去掉常数项即特解）

---
# 第三章 行列式
- 计算行列式时可以混合使用初等行、列变换 
但在求逆矩阵时只能使用**初等行变换或列变换中的一种**（不可混用）

- 行列式交换两行/两列后有一个负号（计算行列式时最少用的一种初等变换）

- 分块矩阵的相关行列式结论

- 伴随矩阵中，$a_{ij}$ 的代数余子式（有符号）位于伴随矩阵的第 $j$ 行 $i$ 列

- 无论 $A$ 是否可逆，$AA^*=A^*A=|A|I$
---
# 考试信息
- 考试时间: 2025.11.16 星期日 9:00~11:00
- 考试地点: 教学中心 101
- 考试范围: 前三章
- 期中考试占总成绩 30%
- 试卷为全中文，题型与难度参考两套练习卷

具体见教务系统 - 我的考试

考前保证充足的营养摄入!

---
<!-- _class: center -->
# Good Luck!


