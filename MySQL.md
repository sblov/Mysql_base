# MySQL

mysql数据库属于MySQLAB公司，总部在瑞典，后被oracle收购

DBMS分类：

​	基于共享文件系统的DBMS（Access）

​	基于客户端-服务器的DBMS	（MySQL）

### 一、常见命令

```mysql
1.查看当前所有数据库
show databases;
2.打开指定的库
use 库名;
2.查看当前库的所有表
show tables;
4.查看其他库的所有表
show tables from 库名;
5.创建表
create table 表名{
	列名 类型,
	……
}
6.查看表结构
desc 表名;
7.查看服务器版本
select version();
```

### 二、语法规范

 -	不区分大小写
 -	每条命令最好用分号结尾
 -	每条命令根据需要，可以缩进或换行
 -	注释：
    -	单行：# ...，-- ...
    -	多行：/* ..... */

### 三、DQL

### 四、DML

### 五、DDL

### 六、TCL

### 七、试图

### 八、存储过程和函数

### 九、流程控制结构