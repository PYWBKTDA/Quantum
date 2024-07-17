# Quantum

记$U=\mathbb{C}^{2^{n}}$，对于$v\in U$且$|v|=1$，有以下两种操作：

- 左乘幺正矩阵$M:U\rightarrow U$

- 对于矩阵$M_{1},M_{2},\cdots,M_{k}:U\rightarrow U$满足$\sum_{i=1}^{k}M_{i}^{\dagger}M_{i}=I$，以$|M_{i}v|^{2}$的概率变为$\frac{M_{i}v}{|M_{i}v|}$并返回对应的$i$

  $\sum_{i=1}^{k}|M_{i}v|^{2}=\sum_{i=1}^{k}v^{\dagger}M_{i}^{\dagger}M_{i}v=|v|=1$

  若$v_{1},v_{2},...,v_{2^{n}}$为$U$的正交基，取$M_{i}=v_{i}v_{i}^{\dagger}$，设$v=\sum_{i=1}^{k}a_{i}v_{i}$，则以$|a_{i}|^{2}$的概率变为$v_{i}$并返回对应的$i$

  测量厄米矩阵：测量特征向量对应的正交基，并返回对应的特征值

对于$2$维向量$\psi_{[1,n]}$，用$|\psi_{1}\psi_{2}\cdots\psi_{n}\rangle$表示$\bigotimes_{i=1}^{n}\psi_{i}\in U$

若$0_{i}$和$1_{i}$正交，则$|0_{1}0_{2}\cdots 0_{n}\rangle,|0_{1}0_{2}\cdots 1_{n}\rangle,\cdots,|1_{1}1_{2}\cdots 1_{n}\rangle$为$U$的正交基

对于$2$维幺正矩阵$A_{[1,n]}$，则$A=\bigotimes_{i=1}^{n}A_{i}:U\rightarrow U$也为幺正矩阵，且$A|\psi_{1}\psi_{2}...\psi_{n}\rangle=|A_{1}\psi_{1},A_{2}\psi_{2}\cdots A_{n}\psi_{n}\rangle$

在通信中，设手中的量子集合为$S$，则$M_{i,j}\ne 0$需满足$i$和$j$不在$S$中的位相同

# Quantum Algorithm

