# BiliEmoji
 B站表情链接收集
 
如有部分表情遗漏，欢迎提交[issues](https://github.com/lrhtony/biliEmoji/issues)，附上表情名称和链接

本人是个收集控，所以才将这些表情的链接收集起来。

本项目随缘更新

## 收集方法
登录B站账号，访问<https://api.bilibili.com/x/emote/setting/panel?business=reply>，即可获取可添加（购买）全部表情的链接。正则表达式提取，最后再修正一下奇怪的表情名称（少字、奇怪的空格等），就提取出了这份总链接。部分限时表情在平时刷B站时收集。

## 链接使用
直接使用或者在链接后加入`@[int]w_[int]h.webp`或`@[int]w_[int]h.png`来获取相应像素大小的表情，`[int]`中填入所需表情的像素大小，以最小的数字为准。表情图片最大只能获取到该图片的原像素大小，如在一般情况下，“小黄脸”、“tv”为`96x96`，其余为`162x162`

例子:
`https://i0.hdslb.com/bfs/emote/02ea49543a3ac52feee185c156ab08fb2bfdd89e.png@162w_162h.webp`
`https://i0.hdslb.com/bfs/emote/c32d39db2737f89b904ca32700d140a9241b0767.png@96w_96h.png`

> 收集不易，如果觉得不错就点个star吧！ヾ(≧▽≦*)o