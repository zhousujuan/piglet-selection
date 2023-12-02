## 简介

类似于美团优选，多多买菜等线上平台。

是一套社区团购的项目，是依托真实社区的一种区域化、小众化、本地化、网络化的团购形式，同事也是一种生鲜商品流通的新零售模式。

背景：

社区团购是真实具名团体的一种互联网线上线下购物的消费行为，是依托真实社区的一种区域化、小众化、本地化、网络化的团购形式。简而言之。它是依托社区和团长社交关系实现生鲜上平流通的新型零售模式。

技术栈
项目采用前后端分离的开发方式，涵盖SpringBoot、SpringCloud、Redis、RabbitMQ、ElasticSearch、微信小程序等

业务流程梳理
从集体模式看，主要围绕平台、团长、用户三个角色展开

1、团长（如社区宝妈、便利店老板等）创建一个群，提前发布优惠商品的链接提供用购买，团长从中抽取佣金；

2、用户提前一天下单

3、平台在收集好订单之后，调动供应链，从仓库发货到自提点（团长家或者便利店）

4、用户前往自提点提货

![](./image/业务流程图.png)

## 功能架构

分为三层：

1、前台会员应用层

2、前台团长应用层

3、基础模块支撑层

## 系统架构

![](./image/系统架构.png)

## 技术架构

![image-20231202174131415](./image/技术架构图.png)

## 开发日志

> 2023/12/02
>
> 技术架构分析

> 2023/12/01
>
> 调研项目背景和功能实现，完成项目简介包括背景介绍，技术栈选择，业务流程梳理、**功能和系统架构分析**

