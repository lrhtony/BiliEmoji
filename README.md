# BiliEmoji
 B站表情链接收集
 
如有部分表情遗漏，欢迎提交[issues](https://github.com/lrhtony/biliEmoji/issues)，附上表情名称和链接

本项目随缘更新

## 收集方法
通过爬取<https://api.bilibili.com/x/emote/package>进行收集

## 链接使用
图片格式化 ，具体可参考：<https://github.com/SocialSisterYi/bilibili-API-collect/blob/master/other/picture.md>

## 计划
1. 将表情按系列分成各个文件，更加方便调用

## 注意
- 请根据实际使用情况自行更改数据形式，勿将本项目直接应用于生产环境
- 如原表情链接被新表情链接取代，则原链接的名称将改为 `[原表情名]-旧` 的形式


## 关于626 DIY表情
通过<https://api.bilibili.com/x/garb/activity/game/colorfill/sketch/list?game_id=381048529516234241>
获取`emote_id`和各部分的颜色, 然后将`color_list` `emote_id` `package_id`通过`GET`请求发送至<https://api.bilibili.com/x/garb/activity/game/colorfill/emote/preview>，
即可获得相关表情的链接

所有DIY表情的链接（包括线稿）将会在活动结束后统一归到单独的文件中
