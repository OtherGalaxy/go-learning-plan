# Go语言学习计划清单

## 总体目标

掌握Go语言基础与高级开发技巧，快速迁移现有的Web开发经验，最终自主实现并部署一个基于Go语言的论坛网站，作为毕业设计项目，7月进组时可以快速上手公司业务。

## 学习目标

- [x] 熟练掌握Go语言语法、特性与最佳实践
- [ ] 掌握Go常见Web框架Gin和Echo
- [ ] 熟悉数据库连接、ORM框架GORM使用
- [ ] 具备独立开发、测试、部署完整Go语言Web应用的能力

## 阶段性学习计划

### 第一阶段：基础入门

- [x] Go环境搭建
  - [x] 安装和配置Go语言环境
  - [x] 熟悉Goland IDE的使用
- [x] Go基础语法
  - [x] 变量声明与初始化
  - [x] 数据类型（整型、浮点型、字符串、布尔型、切片、映射）
  - [x] 运算符与表达式
- [x] 流程控制
  - [x] 条件语句：if、switch
  - [x] 循环语句：for、range
  - [x] 跳转语句：break、continue、goto
- [x] 函数基础
  - [x] 函数定义与调用
  - [x] 参数传递方式（值传递、引用传递）
  - [x] 返回值与多返回值函数
  - [x] 匿名函数与闭包

**成果物**：

- [x] 使用Go语言通过Leetcode经典算法题

### 第二阶段：进阶语法与特性

- [x] 结构体与接口
  - [x] 结构体的定义与使用
  - [x] 方法与方法集
  - [x] 接口的定义与实现
  - [x] 类型断言与类型转换
- [x] 错误处理机制
  - [x] Go中的error类型
  - [x] panic与recover机制
- [x] 并发编程
  - [x] goroutine使用方法
  - [x] channel通信机制
  - [x] sync包与并发控制（Mutex、WaitGroup、Once）
  - [x] 并发安全数据结构（sync.Map）
- [ ] Go模块化管理
  - [ ] Go Modules工具使用
  - [ ] 模块依赖与版本管理

**成果物**：

- [ ] 基于goroutine和channel实现的并发网络爬虫程序

### 第三阶段：Go Web框架与数据库

- [ ] Web框架Gin
  - [ ] Gin框架核心使用（路由、中间件、上下文Context）
  - [ ] 错误处理与异常捕获
  - [ ] 请求参数绑定与数据验证
  - [ ] 文件上传与下载
- [ ] 数据库ORM操作
  - [ ] GORM基础用法（连接数据库、定义模型、基本CRUD操作）
  - [ ] 复杂查询（预加载、关联、事务处理）
  - [ ] 数据库迁移与版本控制

**成果物**：

- [ ] 使用Gin和GORM搭建的简单Web后台应用程序

### 第四阶段：综合实践——论坛网站开发

- [ ] 系统设计与需求分析
  - [ ] 功能模块详细设计（用户管理、帖子管理、评论管理、后台管理）
  - [ ] 数据库详细表结构设计
- [ ] 用户管理系统
  - [ ] 用户注册、登录、权限角色管理
  - [ ] JWT认证集成
- [ ] 帖子与评论管理
  - [ ] 实现帖子发布、编辑、删除、查看功能
  - [ ] 实现评论回复、点赞、管理功能
- [ ] 后台管理系统
  - [ ] 用户审核管理
  - [ ] 内容审核及违规处理
  - [ ] 数据统计与报表生成
- [ ] 项目部署
  - [ ] 使用Docker容器化部署
  - [ ] Linux服务器部署与维护
  - [ ] 性能优化、日志监控与异常处理

**成果物**：

- [ ] 已上线运行的论坛网站，提供源代码、系统设计文档及部署使用说明

## 预计成果物汇总

- [x] 使用Go语言通过Leetcode经典算法题
- [ ] 并发网络爬虫程序
- [ ] 基于Gin和GORM的简单Web后台应用程序
- [ ] 上线运行的论坛网站（源代码、设计文档、部署与使用说明）

## 最终目标

成功完成基于Go语言的论坛网站开发与部署，实现论坛基础功能发帖、评论、用户管理、权限管理，具备高性能和良好的扩展性，达到毕业设计标准并顺利通过答辩。
