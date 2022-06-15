# local-editor
一个纯本地的编辑器，自动保存输入的内容到 lolocalStorage

[线上demo](https://encode.zggmd.com/local-editor/)

# 如果你不需要输入内容的自动保存功能
在浏览器地址栏里直接输入 data:text/html,%20%3Chtml%20contenteditable%3E

下次进入地址栏输入 data 即可联想出地址

# 原理
1. 将 <html/> 设为 contenteditable，整个页面都可编辑了
2. 在页面关闭前将 body 中的内容存到 lolocalStorage 中
3. 页面重新打开时候，读取 lolocalStorage 中内容并恢复
# 样式说明
- 比较喜欢黑色主题，所以将背景字体样式改为了 github 的黑暗风格，而且 默认字体做了放大，适合视力不好的
