# 目录

* [前言](README.md)
* [Ruby on Rails 概述](Chapter_1/summary.md)
    * [Ruby on Rails 开发环境介绍](Chapter_1/1.1.md)
    * [Rails 文件简介](Chapter_1/1.2.md)
    * [用户界面（UI）设计](Chapter_1/1.3.md)
* [scaffold](Chapter_2/summary.md)
    * [scaffold](Chapter_2/2.1.md)
    * [REST](Chapter_2/2.2.md)
        * 什么是 REST
        * resources 方法
        * CRUD
    * [深入 route](Chapter_2/2.3.md)
        * 嵌套的 routes
        * route 中的 namespace
        * route 中的 module
* Rails 中的 View
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
* Rails 中的 Model
    * CRUD
    * Migration
    * query
    * 避免 N + 1
    * 慎用 scope
* Rails 中的 Model 关联
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
* Model 中的校验
    * 触发 validations
    * 不触发 validations
    * valid? 和 invalid?
    * errors
    * 校验中的辅助选项
    * 操作 errors
    * 在 views 显示 errors 信息
* 深入 Model
    * callback
    * 动态查询
    * Find by SQL
    * exists?
    * 计算
    * explain
* Rspec 测试 Model
    * CURD 测试
    * relations 测试
    * validations 测试
* Rails 中的 Controller
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
* Rails 加分项
    * assets
        * 文件位置
        * .erb
    * email
    * active job
    * i18n
        * 配置
        * 读取
    * rake
    * debug
        * views 中测试
        * 代码中测试
    * OH, gem
    * js 和 ujs
    * 完成我们的 Rspec
    * 安全的 Rails
    * git
    * github，你的最佳简历
* 在云服务器部署 Rails
    * 云服务器上部署代码
    * cap









