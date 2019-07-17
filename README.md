# matlab
#为了数学建模学习matlab
#第一章线性规划问题(1.线性规划

求线性规划问题的最优解有两种方法，一种方法是使用linprog命令，另一种是使用optimtool工具箱，下面分别介绍这两种方法.

①linprog命令

一般情况下，Linprog命令的参数形式为[x,fval] = linprog(f,A,b,Aeq,beq,lb,ub,x0)，下面分别介绍各参数的含义.

[x,fval]返回值中x为最优解，fval为最优值.

f表示目标函数中各个变量前面的系数向量，如果是求最小值问题，那么f就是各个变量的系数，如果是求最大值问题，那么f就是各个变量的系数的相反数.

A和b    表示不等式约束A*x <=b中的矩阵A和向量b.

Aeq和beq    表示等式约束Aeq*x =beq中的矩阵Aeq和向量beq.

lb和ub    分别表示自变量的上下界组成的向量，如果没有上下界，该选项用[]表示，如果只有部分变量有上下界，其余的变量没有，那么可以把没有上下界的变量的上下界设为-inf或者inf使lb或者ub的长度符合要求.https://blog.csdn.net/limin_yu/article/details/80256051)
#非线性规划（https://blog.csdn.net/limin_yu/article/details/80257186）
