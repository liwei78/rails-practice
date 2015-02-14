#《Rails 实践》前言

我是里克，从事 Rails 开发有将近八年的时间了，目前，我正在编写《Rails 实践》这本教程，这是我第一次编写完整的教程，对我来说，它的意义更在于对过往经验的总结。

本书内容基于极客学院 《Rails 实践》系列视频的文字稿整理而成，在编写时，一遍整理视频内容，一遍整理知识点和文字讲稿，希望两者互相补充，做到有条有理。

本书的设计想法，是通过一个 shop 项目的实际开发过程，带领大家了解 Rails 全貌，并能独立完成项目交付。其中，还增加了项目设计思想和敏捷开发的理念。我不主张所谓的由浅入深，在实际项目开发中，我提倡做“正确的选择”。所以每一个环节，我会从实践开发入手，在讲解知识点的同时，我们会从`项目设计`开始，到`项目实现`结束。最后，还会带领大家实际部署运行这个项目。

> 我相信，写出正确的代码是需要理由的。

希望这本书，可以帮助初次接触 Rails 的开发者，并希望大家可以用 Rails，做出更多优秀的项目。

再次，感谢你的关注，我将尽力做的更好。

2015年2月21日更新

# 本书约定

* 名词首字母大写
* 英文缩写大写
* 命令小写
* 作为名词时，首字母大写，作为命令时 小写。Rails，Ruby 同。
* 专有名词不翻译，比如 views 特指 Rails 中的视图，model 指数据库模型，controller 指控制器，helper 指辅助方法。这些作为 Rails 特有概念直接使用英文单词。

# 目录

* 1 [Ruby on Rails 概述](Chapter_1/summary.md)
    * [Ruby on Rails 开发环境介绍](Chapter_1/1.1.md)
    * [Rails 文件简介](Chapter_1/1.2.md)
    * [用户界面（UI）设计](Chapter_1/1.3.md)
* 2 [scaffold 命令](Chapter_2/summary.md)
    * [什么是 scaffold](Chapter_2/2.1.md)
    * [REST](Chapter_2/2.2.md)
        * 什么是 REST
        * resources 方法
        * CRUD
    * [深入 route](Chapter_2/2.3.md)
        * 嵌套的 routes
        * route 中的 namespace
        * route 中的 module
* 3 [Rails 中的 View](Chapter_3/summary.md)
    * scaffold 创建的 views
    * 常用的 tag
    * yield 和 content_for
    * partial，局部模板
    * helpers， 辅助方法
    * form_for
    * form 中的 helper
    * 上传文件
    * 使用 js.erb 响应 ajax form 请求
    * 使用 jquery callback 响应 ajax form 请求
    * views 中不要做的几件事
    * haml，一个清洁的方案
    * 安全的 liquid
    * sanitize，让页面变得安全
* 4 [Rails 中的 Model](Chapter_4/summary.md)
    * CRUD
    * Migration
    * 避免 N + 1
    * 慎用 scope
* 5 [Rails 中的 Model 关联](Chapter_5/summary.md)
    * 关联
    * None
    * 多态关联
    * Self Joins
    * belongs_to 建立关联
    * belongs_to 选项
    * belongs_to 使用 scopes
    * has_one 建立关联
    * has_one 选项
    * has_one 使用 scopes
    * has_many 建立关联
    * has_many 选项
    * has_many 使用 scopes
    * 自动保存
    * has_and_belongs_to_many
    * has_and_belongs_to_many 选项
    * has_and_belongs_to_many 使用 scope
    * has_and_belongs_to_many 何时保存
    * 关联中的 callback
    * 扩展关联方法
    * 单表继承
* 6 [Model 中的校验](Chapter_6/summary.md)
    * 触发 validations
    * 不触发 validations
    * valid? 和 invalid?
    * errors
    * 校验中的辅助选项
    * 操作 errors
    * 在 views 显示 errors 信息
* 7 [深入 Model](Chapter_7/summary.md)
    * callback
    * 动态查询
    * Find by SQL
    * exists?
    * 计算
    * explain
* 8 [Rspec 测试 Model](Chapter_8/summary.md)
    * CURD 测试
    * relations 测试
    * validations 测试
* 9 [Rails 中的 Controller](Chapter_9/summary.md)
    * request 和 response
    * 资源复数命名
    * 继承自 ApplicationController
    * 参数 parameters
        * query string
        * post
        * Hash
        * JSON
        * route 中的参数
        * strong parameters，安全的参数
    * session 和 cookie
        * session
        * session key
        * secret_key_base
        * 赋值
        * flash
        * flash.now
        * cookies
        * custom flash type
    * controller 实践
        * 返回特定结果
        * filters
        * 保护 controller 中的方法
    * 其他
        * request object
        * response object
        * etag
    * 如何弄乱 controller
        * 如何控制 C 里的业务逻辑
        * 如何管理 controller
    * Controller 测试
* 10 [Rails 加分项](Chapter_10/summary.md)
    * assets
        * 文件位置
        * .erb
    * email
    * active job
    * i18n
        * 配置
        * 读取
    * Rake 任务
    * debug
        * views 中测试
        * 代码中测试
    * OH, gem
    * js 和 ujs
    * 完成我们的 Rspec
    * 安全的 Rails
    * git
    * github，你的最佳简历
* 11 [在云服务器部署 Rails](Chapter_11/summary.md)
    * 云服务器上部署代码
    * cap









