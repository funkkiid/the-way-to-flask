The Way To Flask
=======

> 本开源书 forked from [The Way To Flask](https://github.com/yetship/the-way-to-flask)，作者为 [yetship](https://github.com/yetship)，欢迎大家 star 原作者的 [repo](https://github.com/yetship/the-way-to-flask)，以便获得最新更新，谢谢！

### 本文目标

通过讲解 Flask 以及它的扩展们，介绍通用用法以及使用过程中的问题和坑，帮助读者使用 Python 编程语言快速得开发健壮的 Web（API）服务端程序。本书在编写之初以及编写过程中始终坚持以下几条原则：

- 让 Python 初学者/会其他语言但没用过 Python 的人能快速入手
- 循序渐进得让读者感受 Flask 的简便与强大
- 以生动有趣的语言讲述 Flask 从入门到着迷

## Flask 简介

Flask 是一个使用 Python 编写的轻量级 Web 应用框架，核心的思想就是自身尽可能提供少的东西，作为一个微框架，将更多的内容以插件的形式提供，因此，衍生出了一系列以 Flask 为核心的 插件。截止至2016年06月02日，在 [Github](https://github.com/pallets/flask) 上已有 **20730** 个星，**6426** 个 Fork 以及 **1511** 个 Watch。

通过使用 pip 包管理工具统计，Flask 的扩展已经达到 **800+**，涵盖大部分日常工作使用到的内容。

### 声明

本文由 [Yetship](https://liuliqiang.info) 编写，使用 [GNU FDL v1.3 Licence](http://www.gnu.org/licenses/fdl-1.3.html) 发布，如有转载、商业使用等用途，请在 Licence 的约束下进行，本人保留一切权利。

### 联系我

如果对本书提到的知识点有不解或者觉得有误，可以根据以下联系方式与我联系，同时，欢迎大家一起编撰修改本书，让更多的人能够喜爱 Flask。

- 主页：https://liuliqiang.info
- 邮箱：liqianglau@outlook.com
- HomePage: http://www.liuliqiang.info/book/
- GitHub: https://github.com/luke0922/the-way-to-flask.git

### 更新记录

## Version 1.0

- date： 2016-6-2
- desc： 终于在一个多月的时间里完成了第一版，期间发生了很多事情，但是，还是坚持下来了，完成了第一版的《The Way To Flask》，虽然个人觉得还有很大的改进空间，但至少是有这么粗糙的一版，后面有什么问题，可以根据大家的建议进行改进。

## Version 1.1
- date: 2016-6-11
- desc: 在 Pycon2016 上观看了《Flask at Scale》的讲解，对 Flask 的项目有了更多的一些理解，发现了 V1.0 的内容已经符合可维护性的要求，在这个版本中新加入优化性能的部分。

## Version 1.2
- begin: 2017-03-01
- end: 2017-03-01
- desc：修改一些文档的错误

## Version 1.3
- begin: 2017-05-01
- end: 2017-05-01
- desc: 转移到 Mkdocs
