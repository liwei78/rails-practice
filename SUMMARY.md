# 目录

* [写在前面](README.md)
* 第一章 Ruby on Rails 概述
    * [概要](Chapter_1/summary.md)
    * [1.1 Ruby on Rails 开发环境介绍](Chapter_1/1.1.md)
    * [1.2 Rails 文件简介](Chapter_1/1.2.md)
    * [1.3 用户界面（UI）设计](Chapter_1/1.3.md)
* 第二章 scaffold 命令
    * [概要](Chapter_2/summary.md)
    * [什么是 scaffold](Chapter_2/2.1.md)
    * [REST](Chapter_2/2.2.md)
        * 什么是 REST
        * resources 方法
        * CRUD
    * [深入 route](Chapter_2/2.3.md)
        * 嵌套的 routes
        * route 中的 namespace
        * route 中的 module
* 第三章 Rails 中的 View
    * [概要](Chapter_3/summary.md)
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
* 第四章 Rails 中的 Model
    * [概要](Chapter_4/summary.md)
    * CRUD
    * Migration
    * 避免 N + 1
    * 慎用 scope
* 第五章 Rails 中的 Model 关联
    * [概要](Chapter_5/summary.md)
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
* 第六章 Model 中的校验
    * [概要](Chapter_6/summary.md)
    * 触发 validations
    * 不触发 validations
    * valid? 和 invalid?
    * errors
    * 校验中的辅助选项
    * 操作 errors
    * 在 views 显示 errors 信息
* 第七章 深入 Model
    * [概要](Chapter_7/summary.md)
    * callback
    * 动态查询
    * Find by SQL
    * exists?
    * 计算
    * explain
* 第八章 Rspec 测试 Model
    * [概要](Chapter_8/summary.md)
    * CURD 测试
    * relations 测试
    * validations 测试
* 第九章 Rails 中的 Controller
    * [概要](Chapter_9/summary.md)
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
* 第十章 Rails 加分项
    * [概要](Chapter_10/summary.md)
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
* 第十一章 在云服务器部署 Rails
    * [概要](Chapter_11/summary.md)
    * 云服务器上部署代码
    * cap









