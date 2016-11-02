# BinaryRelation

离散数学上机实验2：集合上二元关系性质判定的实现

## 实验目的：
编程实现任意集合上二元关系的性质判定

## 要求：
1. 从屏幕输入集合的元素个数
2. 建立元素之间的二元关系 
3. 根据已有的二元关系判定自反性、对称性、传递性、反自反性和反对称性

## 实验原理及内容：
* 从键盘读入元素的个数，生成一个关系矩阵
* 将元素之间的二元关系通过矩阵来表示
* 通过对矩阵的操作来进行二元关系性质的判定
* 程序使用了面向对象。与上次一样，类声明、实现以及主函数流程分为三个文件，编译时由makefile进行连接。

## Tips：
1. 二维数组的实现仍然使用了vector，~~stl那么棒不用白不用~~
2. 判断的主要思想是遍历。对对称和反对称的遍历做了一点小小的优化，判断阶梯阵就行了。但是传递性很暴力的套了好几层……实在是无能无力，有更好的算法请联系我~~(教练我做不到啊)~~
3. 英语无能，输入输出提示啥玩意的都是机翻+初中水平生搬硬凑的，估计会有些错误