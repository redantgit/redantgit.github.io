#  MySQL information_schema库的使用

MySQL 5.0以上的 内置数据库 
**information_schema** 数据库
**schemata**表中的**schema_name**字段 存放所有数据库名
**tables**表中的**table_name**字段 存放所有数据表名
**columns**表中的**column_name**字段 存放所有字段名

#### 通过information_schema数据库查询出CHONGSHENG数据库名，以及查询出其对应的所有表，以及所有表对应的字段名。（每次查询的结果仅为一条需要加WHERE限制条件）

#####  通过information_schema数据库查询出CHONGSHENG数据库名

```mysql
select schema_name from information_schema.schemata where schema_name = 'chongsheng';
```

##### 通过information_schema数据库查询出CHONGSHENG数据库名其对应的所有表

```mysql
select table_name from information_schema.tables where table_schema = 'chongsheng';
```

##### 通过information_schema数据库查询出CHONGSHENG数据库所有表对应的字段名

```mysql
select column_name from information_schema.columns where table_schema ='chongsheng' and table_name = 'sercurity'; 
```

