# BiliEmoji
 B站表情链接收集
 
如有部分表情遗漏，欢迎提交[issues](https://github.com/lrhtony/biliEmoji/issues)

本项目随缘更新

## 收集方法
通过爬取<https://api.bilibili.com/x/emote/package>进行收集

## 链接使用
图片格式化，详情可参考：<https://github.com/SocialSisterYi/bilibili-API-collect/blob/master/other/picture.md>

## 评论支持
### [Waline](https://waline.js.org)
jsdelivr:(推荐，为防止更新导致图片失效，请将latest替换为准确的版本号)
```
https://cdn.jsdelivr.net/gh/lrhtony/BiliEmoji@latest/src/表情
```
Cloudflare:(可能会因更新导致图片无法显示)
```
https://emoji.lrhtony.cn/src/表情
```
### [Valine](https://valine.js.org)
请直接复制`biliEmoji.txt`文件所需内容进行替换修改

### [MiniValine](https://minivaline.js.org)
链接同Waline
> 注意：此项未经测试，请自行试验后再使用，如有bug请提交[issues](https://github.com/lrhtony/BiliEmoji/issues/new)


## 注意
- 请根据实际使用情况自行更改数据形式，勿将本项目直接应用于生产环境
- 如原表情链接被新表情链接取代，则原链接的名称将改为 `[原表情名]-旧` 的形式（如新表情与旧表情无明显变化，则直接替换链接）

## 声明
该仓库中所有表情的版权归原作者所有