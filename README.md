# 使用链表实现一个一元稀疏多项式简单计算器，该项目仅供参考
问题描述：
    
    设计一个一元稀疏多项式简单计算器。

基本要求：

设计一个C++模板类Polynomial<T>，其中 T 给出了系数的类型。类 Polynomial 应该带有一个私有成员 degree ，它是多项式的阶数。当然，它还可能包含其他的私有成员。多项式类应支持以下操作：

(1) Polynomial() ——创建一个0阶多项式。这个多项式的阶数为0，不包含任何项。它是类的构造函数。

(2) Degree()——返回多项式的阶数。

(3) Input()——读入一个多项式。可以假定输入是由多项式的阶数和一个系数表构成，系数表中的系数按指数递增的次序排列。

(4) Output()——输出多项式。输出格式可以与输入格式相同或为类数学表达式；。

(5) Add(b)——把当前多项式加到多项式b 上，并返回所得结果。

(6) Subtract(b)——减去多项式b 并返回所得结果。

(7) Multiply(b)——乘以多项式b 并返回所得结果。

(8) Divide(b)——除以多项式b 并返回所得结果。

(9) Value(x)——返回按x 计算出的多项式的值。

(10)Derivative()——求导。

(11)operator %(x)——返回对x取模运算的多项式结果。

对于(3) 至(9)，需要重载操作符< <、> >、+、-、*、/ 和( )。对于(9)，语法P(x) 应返回多项式在x点的取值，其中P的类型为Polynomial。采用适当的多项式测试一元稀疏多项式简单计算器的基本功能。
