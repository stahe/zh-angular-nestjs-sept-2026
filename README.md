# RdvMedecins - 使用 NestJS 和 Angular 的客户端/服务器示例

**课程在线地址：[https://stahe.github.io/zh-angular-nestjs-sept-2026/](https://stahe.github.io/zh-angular-nestjs-sept-2026/)**

本仓库只包含这份 README：课程本身发布在上述地址。

## 概述

本课程循序渐进地构建一个完整的医疗预约管理应用程序（“RdvMedecins”）：一个提供 JSON API 的 NestJS/TypeScript Web 服务器、一个 MySQL 数据库，以及一个使用该 API 的 Angular 客户端。最后加入基于 JWT 令牌的身份验证和基于角色（ADMIN/USER）的访问控制。

这是用现代技术对课程 [*客户端/服务器示例 - AngularJS 1.x / Spring 4*](https://stahe.github.io/zh-spring-angular1.x-juillet-2014/)（2014 年）的移植：案例研究相同，分层架构相同，只是把 Java/Spring 服务器换成了 NestJS/TypeScript，把 AngularJS 1.x 客户端换成了 Angular（独立组件、信号）。

## 课程内容

- 搭建开发环境（Node.js、MySQL、Visual Studio Code）并创建数据库；
- NestJS 入门：在案例研究之前，通过一个迷你项目介绍开发模型、装饰器和依赖注入；
- 构建完整的 RdvMedecins NestJS 服务器：TypeORM 实体、DAO 层、业务逻辑层、Web 层（控制器和 JSON 路由）；
- Angular 入门：从 AngularJS 1.x 到当前版本的 Angular、组件、信号、独立组件、依赖注入、HTTP 通信，以及新的流程控制语法（`@if`、`@for`）；
- 完整开发 RdvMedecins 的 Angular 客户端：模型、服务、拦截器、界面的法语/英语翻译、组件；
- 加入基于 JWT 令牌的身份验证和基于角色（ADMIN/USER）的访问控制；
- 结论：总结已构建的内容，并给出进一步探索的建议。

每处代码讲解都使用所展示代码中的确切标识符（表、列、类、装饰器等），以确保准确，并帮助你紧跟示例。

## 先决条件

本文档不假定你具备任何 NestJS 或 Angular 的知识。熟悉 TypeScript 和 Web 开发基础（HTTP、JSON、关系型数据库）会让阅读更轻松。

## 作者
**Anthropic 的 Claude AI**，由 Serge Tahé 审阅 - 2026 年 9 月
