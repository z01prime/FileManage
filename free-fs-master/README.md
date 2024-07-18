# Free-Fs — 开源文件管理系统

---


<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/xddcode/free-fs?logo=github)](https://github.com/xddcode/free-fs/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/xddcode/free-fs?logo=github)](https://github.com/xddcode/free-fs/network)
[![star](https://gitee.com/xddcode/free-fs/badge/star.svg?theme=dark)](https://gitee.com/xddcode/free-fs/stargazers)
[![fork](https://gitee.com/xddcode/free-fs/badge/fork.svg?theme=dark)](https://gitee.com/xddcode/free-fs/members)
[![AUR](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg)](https://gitee.com/xddcode/free-fs/blob/master/LICENSE)
</div>

##  📖 项目简介
✨Free-Fs 开源文件管理系统：基于 SpringBoot3.x + MyBatis Flex + MySQL + Sa-Token + Layui 等搭配阿里云Oss、Minio、七牛云等各种云存储实现的云存储管理系统。
包含文件上传、删除、在线预览、云资源列表查询、下载、文件移动、重命名、目录管理、登录、注册、以及权限控制等功能。

#### 源码链接：

- Gitee：[https://gitee.com/xddcode/free-fs](https://gitee.com/xddcode/free-fs)
- GitHub：[https://github.com/xddcode/free-fs](https://github.com/xddcode/free-fs)
- GitCode：[https://gitcode.com/Fr2ed/free-fs](https://gitcode.com/Fr2ed/free-fs)

#### SpringBoot2.x jdk1.8 版本后续不再维护，如需使用请切换至[jdk1.8](https://gitee.com/xddcode/free-fs/tree/jdk1.8/)分支

#### Vue3版本正在开发中......(敬请期待)

#### 在线文档： [前往在线文档](https://doc.elites.chat)

#### 体验地址： [https://fs.elites.chat](https://fs.elites.chat)

#### 内置账号

| 账号    | 密码    |
|-------|-------|
| admin | admin |
| fs    | fs    |

## 📚 项目技术栈

后端：

- 核心框架：Spring Boot 3.3.0
- ORM: MyBatis Flex 1.9.3
- 数据库：MySQL 8.0+
- 权限安全控制：Sa-Token 1.38.0
- 本地缓存：Ehcache
- 存储平台支持：本地存储、Qiniu云、阿里云Oss、Minio、腾讯云Cos、AWS S3
- 第三方登录：JustAuth
- 模板渲染：Thymeleaf
- 
前端：

- Layui v2.5.5
- Jquery
- Ajax


文件在线预览解决方案：

- [kkfileview](https://kkfileview.keking.cn/)

## 🛶 系统设计
![](https://dh_free.gitee.io/images/img/1616399886.png "1616399886.png")

##  💻 项目开发环境
- 操作系统：Windows 11、MacOS
- 构建工具：Maven 3.8.1
- 开发工具：Intellij IDEA
- 应用服务器：Undertow
- 接口测试工具：Postman
- 压力测试工具：Apache JMeter
- 版本控制工具：Github、Gitee
- Java 版本：17+
- idea开发插件: lombok

##  📁 项目模块结构说明

```
  - fs-admin              web管理模块，主要包括对外的api和web配置
  - fs-common             公共模块，包括自定义注解，全局异常处理，公共对象，ORM配置，存储平台sdk的封装，工具类等
  - fs-core               核心模块，包括业务逻辑处理，数据库操作，存储操作等
  - sql                   项目SQL脚本文件
```

##  👀 界面预览
登录页：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141545_ecc0619a_4951941.png "login.png")
注册页：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141609_07de32bf_4951941.png "reg.png")
主页：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141739_a327df31_4951941.png "index.png")
资源操作：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141814_39f4030f_4951941.png "view.png")
目录管理：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141837_3d08629c_4951941.png "dir.png")
重命名：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141853_e968e4a5_4951941.png "rename.png")
添加文件夹：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141910_c98bcc58_4951941.png "addFalod.png")
移动文件或目录：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141929_f5dc52ec_4951941.png "move.png")
删除文件：
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/141941_f77cd13e_4951941.png "delete.png")

##  📧 反馈交流
- QQ交流群：739596094

##  ☎ 联系我
- 有什么问题也可以添加我的微信，请注明来意！
- **加之前请动动小手点一个star，您的支持是我长期维护的动力！**
  ![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/145547_114a3b71_4951941.jpeg "wechat.jpg")

