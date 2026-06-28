# 外卖小程序SSM

## 前言

随着移动互联网的普及，外卖行业得到了飞速的发展。在这个背景下，我们开发了一款基于SSM框架的外卖小程序，为广大用户提供便捷的外卖服务。本项目适用于初学者和开发者，可以帮助他们更好地了解SSM框架和微信小程序的开发。

## 内容介绍

本项目主要包括以下功能：用户注册登录、浏览商家、查看商品、下单、支付、查看订单等。通过使用Spring、Springmvc和MyBatis框架，实现了前后端分离，便于维护和扩展。前端采用Uniapp框架，实现了一套代码多端运行，提高了开发效率。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Springmvc、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于查询商家列表的核心代码：

```java
// 商家Service接口
public interface BusinessService {
    List<Business> findAll();
}

// 商家Service实现类
@Service
public class BusinessServiceImpl implements BusinessService {
    @Autowired
    private BusinessMapper businessMapper;

    @Override
    public List<Business> findAll() {
        return businessMapper.selectByExample(new BusinessExample());
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/339252/35/10516/102022/68c59bcdF1eb893f4/fb8b4a07d7bf1f4f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/338812/12/8916/72103/68c59ba5F45aed6b3/2898175432f2be8a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/324640/33/19527/57569/68c59ba5Fa7a23f84/ad156b620e73f710.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328034/24/19415/23603/68c59ba5Fe01e7c8f/d4f2b865d4558261.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/350199/27/3014/18728/68c59ba5F0f727bfe/d2f5893dad528043.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/330400/26/13056/36548/68c59ba5Fe1e9ba3c/8a42d8a14b351397.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/338963/15/10542/49377/68c59ba5F81cdb816/15db75779e3184e5.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/337865/12/10407/25716/68c59ba6Fd5d9dcbc/3960d838c1edc45f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340465/27/9990/34033/68c59ba6F512b2c1d/2fcbce5cc02a300e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/333967/7/12676/72507/68c59ba6F2327a17a/df4548577e9713cc.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
