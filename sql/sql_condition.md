# sql条件的使用

## in

### oracle

https://docs.oracle.com/en/database/oracle/oracle-database/12.2/sqlrf/IN-Condition.html#GUID-C7961CB3-8F60-47E0-96EB-BDCF5DB1317C



### MySQL

https://blog.csdn.net/happygan520/article/details/108335714

IN()列表中值的数量仅受该max_allowed_packet值限制 。

不同版本的值不相同：*

版本	参数	默认值	官网链接
5.7	max_allowed_packet	默认4MB	https://dev.mysql.com/doc/refman/5.7/en/server-system-variables.html#sysvar_max_allowed_packet
8.0	max_allowed_packet	默认64MB	https://dev.mysql.com/doc/refman/8.0/en/server-system-variables.html#sysvar_max_allowed_packet
