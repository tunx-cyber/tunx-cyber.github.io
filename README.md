# Hello world

思来想去觉得还是分享一下我面试字节的面试题，希望有所帮助，有可能会打击。你们可以试试。

**本文使用Typora编写，仅仅展示文字，没有专门写js**

题目如下：

1.https如何建立安全的连接

2.在你业务增长的过程中，controller是否会变得臃肿

3.http连接可以连接几个

4.请描述一下c++内存分区

5.c++中堆栈会有内部碎片吗

6.会不会存在虚拟地址映射不成功的情况

7.请实现一种页表置换算法 描述其数据结构以及复杂度

8.描述一下cpu执行指令过程，具体到内存的层次结构。

9.TCP建立连接过程。

10.TCP如何保证可靠

11.描述一下MVC

12.讲讲MVC和MVVM 讲讲模式

13.如何做sql优化

14.讲讲索引

15.b/b+树 以及哪个查询效率高

16.get和post的区别。哪种更安全，为什么。对数据长度的限制是什么。



程序题：

```
struct test
{
    char ch;
     int a;
};
struct test1
{
    int * c;
    test d;
    char l;
};
int main()
{
    cout<<sizeof(test)<<endl;//输出多少
    cout<<sizeof(test1)<<endl;  //输出多少
}
```



求一个数组中x和x+1都在数组中的数目

eg: 

input = [1,2,3]

output=2

我给两个思路，sort和hash