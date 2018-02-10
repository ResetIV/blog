###### 问题：
** 我们在编写c++程序时可能会遇见一个问题，就是在编写一个类的内容时我们通常并不想在一开始时就定义数组的长度，我们希望创建一个可以给自由变化长度的数组**

---

###### 解决方法：
** 1.利用stl标准库的Array容器**
stl标准库有个容器就是可变长数组，我们先将头文件“Array.h”加入放到程序中，整体代码如下
	#include"iostream"
	#include"Array.h"//加入
	using namespace std;
	
	int main()
	{
		Array<int> example;
		example.
	}
