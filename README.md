C++实现一个简单的航空购票程序(主要是结构体的使用，未涉及面向对象编程)  

=====  

题目要求：  

编写一个航空订票程序：  
假设一等舱5个座位，编号为1~5，经济舱20个座位，编号为1~20  
具体要求如下：  
当程序开始时，提示输入乘客姓名，一个名字只能订一个座位，如果该名字已经订过座位了，则提示该乘客座位已定及座位号，否则提示输入舱位类型；  
当输入舱位类型后，如果该舱位已全部订出，则提示此舱全部订完，重新选择舱位类型；
否则显示可以选择的座位号，注意已经被订出的座位号不能出现，提示输入座位号；  
舱位类型：只能输入”F”或”E”，一等舱为F，经济舱为E，如果输入其它字符则提示输入无效。  
座位号：只能输入前面列出可以选择的座位号，若输入其它则提示输入无效。  程序可以为多个乘客订票，直到输入名字为”.”;  
最后程序按照舱位类型与座位号排序打印出所有订票信息（座位号及对应乘客姓名）
