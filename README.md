## 前言

在如今快速发展的互联网时代，校园二手交易市场也在不断地向线上平台迁移。为了方便学生群体进行二手物品的买卖，我们基于Spring Boot技术，设计并实现了一款校园二手交易微信小程序。以下是该项目的基本介绍。

## 内容介绍

本微信小程序主要包括以下几个功能模块：用户模块、商品模块、订单模块、消息模块以及个人中心。用户可以在小程序中浏览商品、发布商品、下单购买、查看订单状态等。此外，我们还实现了消息提醒功能，以便用户及时了解订单状态及商品动态。

## 技术介绍

本项目采用以下技术栈：

- **语言：** Java
- **使用框架：** Spring、Spring MVC、MyBatis、微信小程序
- **前端技术：** JS、Vue、CSS3、Uniapp
- **开发工具：** IDEA/Eclipse、Uniapp
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下是项目中的一段核心代码，展示了如何实现商品列表的查询：

```java
// 商品服务类
@Service
public class GoodsService {

    @Autowired
    private GoodsMapper goodsMapper;

    public List<Goods> listGoods() {
        return goodsMapper.listGoods();
    }
}

// 商品Mapper接口
public interface GoodsMapper {
    List<Goods> listGoods();
}

// 商品Mapper.xml
<mapper namespace="com.example.mapper.GoodsMapper">
    <select id="listGoods" resultType="com.example.entity.Goods">
        SELECT * FROM goods
    </select>
</mapper>
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
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/341728/30/3169/243563/68c63899F090220aa/3bd9e4ce7029d730.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/350913/38/3267/39640/68c63870Fc9ea1b67/83057cd28263e3f0.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/338583/21/9931/57741/68c63870F714d1b6d/e7c8dc8fc5864b73.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/344484/40/3329/62653/68c63871F257edec4/3efc1d1c628e06ff.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/349174/7/3205/211556/68c63871F2ed5cdd4/f578dabcd7ed93ba.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/324941/30/19847/23510/68c63871F0e9138d3/1d8b8782ee7b8e78.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/348149/4/3167/18656/68c63872F630482c8/b520432d644ab63c.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/338100/9/10617/46295/68c63872F20e2f520/21223235690edef9.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329914/17/12987/22265/68c63872F8825cc42/867b1f5ce4f3cf86.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/331726/40/13186/81979/68c63872F513add87/f4854288e174e4be.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
