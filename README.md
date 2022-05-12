# bbq (barbecue 户外烧烤)

因为疫情的原因已经很久没有出去玩过了，难得有这个机会宅在家里，还能不被打扰。正好在家里卷起来，学习学习 RocketMQ 的原理。在看源码的过程中我发现，不实际操练下还是理解的不够深刻，于是有了造轮子的想法。

可能是因为太久没有吃烧烤了，所以给这个项目起名叫 bbq （bbq是网络流行语，Barbecue的英文缩写）。无论是学习还是造轮子都需要想吃烧烤一样，要一串一串撸，一口是吃不下所有的。

bbq 是一个采用计算存储分离式架构的 Message Queue。服务端没有像 RocketMQ 那样使用 netty 来编程，我打算使用常用的 Springboot 来做服务端框架，使用 grpc 来做客户端与服务端之间的通信。并且对外提供 Open API 来做一些运维操作。

![](https://tva1.sinaimg.cn/large/e6c9d24ely1h25p2fbvjsj20wv0u0ta8.jpg)




