学习笔记

/**
 *   tic_tac_toy
 * */

1.查缺补漏  新掌握原生js操作类名方法 增删改查
		classList.add()             	添加新的类名，如果已经存在，取消添加(即不重复添加)
		classList.contains()        	确定元素是否有该类名，返回为布尔值
		classList.remove()          	删除已经存在的类名
		classList.toggle()         	 	如果存在给定的值，就删除，反之添加
		classList.replace(old, new)     替换类名
		
2.反复使用一个let 变量而不互相影响的情况   可以在该变量外加{ }  使其成为单独的作用域 

3.通过JSON.stringfy()和JSON.parse() 可实现对象或者数组深拷贝

4.continue  直接跳出本次for循环 下次继续执行  ** 只能在循环中使用 **

5.break;  跳出多层循环的时候要在最外层加label
		xxx:for(){
			for{
				break xxx;
			}
		}
		
6.Object.create()    //可以克隆一维数组

7.while(true)      //无限循环