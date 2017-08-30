### EMD 规范

- img必须设定宽、高、边框及border=0;valign="top"
- 页面字符集写成utf-8；文件保存编码类型也必须为utf-8。
```
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
```
- 所有颜色值要设置6位，不要设置简写
- margin属性也最好不用
- 火狐邮箱文字align=“center”无法居中，要设置text-align:center
- p标签的行间距在不同的邮箱显示会不一样会增大，可用span标签代替
- 某些邮箱不支持背景图，要用img
- tr可以设置的样式：background-color，不能设置border