学习笔记

1.proxy与双向绑定     po = new Proxy(object, {
					  set(obj, prop, val) {
						//未操作object
					  }
					})
	监听、管理对象
	可以设置get、set的钩子函数
	
	handle 对象的方法
	set() 属性设置操作
	get() 属性读取操作
	deleteProperty() delete操作符
	apply() 函数调用操作
	construct() new操作符