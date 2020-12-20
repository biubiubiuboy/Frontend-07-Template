学习笔记


/**
 *  四则运算
 * */

1.  词法分析：TokenNumber: 1、2、3、4、5、6、7、8、9、0
             Operator: + 、- 、* 、/
			 Whitespace:<SP>
			 LineTerminator:<LF><CR>
			 
2.  yield   新script语法特性    当我们要返回一个序列的时候使用  与return不同 
								yield并不能直接生产值，而是产生一个等待输出的函数
								yield无法单独工作，需要配合generator(生成器)的其他函数