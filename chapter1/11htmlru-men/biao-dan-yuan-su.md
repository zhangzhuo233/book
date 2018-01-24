# 表单元素

form标签

1.input

input:文本text,密码password,单选\(name="gender" type="radio"\),多选checkbox,button,number,date\(建议调用第三方类库\),color,range\(min,max\),带格式校验email,submit提交,url,file\(multiple="multiple"\),

type= text/password/radio/checkbox

maxlength

value

checked表示默认选中（应用于单、多选）

2.select组合标签

下拉列表，option默认选中+selected  
3.textarea

rows,cols属性，设置样式resize：none可设置文本框大小不变

4.button

type,form

type="submit" form="表单的id属性,而不是name属性的值"

type="reset"重置

type="button"普通按钮

palceholder

```
定义和用法
placeholder 属性提供可描述输入字段预期值的提示信息（hint）。

该提示会在输入字段为空时显示，并会在字段获得焦点时消失。

注释：placeholder 属性适用于以下的 <input> 类型：text, search, url, telephone, email 以及 password。
```

```
<form action="demo_form.asp" method="get">
  <input type="search" name="user_search" placeholder="Search W3School" />
  <input type="submit" />
</form>
```



