# Meteor 官方指南中译本

[![Build Status](https://travis-ci.org/ourmeteor/guide-zh.svg?branch=master)](https://travis-ci.org/ourmeteor/guide-zh)

[阅读指南中译官方版](http://guide.meteor.com/zh_cn)

[阅读指南中译开发版](http://guide-zh.ourmeteor.com/)

>开发版为本 repo `master` 分支最新内容，不保证正确性，请谨慎翻阅。

## 支持

本 repo 由志愿者共同维护，同时也欢迎捐款。

每收到￥66 捐款，laosb 将翻译一篇指南，并保持翻译维护半年，单笔达￥66 的可以指定指南中的篇目。所有资助者将默认列入 [SPONSORS.md](SPONSORS.md)，以示感谢。

对于每一个 review 合格的篇目 PR，合并后将给予 PR 提交者￥60 奖励。所有捐款的收支明细均公开。

## 注意

本 repo 已合并至 `meteor/guide`。由于 MDG 尚未提出有效的翻译/本地化管理方案，所有翻译请继续提交至本 repo，我们将会不定期同步至官方版。

## 如何贡献翻译

首先查看[这里](https://github.com/ourmeteor/guide-zh/wiki/%E7%BF%BB%E8%AF%91%E5%AE%89%E6%8E%92)以了解翻译情况。

请在 Issues 认领翻译段落，以防止同时翻译。

在本地运行这个站点，请参考 http://guide-zh.ourmeteor.com/CONTRIBUTING.html 。

通过提交 PR 的方式贡献翻译。PR 合并后网站即会更新。

### 翻译规范

翻译术语时请参照[术语表](https://github.com/ourmeteor/guide-zh/wiki/%E6%9C%AF%E8%AF%AD%E8%A1%A8)。可以按照语境有所调整。

#### 中西混排

* 保留原文时，保留对应的单复数形式，但不保留语态，如：「We linted our code. Publications worked.」应译为「我们 lint 了代码。Publications 工作正常。」

#### 哪些保留原文

* 术语表里规定的。
* 代码，或者说所有包在反引号里的内容。
* 品牌、产品名、人名、地名等特殊名词，如果来自英文，请使用英文以避免在不同译法之间选择。
* 去往其他语言的博客、论坛等站外链接，且链接显示内容为目标的标题的。如「[所有 ecmascript 包支持的 ES2015 特性](https://docs.meteor.com/packages/ecmascript.html#Supported-ES2015-Features)」应该予以翻译，「[Getting started with ES2015 and Meteor](http://info.meteor.com/blog/es2015-get-started)」不需要。

#### 中文、英文、数字混排时空格的使用

* 英文与非标点的中文之间需要有一个空格，如「Meteor 是一个用于开发现代网页和移动应用的全栈 JavaScript 平台。」而不是「Meteor是一个用于开发现代网页和移动应用的全栈JavaScript平台。」。
* 数字与非标点的中文之间需要有一个空格，如「我们发布了 5 个产品」而不是「我们发布了5个产品」。 正确：「这是 1 款 Android 应用」，错误：「这是1款Android应用」。 正确：「2014 年 2 月 14 日」，错误：「2014年2月14日」。
* 尽可能使用中文数词，特别是当前后都是中文时。上面的例子写为「我们发布了五个产品」会更好。
* 除了「%」、「°C」、以及倍数单位(如 2x、3n)之外，其余数字与单位之间需要加空格。
* 书写时括号中全为数字，则括号用半角括号且首括号前要空一格，例如「联系人 (22)」。

#### 标点相关

* 只有中文或中英文混排中，一律使用中文/全角标点。
* 中英文混排中如果出现整句英文，则在这句英文中使用英文/半角标点。
* 中文标点与其他字符间一律不加空格。 正确：「有：Apple、Android、诺基亚」错误：「有：Apple 、 Android 、 Nokia」
* 中文中使用中文引号「」和『』，其中「」为外层引号。Mac 上如「搜狗输入法」等都可以方便地输入中文引号。
* 省略号请使用「……」标准用法，不要使用「。。。」 ，也不要使用三个英文句点「.」。
* 感叹号：请勿使用「！！」。尽量避免使用「！」。请先冷静下来再坐电脑前敲键盘。
* 波浪号：请勿在文章内使用「~」，活泼地卖萌有很多其他的表达方式。

#### 译注

由于国情特殊，可以在翻译中以块级引用的方式添加译注。如：

```markdown

> 译注：若上述地址无法使用，可以尝试使用 `curl http://install-cn.ourmeteor.com/1.3.2.4 | sh`。其中 `1.3.2.4` 是版本号，我们将保持它更新到最新版。

```
