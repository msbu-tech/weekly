# 业内技术周刊

* 周刊：<https://msbu-tech.github.io/weekly/>
* 订阅：<https://msbu-tech.github.io/weekly/feed.xml>
* 收集：<https://github.com/msbu-tech/weekly/issues>

## 规范

* 周刊每周二发行，节假日除外，前一个周五会基本确定本期内容。
* 周刊会邮件发送大组，并发布到 <https://msbu-tech.github.io/weekly/>。
* 投稿内容包括但不仅限于 MSBU 相关 Web，App，大数据，人工智能，开发模式，测试，运维，工具在内的自媒体、博客、框架、新闻、教程等。
* 投稿需要包含：文章标题、文章链接、评语或简介和标签。其中，简介可以引用原文内的句子；标签最好在3-5个左右。
* 投稿统一在本 Repo 的 Issues 中进行，直接在响应日起的 Issue 中回复，请不要发 PR 给 `msbu-tech.github.io`。
* 请尊重知识产权，主动抵制_抄袭、侵权和盗版_的内容。
* MSBU Tech Group 成员每周至少推荐__两篇__；非 MSBU Tech 成员也可以参加，其它 GitHub 用户也可以投稿。后续，可能会在周刊中加入投稿人感谢页面。
* MSBU Tech Group 成员可以选择加入 `weekly team`，参加项目维护。

## 投稿

MSBU Weekly 目前启用纯自动化方式投稿，投稿人需要在周二发版前在本 Repo 的 Issues 中回复文章收集贴。如果文章收集贴尚未创建，请自行创建或通知管理员创建。

投稿时直接回复当前收集贴，格式如下：

* 回复内容第一行必须是 `/post`
* 回复内容第二行到第五行是内容需要以减号 `-` 开头（GitHub 会渲染成列表）
* 回复内容第二行是标题
* 回复内容第三行是链接
* 回复内容第四行是介绍语
* 回复内容第五行是标签，以英文半角逗号分隔 `,`
* 投稿人会自动根据回复者 ID 抓取

示例：

```
/post
- 疯狂的JSONP
- http://www.cnblogs.com/twobin/p/3395086.html
- 何为跨域？何为JSONP？JSONP技术能实现什么？是否有必要使用JSONP技术？
- javascript, jsonp, 跨域
```