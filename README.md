# sql-translator
sql转换工具，sql翻译，sql格式化，支持oracle转mysql，后续支持各种数据库的sql互转。为项目迁移及跨库支持提升效率迭代。 如果有兴趣，点个star关注一下，谢谢

# 特点

灵活性高，可定制化。

可嵌入项目，可底层拦截sql，轻松转换。

# 支持特性
#### 1. 支持oracle语法转Mysql语法

#### 2. 支持在表名前动态配置用户名
> 由于在项目中的表名一般不会使用[user].tableName, 但是在某些不跨库场景下，需要在A用户下，去访问B用户的表时。就需要根据表名来动态加上用户B。


