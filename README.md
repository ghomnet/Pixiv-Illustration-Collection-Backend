<p align="center">
<img src="https://pixivic.com/img/icon.9a42bbfa.svg" width = "129" height = "90" alt="pixivic_icon"/>
</p>


 ## 前言

## About Code

### 架构图

![](https://cdn.jsdelivr.net/gh/OysterQAQ/Blog-Image/Nginx.png)

### Bright Point

- 基于注解的基础设施aop模块（jwt权限校验、令牌桶限流、状态机敏感词过滤、验证码校验）
- 基于[Deeplearning4j](https://github.com/eclipse/deeplearning4j)使用机器学习训练的nsfw模型进行图片色情检测
- 基于[Graphicsmagick](http://www.graphicsmagick.org/)的图片裁剪
- 基于[ElasticSearch](https://www.elastic.co/elasticsearch/)的近实时搜索
- 基于[Rabbitmq](https://www.rabbitmq.com/)作为消息总线构成事件驱动的业务模型
- 基于[Logstash](https://www.elastic.co/logstash)的同步
- 基于[Mahout](https://mahout.apache.org/)的简单单机离线推荐
- 基于`JDK 11`的`Httpclient`
- `Restful` API

#### Api Doc

[https://github.com/OysterQAQ/Pixiv-Illustration-Collection-Backend/blob/master/Pixivic.com%20Api%20Doc.html](