
<p align="center">
 <img alt="JeeSite" src="https://jeesite.com/assets/images/logo.png" width="120" height="120" style="margin-bottom: 10px;">
</p>
<h3 align="center" style="margin:30px 0 30px;font-weight:bold;font-size:30px;">快速开发平台 - Spring Boot</h3>
------

## 技术选型

* 主框架：Spring Boot 2.7、Spring Framework 5.3、Apache Shiro 1.12、J2Cache
* 持久层：Apache MyBatis 3.5、Hibernate Validator 6.2、Alibaba Druid 1.2
* 视图层：Spring MVC 5.3、Beetl 3.10（替换JSP）、Bootstrap 3.3、AdminLTE 2.4
* 前端组件：jQuery 3.7、jqGrid 4.7、layer 3.5、zTree 3.5、jQuery Validation
* 分离前端版：Node.js、TypeScript、Vue3、Vite、Ant Design Vue、Vue Vben Admin
* 工作流引擎：Flowable 6.6、符合 BPMN 规范、在线流程设计器、中国式流程、退回、撤回、自由流
* Bootstrap 版 支持 IE9 及以上版本及其他所有现代浏览器，如：谷歌、火狐、国产浏览器 等
* Vue3 版 支持现代浏览器，如：谷歌 Chrome 86+、火狐、国产浏览器 等
* 技术选型（详细）：<http://jeesite.com/docs/technology/>
* JeeSite Vue 版本：<https://gitee.com/thinkgem/jeesite-vue>
* Spring Boot 3.x 版本：<https://gitee.com/thinkgem/jeesite5/tree/v5.springboot3>

## 更多介绍

* 内置功能：<https://jeesite.com/docs/function/>
* 目录结构：<https://jeesite.com/docs/catalog/>
* 架构特点：<https://jeesite.com/docs/feature/>
* 开发规范：<https://jeesite.com/docs/standard/>
* 代码生成：<https://jeesite.com/docs/code-gen/>

## 生态系统

* 分布式微服务（Spring Cloud）：<https://gitee.com/thinkgem/jeesite-cloud>
* Flowable业务流程引擎（BPM）：<http://jeesite.com/docs/bpm/>
* 多站点内容管理模块（CMS）：<https://jeesite.com/docs/cms/>
* 手机端移动端：<https://gitee.com/thinkgem/jeesite-uniapp>
* PC客户端程序：<https://gitee.com/thinkgem/jeesite-client>
* Vue3分离版本：<https://gitee.com/thinkgem/jeesite-vue>
* JeeSite统一认证：<https://jeesite.com/docs/oauth2-server>
* JFlow工作流引擎：<https://gitee.com/thinkgem/jeesite-jflow>
* Mybatis-Plus: <https://gitee.com/thinkgem/jeesite-mybatisplus>
* Magic接口快速开发：<https://gitee.com/thinkgem/jeesite-magic-api>
* 内外网中间件：<https://my.oschina.net/thinkgem/blog/4624519>

## 快速体验

### 在线演示

1. 全栈版地址：<http://demo.jeesite.com>
2. Vue3分离版地址：<http://vue.jeesite.com>

### 本地运行

1. 环境准备：`JDK 1.8 or 11、17`、`Maven 3.6+`、使用 `MySQL 5.7 or 8.0` 数据库、[其它数据库](https://jeesite.com/docs/technology/#_8、已支持数据库)
2. 下载源码：<https://gitee.com/thinkgem/jeesite5/repository/archive/v5.9.zip> 并解压
3. 打开文件：`/web/src/main/resources/config/application.yml` 配置JDBC连接
4. 执行脚本：`/web/bin/init-data.bat` 初始化数据库
5. 执行脚本：`/web/bin/run-tomcat.bat` 启动服务即可
6. 浏览器访问：<http://127.0.0.1:8980/js>  账号 system 密码 admin
7. 部署常见问题：<https://jeesite.com/docs/faq/>
8. 分离端安装：<https://jeesite.com/docs/vue-install-deploy/>

### 快速运行

1. 环境准备：`JDK 1.8 or 11、17`、`Maven 3.6+`、无需准备数据库（使用内嵌 H2 DB、Vue资源包）
2. 下载源码：<https://gitee.com/thinkgem/jeesite5/repository/archive/v5.9.zip> 并解压
3. 执行脚本：`/web-fast/bin/run-tomcat.bat` 启动服务即可（自动初始化库）
4. Vue分离版本地址：<http://127.0.0.1:8980/vue/login>
5. 全栈版本地址：<http://127.0.0.1:8980/a/login>
6. 初始登录账号：超级管理员：system  密码：admin
7. 部署常见问题：<https://jeesite.com/docs/faq/>

### 容器运行

- 拉取 Docker 镜像（演示使用，JeeSite版本较久）：
```sh
docker pull thinkgem/jeesite-web
```
- 启动脚本：
```sh
docker run --name jeesite-web -p 8980:8980 -d --restart unless-stopped \
    -v ~/:/data thinkgem/jeesite-web && docker logs -f jeesite-web
```
- 浏览器访问：<http://127.0.0.1:8980/js/>  账号 system 密码 admin
- 分离端安装：<https://jeesite.com/docs/vue-install-deploy/>

### 开发环境

1. 部署运行文档：<https://jeesite.com/docs/install-deploy/>
2. 部署常见问题：<https://jeesite.com/docs/faq/>
3. 分离端安装：<https://jeesite.com/docs/vue-install-deploy/>

## 技术文章

* 菜单和按钮权限：<https://jeesite.com/docs/permi-shiro/>
* 强大的数据权限：<https://jeesite.com/docs/service-datascope/#数据权限>
* 表结构数据字典：<https://jeesite.com/docs/code-gen/#表结构数据字典>
* 持久层设计：<https://jeesite.com/docs/dao-mybatis/>
* 后端工具：<https://jeesite.com/docs/sys-utils/>
* 表单组件：<https://jeesite.com/docs/views-beetl/>
* 表格组件：<https://jeesite.com/docs/datagrid/>
* js工具：<https://jeesite.com/docs/jeesite-js/>

## 专题文章

* 自定义主题：<https://jeesite.com/docs/custom-views/>
* 国际化多语言：<https://jeesite.com/docs/i18n-locale/>
* 接口文档：<https://jeesite.com/docs/mobile-rest-api/>
* BPM工作流引擎：<https://jeesite.com/docs/bpm/>
* 用户类型：<https://jeesite.com/docs/user-type/>
* 消息推送：<https://jeesite.com/docs/msg-push-use/>
* 单点登录：<https://jeesite.com/docs/sso-cas/>
* 在线任务调度：<https://jeesite.com/docs/job/>
* 对象存储：<https://jeesite.com/docs/oss-client/>
* 大屏设计器：<https://jeesite.com/docs/visual/>
* 报表设计器：<https://jeesite.com/docs/ureport/>
* 文件在线预览：<https://jeesite.com/docs/filepreview/>
* 三员管理员：<https://jeesite.com/docs/manager3/>
* 手机端框架：<https://jeesite.com/docs/uniapp/>
* 统一认证服务：<https://jeesite.com/docs/oauth2-server/>
* 树表结构设计：<https://jeesite.com/docs/tree-table-use/>

## 云服务架构

* 多租户、SaaS服务：<https://jeesite.com/docs/saas-corp-use/>
* 集群、负载均衡、高可用：<https://jeesite.com/docs/cluster/>
* Spring Cloud 微服务：<https://jeesite.com/docs/springcloud/>
* 分布式事务 Seata：<https://jeesite.com/docs/springcloud-seata/>
* 读写分离、分库分表：<https://jeesite.com/docs/sharding/>

## 前后分离版

* Vue 版介绍：<https://jeesite.com/docs/jeesite-vue/>
* Vue 安装部署：<https://jeesite.com/docs/vue-install-deploy/>
* Vue 参数配置：<https://jeesite.com/docs/vue-settings/>
* Vue 前端权限：<https://jeesite.com/docs/vue-auth/>
* Vue 源码解析：<https://jeesite.com/docs/vue-crud-view/>
* Vue 表单组件：<https://jeesite.com/docs/vue-basic-form/>
* Vue 表格组件：<https://jeesite.com/docs/vue-basic-table/>
* Vue 常用组件：<https://jeesite.com/docs/vue-comp/>
* Vue 图标组件：<https://jeesite.com/docs/vue-icon/>
* Vue 国际化多语言：<https://jeesite.com/docs/vue-i18n/>
* Vue 样式库：<https://jeesite.com/docs/vue-style/>

# Git 全局设置技巧

```
1、提交检出均不转换换行符

git config --global core.autocrlf false

2、拒绝提交包含混合换行符的文件

git config --global core.safecrlf true
```