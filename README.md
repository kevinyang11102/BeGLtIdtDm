# 前言

欢迎来到民大食堂用餐综合服务平台项目！此项目旨在为用户提供便捷、高效的食堂用餐服务。本项目基于SSM框架，结合微信小程序、Uniapp等前端技术，打造一套功能完善的用餐服务平台。以下是项目的详细介绍。

# 内容介绍

民大食堂用餐综合服务平台主要包括以下功能模块：用户模块、菜品模块、订单模块、评论模块等。用户可以通过微信小程序端查看菜品信息、提交订单、发表评论等。食堂管理员可以管理菜品、订单、评论等数据，实现食堂运营的高效管理。

本项目通过整合多种技术，提高食堂用餐的便捷性，为用户带来更好的用餐体验。同时，项目采用模块化设计，便于后期维护和功能拓展。

# 技术介绍

## 语言：Java

## 使用框架：Spring Springmvc，mybatis

## 前端技术：JS、Vue、css3，Uniapp

## 开发工具：IDEA/Eclipse，Uniapp

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven: apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下为项目中的一部分核心代码，展示了用户查询菜品信息的操作：

```java
// 菜品Service层
public List<Dish> queryDishesByCategoryId(Integer categoryId) {
    DishExample example = new DishExample();
    example.createCriteria().andCategoryIdEqualTo(categoryId);
    return dishMapper.selectByExample(example);
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/332985/31/12822/112532/68c57241F1b626291/97e4446d04143a50.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/343051/1/2854/28076/68c57219Fde13ce9d/f49ff4f4ddcf1300.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/328360/35/19555/25047/68c57219F76daca90/5e85dd6a7aaf19fc.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336856/5/10342/32365/68c57219F697fc1a8/b806183dcfee7f4d.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/342772/22/2983/20301/68c57219Fb5b58a52/7a61143c9832ef20.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/350630/22/3004/9820/68c57219F24876606/bb5783cc29034c31.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/340028/4/10351/67575/68c5721aFb1e992d9/b8800bda2153c7cf.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/342035/23/2941/7830/68c5721aF71ec18b0/a5df67e68b03f137.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/333906/8/12969/56549/68c5721aFd0b6ca03/01a1ca79c7005591.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/342135/13/2961/52828/68c5721aF42f8abaa/29c2c7d4be231fba.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
