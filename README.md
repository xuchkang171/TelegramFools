# Telegram Fools Client

本项目是一个开源的第三方 Telegram Client。

## 增强搜索

### 支持中文搜索

### 支持消息搜索语法

筛选作者 
`from:username`

筛选时间
`since:2010-1-1`
`until:2017-12-31`

筛选含有链接的消息
`filter:links`

筛选含有图片的消息
`filter:images`

筛选含有视频的消息
`filter:Videos`

筛选给他人的回复
`to:username`

### 统一搜索

* User
* Message
* Group (Public)
* Channel (Public)
* Bot

连接各大「群组信息整合 bot/website」。查找 Group/Channel 的需求现在也可以直接在主界面搜索框中完成了。
![Alt text](https://i.imgur.com/PkDjAiG.png)

## 去掉令你反感的消息

### 选项：屏蔽已 Block 用户在 Group 中的发言

开启后，已 Block 用户除了 Telegram 原有的禁止其 PM 外，其在 Group 中的发言也会被（本地）屏蔽：
![Alt text](http://i.imgur.com/1miLlCO.png)

鼠标指向「2 messages muted」可预览被屏蔽的消息，点击恢复显示原消息。
也可以设置为「屏蔽且无任何提示」。

### 选项：Group 中 Sticker 替换为 Emoji

Group 中用户发送 Sticker 太频繁打乱交流？开启该选项后，Group 中用户发送的 Sticker 消息将替换为其对应 Emoji，鼠标指向即预览原图，点击即恢复原始 Sticker 消息，再点击 Sticker 可如原版一样查看、添加 Sticker pack。

### NO NOTIFICATION

![Alt text](http://i.imgur.com/pTODNu6.png)

GROUP 的 NOTIFICATION 关闭后，GROUP 消息无提醒。
PIN 也不例外！
收到 Pin 消息仅在 Chat 列表中如上特殊标识。

## 内置通知中心

默认 24 小时内的消息通知都保留在通知中心，如果错过了消息通知，可以在这里查看，点击跳转到原消息处。
保留期限可自定义。

## 任意 Pin to top

没有数量限制。

通过 Telegram Fools Client 设置的前 5 个 Pin Chat 与 Telegram Server 同步，之后的 Pin Chat 仅本地有效。

## 消息流显示模式选项：舒适/紧凑

![Alt text](http://i.imgur.com/LUo4ZFx.png)

「紧凑」模式下不显示头像，消息显示格式如上右图示：
> [time] [nickname] [message]

## 主题选项: 黑/白

![Alt text](http://i.imgur.com/jW44OGg.png)

## 视频点击即播放

边下边播，无需等待下载完成。

## 项目进度

本项目主要分为 Markdown 部分和代码部分。
目前已完成 Markdown 部分。
进度：50%。

![Alt text](http://i.imgur.com/mU2OFua.png)

## License

This project is licensed under the [WTFPL](http://www.wtfpl.net/).