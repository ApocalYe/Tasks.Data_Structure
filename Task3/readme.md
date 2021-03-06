# 数据结构 第三次课堂作业

# 题目

## 第四章练习题 10
设计一个算法，判断一个字符串```s```是否为形如 ```序列1@序列2``` 模式的字符序列。
其中 ```序列1``` 和 ```序列2``` 都不含有 ```'@'``` 字符，且 ```序列2``` 是 ```序列1``` 的逆序列。
例如 ```a+b@b+a``` 属于该模式的字符序列，而 ```1+3@3-1``` 不是。

## 第四章练习题 11
采用顺序结构储存串，设计一个算法求串 ```s``` 中出现的第一个最长重复子串的下标和长度。

## 用队列求解迷宫问题
给定一个 ```M*N``` 的迷宫图，入口与出口、行走规则。求一条从指定入口到出口的最短路径。

测试数据说明：
- 第1行表示地图矩阵大小：行数```N``` 列数```M```
- 第2行表示起点位置：行 列
- 第3行表示终点位置：行 列
- 第4到```N+3```行 每行```M```个字符：```0```表示可以走，```1```表示障碍。

一些测试输入：
1. [11*11 满足右手法则](../Task2/test/maze_11x11.txt)
2. [21*21 满足右手法则](../Task2/test/maze_21x21.txt)
3. [21*21 一般](../Task2/test/maze_21x21_1.txt)
4. [601*601 一般](../Task2/test/maze_601x601.txt)

## 出栈次序验证
假设存在一个栈，现给定一个 ```N``` 表示 ```1```， ```2```， ```3```, ```...```, ```N-1```, ```N``` 依次入栈，
再给定一个长度为```N```的序列 ```S``` ，表示这```N```个元素的出栈次序。

现要求设计一个算法来验证这个```S```所表示的出栈次序是否合法。

# 提交
1. 将作业打包为压缩文件，如 ```zip``` 格式。
2. 压缩文件命名为你的学号， 如 ```2018302114514.zip``` 。 
3. 将压缩文件以附件形式发送到邮箱 ```DS_Task3 # superexercisebook.com```
4. 如果一切顺利，你将会收到一个投递成功回执。