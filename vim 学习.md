
##### vim清空所有内容

	在命令模式下，首先执行  gg (跳至文件首行)  再执行：dG

或者

	echo > file
##### vim 查找

命令状态下输入：

	/关键词  然后回车查找
	
##### vim 查找下一个/ 上一个

搜索高亮后：

	跳到下一个：小写n
	上一个：大写N

##### 客户端putty连接linux中vim的小键盘问题

在putty上用vi的时候，开NumLock时按小键盘上的数字键并不能输入数字，而是出现一个字母然后换行（实际上是命令模式上对应上下左右的键）。

解决方法：

选项Terminal->Features里，找到Disable application keypad mode，选上就可以了
