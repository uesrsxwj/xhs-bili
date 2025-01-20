# xhs-bili
小红书/哔站/哔站爬虫 数据采集/评论发送/批量点赞/小红书爬虫/js逆向实现/可抓取搜索数据/评论数据/发送评论/发送私信/自动点赞收藏等
## 实现过程
- 通过js逆向破解前端 "x-s": x_s, "x-t"，"x-s-common"，"x-b3-traceid"，"searchId"等参数
- 重构代码逻辑，开箱既用
- 调用python进行api封装
## 功能特性
- 爬虫搜索内容
- 爬取笔记详情
- 爬取笔记图片或者视频
- 采集用户评论（包含二级评论）
- 自动发送评论
- 自动关注，点赞，收藏
- 发送私信
## 2025年1月20号（可用）
![image](https://github.com/uesrsxwj/xhs-bili/blob/main/20%E5%8F%B7%E7%85%A7%E7%89%87.png)
## 基础设置
- 需要用户cookie（账号信息）【数据采集作者提供账号】值进行本账号爬取或发布
- 保存可支持数据库和execl，csv保存
## 一些疑问
- 小红书搜索是不支持指定时间段的，如果需要时间段的数据，只能做数据筛选
- 同一关键词一次只能搜索220条数据，如果需要更多需要多个相近关键词过一会再跑一遍来去重处理，不断积累
## 需要的请添加我（需要收取费用）
- 收费标准: 需要评论数据的2千条数据一块钱，视频数据1块200条,需要一个功能源码的（200元起步），需要功能exe软件[可按需求自定义添加功能]（300元起步【软件定制前需要先付30%押金】）
- WX号:xwj18282514853
### 环境要求
- Python 3.x
- requests：用于发送HTTP请求
- execjs：调用js文件
