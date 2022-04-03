# BiliEmoji
 B站表情链接收集

这是一个收集B站表情的仓库，主要用于各评论系统。当然，你也可以直接下载使用。
 
如有部分表情遗漏，欢迎提交[issues](https://github.com/lrhtony/biliEmoji/issues)

目前不对UP主大表情进行收集，未来有机会的话可能会搭建api（挖坑+1）

本项目随缘更新

## 收集方法
通过爬取<https://api.bilibili.com/x/emote/package>进行收集
详细信息可参考：[SocialSisterYi/bilibili-API-collect](https://github.com/SocialSisterYi/bilibili-API-collect/blob/master/emoji/list.md#%E8%8E%B7%E5%8F%96%E6%8C%87%E5%AE%9A%E7%9A%84%E8%A1%A8%E6%83%85%E5%8C%85%E6%98%8E%E7%BB%86)

## 链接使用
图片格式化，详情可参考：<https://github.com/SocialSisterYi/bilibili-API-collect/blob/master/other/picture.md>

## 评论支持
### [Waline](https://waline.js.org)
jsdelivr（支持版本控制）:
```
https://cdn.jsdelivr.net/gh/lrhtony/BiliEmoji@master/src/表情
https://fastly.jsdelivr.net/gh/lrhtony/BiliEmoji@master/src/表情
https://gcore.jsdelivr.net/gh/lrhtony/BiliEmoji@master/src/表情
```
Cloudflare（自测最快）:
```
https://emoji.shojo.cn/bili/src/表情
```

### [Valine](https://valine.js.org)
请直接复制`biliEmoji.txt`文件所需内容进行替换修改

### [MiniValine](https://minivaline.js.org)
链接同Waline


## 注意
- 请根据实际使用情况自行修改，勿将本项目直接应用于生产环境
- 如原表情链接被新表情链接取代，则原链接的名称将改为 `[原表情名]-旧` 的形式（如新表情与旧表情无明显变化，则直接替换链接）

## Todo
- [ ] ~~支持twikoo~~支持[OwO](https://github.com/DIYgod/OwO)
- [ ] 小黄脸和热词系列一表情列表与B站保持同步，全表情则另开文件夹

## 声明
该仓库中所有表情的版权归原作者所有