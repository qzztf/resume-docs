---
# 语言 （可选）
lang: zh-cn
# 网页关键词和描述
keywords: 简历,Hexo,龚海生的简历
description: 龚海生的在线简历。
# 简历标题
resume_title: Maple's Resume
# 应聘者姓名
name: 龚海生
# 联系方式
contact:
  - icon: fas fa-home
    text: Maples Blog
    url: http://www.ice-maple.com
  - icon: fas fa-h-square
    text: 知乎
    url: https://www.zhihu.com/people/gonghs-maple/posts
  # 邮箱
  - icon: fas fa-envelope
    text: maple.haisheng@qq.com
    url: http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=LkNPXkJLAEZbXFxHXW5IQVZDT0dCAE1BQw
  # 电话号码
  - icon: fas fa-phone-alt
    text: 18065972341
    url: tel:18065972341
# PDF下载链接
download:
  title: PDF下载
  icon: fas fa-download fa-fw
  url: http://www.ice-maple.com/uploads/Maple's Resume.pdf
---

{% raw %}
<grid>
<avatar><img src="https://gitee.com/gonghs/image/raw/master/img/20200807164229.png"></avatar>
<h1>龚海生的简历</h1>
<center>
编码是一门严谨而优雅的艺术。代码写的越急，程序跑得越慢。
<!-- <a href='/'>English</a> | <a href='/zh-cn/'>简体中文</a> -->
</center>
<br>
</grid>
{% endraw %}

## <i class="fas fa-user-graduate"></i> 教育背景

**龙岩学院 物理与机电工程学院 电子信息工程 2017年毕业**

## <i class="fas fa-user-tie"></i> 工作经验

#### 2020.10 ~ 2021.11: 深圳市立创电子商务有限公司

- Java后端开发
- Vue前端开发
- 微信小程序前后端开发

#### 2017.6 ~ 2020.8：厦门海西医药交易中心

- 主要负责Java后端开发
- 在旧架构中也包揽前端工作

## <i class="fas fa-award"></i> 项目经验

<!-- 
{% raw %}
<btns rounded>
<a href='https://apps.apple.com/cn/app/heart-mate-pro-hrm-utility/id1463348922?ls=1'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/heartmate/icon.png'>
  心率管家
</a>
<a href='https://apps.apple.com/cn/app/c%E5%85%BB%E8%80%81/id1458315594'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/het-cyanglao/icon.png'>
  C养老
</a>
<a href='https://apps.apple.com/cn/app/c-life%E5%85%BB%E8%80%81/id1393937890'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/het-clife/icon.png'>
  C-Life养老
</a>
<a href='https://apps.apple.com/cn/app/linksmart/id1109303355'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/ht-linksmart/icon.png'>
  LinkSmart
</a>
<a href='https://apps.apple.com/cn/app/hitfit/id1207738581'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/ht-hitfit/icon.png'>
  HitFit
</a>
<a href='https://apps.apple.com/cn/app/%E8%85%95%E8%83%BD%E5%8A%A9%E6%89%8B/id1138242219'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/ht-fiyta/icon.png'>
  飞亚达腕能助手
</a>
</btns><br>
{% endraw %} -->

### 立创芯管家

项目基于SpringBoot，涉及技术：SpringCloud，Feign，roketMq，Redis，Swagger，Mybatis，Mysql，Vue

#### 2020.10 ~ 2021.11：前后端开发

- doc，excel等文件导出方案调整，将原有基于fremarker导出xml文件的方案修改为使用EasyExcel实现，优化用户体验
- [基于druid访问器编写Mybatis插件，实现全局逻辑删除](http://www.ice-maple.com/2021/11/22/Mysql%20Druid%20SQL%20Change/)
- 前后端灰度发布方案研究发布
- 部分系统数据库迁移，SqlServer迁移Mysql（代码调整）
- 父子仓，包装单位调整，商品删除，库位管理等全局业务方案制定和开发，其余小模块业务开发调整。

### 省药械集中采购平台

新系统基于SpringBoot，涉及技术：SpringCloud，Nacos，Feign，Kafka，Redis，Swagger，Shiro，Mybatis-Plus，XXL-Job，Mysql，Jsp，Thymeleaf
旧系统基于SpringMVC，涉及技术：Shiro，Mybatis，Redis，Quartz，Oracle，Jsp，Thymeleaf

#### 2020/07 ~ 2020/08: 数据库由Oracle迁至Mysql

修改系统依赖，修改旧分页功能，使用Idea正则重构功能完成大部分函数，语法全局替换。
引入mybatis-plus并重写代码生成器，增加根据注释生成枚举类的功能，并研究[字段枚举类型的可行性方案](http://www.ice-maple.com/2020/06/23/Springboot%20Enum/)。
参与部分业务及存储过程迁移，包含merge语法替换，游标语法替换，动态sql等。

#### 2020/06 ~ 2020/06: 系统多租户改造

由于各省市平台较多，数据量并不大，使用多租户方式合并数据解决数据库资源浪费的问题。
参考mybatis-plus多租户插件实现多租户改造，无侵入式统一修改sql。

#### 2020/05 ~ 2020/06: 接入单点登录

由于业务变更，需要统一登录入口，用户信息，需要将原系统改为使用token控制登录。
系统维持shiro登录，编写拦截器，校验token，同步用户企业信息并进行登录操作，协同单点登录方迁移数据。
整理系统Readme文档。

#### 2020/03 ~ 2020/05: 系统架构改造

将基于SpringMVC的项目改造为SpringBoot项目，微服务化并接入Nacos配置中心。
依赖变更，升级，将xml配置替换为Java Config配置，接入Kafka，Feign，Swagger，替换分页定时任务实现。
解决[Jsp页面公共头无法引入的问题](http://www.ice-maple.com/2019/12/06/springboot%E9%85%8D%E7%BD%AEjsp-config%E7%9A%84%E6%8E%A2%E7%A9%B6/)。

#### 2019/01 ~ 2019/04: 文件迁移

背景：项目本身时间跨度较大，并非同一批开发人员研发，并且现有功能涉及模块众多，数据量较大，各功能数据库存储差异较大（有些文件还在Clob字段中需要解析）。
编写工具，分模块将文件数据由阿里云迁至公司文件服务器，使用JDK8 CompeteFuture多线程分页执行，提高效率。（>_<之后又迁回去了，还是我）
统一上传接口，修改Js上传组件并提供适应本系统的默认实现，便于各业务模块功能统一修改。

#### 2017/06 ~ 2018/05: 前后端不分离阶段开发

初期权限设计。
利用Aop实现系统业务日志统一存储。
熟悉JDK8 Api并修改BaseController，BaseService等相关基础类暴露函数式接口参数，减少冗余代码。
在开发过程中发现原有的开发流程中表格服务和上传服务代码过于冗余。研究Datatables，WebUploader并封装适应本系统的[前端直传组件](https://zhuanlan.zhihu.com/p/35133548)，和表单组件，提供相对完善的文档。
为了便于维护引入Vue.js使前端代码模板化（而不是使用字符串拼接出来），以后台配置方式维护前端字段渲染方式，校验方式，必填关系，并由于字段存在上传按钮，提供了[基于Vue.js的上传组件](https://zhuanlan.zhihu.com/p/39472915)。

### 国家药械联合采购平台

基于SpringBoot，涉及技术：SpringCloud，Nacos，Feign，Kafka，Redis，Swagger，Shiro，Mybatis-Plus，XXL-Job，Mysql

#### 2019/07 ~ 2019/09: 公共组件开发

提供分布式锁starter包。
提供[用户上下文注入解决方案](http://www.ice-maple.com/2019/08/20/springboot%E7%94%A8%E6%88%B7%E4%B8%8A%E4%B8%8B%E6%96%87%E6%B3%A8%E5%85%A5/)starter包。
解决[SpringBoot集合校验](http://www.ice-maple.com/2019/07/25/springboot%E5%A4%84%E7%90%86%E9%9B%86%E5%90%88%E7%B1%BB%E5%9E%8B%E6%A0%A1%E9%AA%8C/)问题。
提供数仓参数拼接工具。
提供缓存工具类和支持SpringEL表达式的缓存注解。
封装基于Shiro的starter包。
提供Dozer工具类。
提供统一文件上传接口。

### 2.0系统开发

基于SpringBoot，涉及技术：SpringCloud，Dubbo，Mybatis，Mysql，Redis，Quartz

#### 2019/01 ~ 2019/01: 业务数据初始化

由于数据处理量相对较大，响应较慢，采用异步执行，前端轮询的方式等待响应。
使用多线程优化执行效率。

### 出行项目

基于SpringMVC，涉及技术：Dubbo，Memcached，Mybatis，JWT，微信登录，微信支付

#### 单点登录服务开发

编写统一登录服务，存储用户信息，调取微信公众号登录存储OpenId，UnionId，并利用JWT生成统一Token供其他服务鉴权。
编写拦截器在维持子业务不受影响的情况下校验token实现登录。

## <i class="fab fa-github"></i> 开源项目

### Auth-System

#### 2020.3 ~ 至今，一个简单的权限系统，starter练手项目

- 基于SpringBoot，Shiro，Jwt，Mysql，Mybatis-plus，Amaze-ui
- SpringBoot starter练手项目
- 移植了开发至今认为比较好的一些项目实践
- 源码：https://github.com/gonghs/auth-system

## <i class="fas fa-phone-alt"></i> 与我联系

目前状态为：已离职，月内到岗。

<i class="fas fa-envelope fa-fw"></i> [maple.haisheng@qq.com](http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=LkNPXkJLAEZbXFxHXW5IQVZDT0dCAE1BQw)
<i class="fas fa-phone-alt fa-fw"></i> [18065972341](tel:18065972341)
<i class="fas fa-home fa-fw"></i> [博客](http://www.ice-maple.com)
<i class="fas fa-h-square fa-fw"></i> [知乎](https://www.zhihu.com/people/gonghs-maple/posts) 
