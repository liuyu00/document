# mysql
mysql是一个关系型数据库管理系统，在mysql中以表的形式管理数据，一个数据库由若干表组成，一个数据表由行和列组成，一个表中可以存放无数条数据

数据库: 数据库是一些关联表的集合（若干张表）。
数据表: 表是数据的矩阵。在一个数据库中的表看起来像一个简单的电子表格。
列: 一列(数据元素) 包含了相同类型的数据, 例如邮政编码的数据。
行：一行（=元组，或记录）是一组相关的数据，例如一条用户信息的数据（ID、名字，头像、手机号、....）。
主键：主键是唯一的。一个数据表中只能包含一个主键。你可以使用主键来查询数据（每一条数据的唯一标识）。
外键：外键用于关联两个表。
复合键：复合键（组合键）将多个列作为一个索引键，一般用于复合索引。
索引：使用索引可快速访问数据库表中的特定信息。索引是对数据库表中一列或多列的值进行排序的一种结构。类似于书籍的目录。
参照完整性: 参照的完整性要求关系中不允许引用不存在的实体。与实体完整性是关系模型必须满足的完整性约束条件，目的是保证数据的一致性。

# 操作数据库
操作数据库的语言称为sql语言，可以实现数据的crud（增删改查）

插入：
INSERT INTO 表名 (列名, 列名, 列名, ...) VALUES (值, 值, 值, ...)
查询：
SELECT * FROM 表名
删除
DELET FROM 表名 WHERE id=1
更新
UPDATE 表名 SET name='你好', price=100  WHERE id=1

# 数据类型
在mysql中数据只有3总类型（数值、字符串、日期）