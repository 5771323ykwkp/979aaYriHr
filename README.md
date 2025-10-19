## 前言

大家好，本次分享的毕业设计项目是基于Java语言和MySQL数据库开发的时尚美妆电商网站。该项目包含了从前端到后端完整的开发流程，是一套实战项目。以下将详细介绍本项目的相关内容。

## 内容介绍

本项目是一款集时尚美妆商品展示、购买、支付等功能的电商平台。用户可以在网站上浏览各类美妆商品，查看商品详情，进行下单购买。后端管理界面则提供了商品管理、订单管理等功能，方便管理员进行网站维护。整个项目从前端到后端，采用了主流的开发技术和框架，具有较高的实用性和扩展性。

## 技术介绍

- **语言：Java**
- **使用框架：Spring Boot**
- **前端技术：JS、Vue、css3**
- **开发工具：IDEA/Eclipse**
- **数据库：MySQL 5.7/8.0**
- **数据库管理工具：phpstudy/Navicat**
- **JDK版本：jdk1.8**
- **Maven: apache-maven 3.8.1-bin**
- **前端环境：Node.Js 12\14\16**

## 核心代码

以下是项目中的一段核心代码，用于查询美妆商品信息：

```java
@RestController
@RequestMapping("/product")
public class ProductController {

    @Autowired
    private ProductMapper productMapper;

    @GetMapping("/list")
    public List<Product> list() {
        return productMapper.selectList(null);
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

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/346339/22/500/82092/68bc7eccF73464e93/e978bcdcb009d4ed.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/349232/8/508/14658/68bc7ea4F4dfcde72/eba77bce7e9d5678.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/336913/12/7817/13955/68bc7ea4F431cef72/5938d8e60b1fdd77.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/288513/18/13134/15982/68bc7ea5F5db2945e/dbdd6c7d1739a83b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325284/20/17133/14179/68bc7ea5F94b65bf8/0218747157773b06.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/351228/38/473/31983/68bc7ea6F9111ad5a/401d851ff1c3787c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340061/33/7863/10913/68bc7ea6Fbeeef1a2/91f0919b1fdd0d16.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/347356/38/477/64677/68bc7ea7Fd6f5213e/ce5d11cfae129325.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/342067/40/505/64042/68bc7ea8Fef18a784/a425b5fb2836c4dc.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/340162/14/7769/35592/68bc7ea8F017cc215/4f616f0030e0e053.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
