# Pandollo

自己改了改，原仓库请见fork地址。

---------

更改内容：

- [x] 大部分文案提示改为中文```例如，上一页 / 下一页 , 上一篇 / 下一篇 ，阅读更多```
- [x] 去掉line number
- [x] 去掉代码滚动条

准备更改内容

- [ ] 在没有配置```<!--more-->```的时候，显示文章预览
- [ ] markdown表格显示
- [ ] 引用样式的替换
- [ ] 复选框样式的替换

----------

另外发布时报错
```
Cannot read property 'each' of undefined
```
可能是因为有些文章没有配置tag导致，在配置tag之后可以解决，之后可能也会改一下这里的逻辑。