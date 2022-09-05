## DDL-表操作-修改：

###    添加字段：

####  alter table 表名 add 字段名 类型（长度）【comment 注释】【约束】

```mysql
eg:::  alter table emp add nickname varchar(20) comment '昵称';
```



###  修改字段名和字段类型：

####    alter table 表名 change  旧字段名 新字段名 类型（长度）【comment 注释】【约   束】

```mysql
 eg:::::  alter table emp change nickname username varchar(30);
```



### 删除字段：

####     alter table 表名 drop 字段名；



### 修改表名：

#### alter table 表名 rename to 新的表名；



### 删除表

####   drop table [if exists] 表名；



### 删除指定表，并重新创建该表

####     truncate table 表名； 