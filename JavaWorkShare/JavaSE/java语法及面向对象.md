## 01、 流程控制

### 001、分支结构

​		分支结构有if --else 和switch-case两种结构

if（）判断中必须是布尔表达式，即结果为boolean，可以嵌套使用，**当多个条件是“互斥”关系时，条件判断语句及执行语句间顺序无所谓，当多个条件是“包含”关系时 **，**“小上大下、子上父下”**

​	  switch语句中表达式 只能是byte，short，char，int，枚举，String

不可以采用long，float，double，boolean

​	   **当case进入后，一旦匹配成功，执行相关语句，仍继续向下执行其他case语句，直到遇到break关键字或末尾结束**

### 002、循环结构

