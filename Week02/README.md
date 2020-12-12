学习笔记


/**
 *  地图算法
 * */

1.fill() 方法：  使用固定值填充数组
				array.fill(value,start,end)   //value 填充的值   start 开始的替换的index位置(包括index)   end 结束的下标位置(不包括本身，可理解为 index+ 1)  
				
2.event.which:      (e.which===1)代表鼠标左键   (e.which===3)代表鼠标右键  

3. '集合' 是所有搜索算法的灵魂，所有搜索算法的差异部分全在集合里
		当前广度优先搜索集合用数组表示  先进先出  push和shift相对就是队列  push和pop同时使用就是个栈
		
4.一维数组拷贝   Object.create(map)