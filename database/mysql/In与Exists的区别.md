### In关键字
```sql
select * from A where id in (select id from B)
```
**等价于**
```sql
select id from B;
select id from A where A.id = B.id
```
执行过程：
* 先查询内表【select id from B】
* 再把内表结果与外表 【select * from A where id in ...】进行匹配

> **in查询使用内表作为驱动，把内表结果与外表结果匹配，对外表使用索引，对内表多大都需要查询，外表使用索引，故当外查询的数据集大于内查询的数据集时，用in优于exists**  
### Exists关键字
```sql
select * form A where exists (select 1 from B where B.id = A.id)
```
**等价于**
```sql
select A.id from A;
selet id from B where B.id = A.id
```
执行过程：
* 首先对外表【select * from A ...】 做loop循环
* 每次loop循环再对内表【select 1 from B where B.id = A.id】进行匹配

> **exists查询使用外表作为驱动，基于外表的每条数据对内表进行查询，内表使用索引，外表多大都需要遍历，内表使用索引，故当外查询的数据集小于内查询的数据集时，用exists优于in**  


### 总结 ###

**当外表的数据集大于内表的数据集时，用in优于exists；**  
**当外表的数据集小于内表的数据集时，用exists由于in；**  
**子查询表大的用exists，子查询表小的用in**


