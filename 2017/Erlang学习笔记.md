# Erlang学习笔记

## 第一章节

- 并发与并行

- 模拟创建进程

- 发送消息

- 接收消息

- 如果你习惯了命令式语言，可能会对这个概念感到不可思议。在命令式语言里，变量其实是
  伪装起来的内存地址。某个程序里的X其实就是内存某处的数据项地址。定义X=12时，改变的是
  地址X处的内存值，但在Erlang里，变量X代表的是一个永远不能改变的值。

- 请注意Erlang的变量以大写字母开头。所以X、This和A_long_name都是变量。以小写字母
  开头的名称(比如monday或friday)不是变量，而是符号常量，它们被称为原子(atom)。(老子也是醉了。)	

- ​


  ​			
  ​		
  ​	
