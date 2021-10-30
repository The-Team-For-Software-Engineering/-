编码规范
==========
缩进
----------

次一级的代码需进行缩进，个人习惯“{”另起一行
```
If(ture) 
{
	if(ture)
        {
          cout << ”a” << endl;
	}
}
```
变量命名：
----------
变量 (包括函数参数) 和数据成员名一律小写, 单词之间用下划线连接
~~~
string data;
~~~
常量命名：
----------
根据需要的功能用英文进行命名

函数命名：
----------
函数名和类名使用驼峰命名法，每个单词的首字母全部大写，单词之间通过下划线连接
~~~
AddTableEntry()	DeleteUrl()	OpenFileOrDie()
~~~
每行最多字符数：
----------
每一行代码字符数不超过 80.

函数最大行数：
----------
每个函数最大行数不超过80

注释：
----------
一律使用 // 进行注释
在函数声明前一行进行注释表明功能

空行：
-----------
两段函数的定义之间必须留有一行空行
操作符前后空格：
----------
~~~
for (  ;  i < 5  ;  ++i)  {  }
// 循环里内 ; 后恒有空格, ;  前可以加个空格.
x  =  0;
~~~
//赋值运算符前后总是有空格.其它二元操作符也前后恒有空格
