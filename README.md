# 写在前面

你好，我是李玮，网名里克，2007年开始从事 Rails 开发工作。《Rails 实践：使用 Rails 4 构建在线网店》这本书，是我第一次编写完整的教程，对我来说，它更像是对过往经验的总结。

本书通过一个在线网店程序的开发过程，带领大家了解 Rails 全貌。第一章，我们安装 Ruby 和 Rails 的开发环境，并学习如何设计项目 UI。第二章，我们讲解 Rails 中的资源含义，学习 Rails 如何实现 REST 风格架构，感受 Rails 的快捷开发。第三章，我们关注 Rails 的视图，从页面部分开始了解 MVC 框架。第四章，我们关注数据库部分，讲解 Rails 中的 M。第五章，我们在了解控制器的同时，完成我们网店的购买功能。第六章，我们学习 Rails 中的各种配置，并将它在云服务器上部署运行。

在阅读本书同时，也希望你能阅读其他 Ruby 和 Rails 的教程，博客和新闻，增加知识储备。

> 写出正确的代码是需要理由的。

## 目录

* [写在前面](README.html)
* 第一章 Ruby on Rails 概述
   * [Ruby on Rails 开发环境介绍](Chapter_1/1.1.html)
   * [Rails 文件简介](Chapter_1/1.2.html)
   * [用户界面（UI）设计](Chapter_1/1.3.html)
* 第二章 Rails 中的资源
   * [应用 scaffold 命令创建资源](Chapter_2/2.1.html)
   * [REST 架构](Chapter_2/2.2.html)
   * [深入路由（routes）](Chapter_2/2.3.html)
* 第三章 Rails 中的视图
   * [布局和辅助方法](Chapter_3/3.1.html)
   * [表单](Chapter_3/3.2.html)
   * [视图中的 AJAX 交互](Chapter_3/3.3.html)
   * [模板引擎的使用](Chapter_3/3.4.html)
* 第四章 Rails 中的模型
   * [模型的基础操作](Chapter_4/4.1.html)
   * [深入模型查询](Chapter_4/4.2.html)
   * [模型中的关联关系](Chapter_4/4.3.html)
   * [模型中的校验](Chapter_4/4.4.html)
   * [模型中的回调](Chapter_4/4.5.html)
* 第五章 Rails 中的控制器
   * [控制器中的方法](Chapter_5/5.1.html)
   * [控制器中的逻辑](Chapter_5/5.2.html)
* 第六章 Rails 的配置及部署
   * [Assets 管理](Chapter_6/6.1.html)
   * [缓存及缓存服务](Chapter_6/6.2.html)
   * [异步任务及邮件发送](Chapter_6/6.3.html)
   * [I18n](Chapter_6/6.4.html)
   * [生产环境部署](Chapter_6/6.5.html)
   * [常用 Gem](Chapter_6/6.6.html)
* [写在后面](AFTER.html)

## 电子版

本书电子版为免费阅读，目前有两个指定的发布地址：

独立域名：rails-practice.com （已过期）

极客学院wiki：http://wiki.jikexueyuan.com/project/rails-practice/ （已无法打开）

正式域名：http://rails-practice.railsbook.cn/

## 当前版本

1.1.0

## 2022年7月更新说明

* 启用独立的域名访问
* 增加目录导航，方便阅读

## 2017年2月更新说明

* 书名更新为《Rails 实践：使用 Rails 4 构建在线网店》
* 使用 Docker 作为开发调试环境，增加了 README.md，针对每一份代码有如何创建容器的说明
* Ruby 版本更新为 2.3.3，请使用 `docker pull ruby:2.3.3` 镜像创建容器
* Rails 版本统一更新为 4.2.7.1，请使用 `bundle update rails` 升级当前版本
* 调整项目代码在当前 Ruby 和 Rails 版本下可正常运行
* 更新 gems 数据源为 `https://gems.ruby-china.org`
* 去掉了 .ruby-version 和 .ruby-gemset 两个文件
* 结合大家在 issue 中反馈的问题进行调整
* 精简部分代码
* 修正 bug

## 本书读者

本书适合期望使用 Rails 制作 Web 网站的开发者，读者需要具备基础的 HTML，JS 和 CSS 知识，并且了解 Ruby 基本语法。你可以从未使用过 Ruby 和 Rails，这没关系，本书会带领你从安装 Ruby 环境开始，直到完成这个 Rails 项目。

在学习的过程中，我建议读者注册一个 github.com 账号，建立一个学习笔记的代码仓库（Repo）中。

## 本书约定

* 名词首字母大写。
* 英文缩写大写。
* 命令小写。
* 作为名词时，首字母大写，作为命令时 小写。Rails，Ruby 同。
* 专有名词不翻译。
* 专有名词按照约定书写，如 iPhone，iMac，html，js，css，php，jQuery 等等。
* 中文和英文间留有空格。
* 命令行中，当前用户操作使用 `%` 开头，root 用户操作，用 `$` 开头。

## 版权声明

本书的著作权归作者李玮（署名：里克）所有。

你可以：

* 下载、保存以及打印本书
* 网络链接、转载本书的部分或者全部内容，但是必须在明显处提供读者访问本书发布网站的链接
* 在你的程序中任意使用本书所附的程序代码，但是由本书的程序所引起的任何问题，作者不承担任何责任

你不可以：

* 以任何形式出售本书的电子版或者打印版
* 擅自印刷、出版本书
* 以纸媒出版为目的，改写、改编以及摘抄本书的内容

## 读者反馈

你可以在 [https://github.com/liwei78/rails-practice/issues](https://github.com/liwei78/rails-practice/issues) 页面写下你的问题，也可以留下意见和建议。

## 示例代码

[https://github.com/liwei78/rails-practice-code](https://github.com/liwei78/rails-practice-code)

你可以 `fork` 这份代码到自己的代码仓库（Repo）中，修改并提交，然后向我的代码仓库提交 `Pull Request`，如果修改无异议，我将合并到 master 中。

## 作者介绍

李玮，网名里克，2007年开始从事 Rails 开发，先后经历过社会化搜索引擎 deyeb，华为生活社区百草网，电商平台等开发工作。在某网络安全公司从事产品开发。

工作之余，担任长春心语志愿者协会网络顾问，编程教练以及80学院 Rails 导师。


## 里克的自习室公众号

![](images/railser.jpg)

## 感谢

感谢北京迅思科技及课程树团队中的每位成员。

感谢所有关注过里克的自习室的朋友们。

感谢 [Ruby China 社区](https://ruby-china.org) 让 Ruby 和 Rails 在中国充满活力。
