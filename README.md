# SQL
* 密码 fjy0408<br>
* `show databases；`显示数据库列表<br>
* `use 数据库名;`<br>
* `show tables；`显示tables 列表<br>
* 查询语句；<br>
* `exit；` 退出<br>
		create table table名 （  创建表<br>
		vars char...）；<br>
* `insert` into table_name values()<br>
* `delete` from table_name where ...<br>
* `update` table_name set .. where ...<br>
### 数据类型 https://www.runoob.com/mysql/mysql-data-types.html <br>
### 约束 
* 主键约束  `var primary key`  不为空且不重复<br>
* 联合主键  `primary key (var1,var2)`  不为空且不能同时重复<br>
* 自增约束  `var vartype primary key auto_increment`  不为空且不重复<br>
* 重新定义主键约束 `alter table table_name add primary key(varnamen) <br>
* 删除主键约束  `alter table table_name drop primary key(varnamen) <br>

## 数据库设计范式
*　表中所有字段都是不可分割的原子值（不可拆分） <br>
×　完全依赖主键 <br>
×　其他不存在依赖关系 <br>

＃＃　事物
＊
