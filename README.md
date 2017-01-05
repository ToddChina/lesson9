### 原生js讲解

1. 变量和数据类型
	* 六种数据类型：数字，字符串，布尔，null，undefined，object对象
	* var定义变量，=给变量赋值，赋值为六种数据类型的其中一种
	* 变量的命名方式：语义化，区分大小写，以字母/下划线/$开头，驼峰命名法
	* 加号的用法，字符串连接和数字的加法
	* 详见demo01
2. 重点讲解object对象
	* 属性的无序集合
````js
		var dog = {
			"name":"wangcai",
			"age":3,
		};
		dog.name;
````

	* 结果为“wangcai”
	* 详见demo02
3. 内置对象
	* 只讲解日期对象
	* 如何获取日期对象，从对象中获取属性
	* 详见demo03
4. 获取当前的日期和时间
	* 做一个小的获取当前日期和时间的demo
	* 详见demo04
5. 函数
	* 使用function声明函数，后面加函数的名称，然后(){}，在{}内写语句块
	* 声明函数完成之后需要执行函数才能使函数中的语句块运行，执行函数需要在函数外写函数名称加()
	
````js
		function fun(){
			alert("hello world");
		}
		fun();
````

	* 对象中也可以添加函数，为这个对象的方法
````js
		var dog = {
			"name":"wangcai",
			"age":3,
			sayName:function(){
				alert("我叫" + this.name)
			}
		};
		dog.sayName();
````

6. 函数传参
	* 写在声明函数括号中的是形参
	* 写在执行函数括号中的是实参
````js
		function fun(str){ 
			alert(str);
		}
		fun("hello 函数传参"); 
````

7. 函数传参为两个参数
````js
		function add(num1,num2){
			var result = num1 + num2;
			alert(result);
		}
		add(10,20);
````

8. 函数的返回值
	* 函数运行的结果，使用return将函数运行完成的结果传递出来
````js
		function fun(num1,num2){
			var result = num1 + num2;
			return result;
		}
		var re = fun(10,20);
		alert(re);
````

9. 数组
	* 数据的有序集合
	* 获取数组中的数据，需要数组和数组下标的组合
	* 获取数组的长度:arr.length
````js
	var arr = ["钢铁侠","闪电侠","蜘蛛侠","绿箭侠","蝙蝠侠"];
		console.log(arr[4]);
		console.log(arr.length);
````

10. 数组的push方法
	* arr.push()将括号内的数据添加到数组的最后
	* arr.pop()将数组的最后一个元素删除
	* arr.shift()删除数组的第一个元素
	* arr.unshift()从开头添加括号内的元素

### swiper的应用

1. 前端工程师的其中重要任务，就是学会使用框架和插件
2. 今天就来学习一个移动端常用插件：swiper
3. 通过中文教程教学生如何去学习文档
4. 首先实现一个最基础的页面切换的功能
5. 其次通过添加属性增加其他功能
6. 利用swiper中的animation制作一个自己的简单微场景

### 介绍jquery插件

1. juqery之家等类似的利用jquery,css3,h5开发的插件，以轻便的形势实现完美的效果
2. 下载插件，学习如何使用插件

## 时间可以继续向下学习

1. echart数据课时化，根据中文文档，做一个简单的案例