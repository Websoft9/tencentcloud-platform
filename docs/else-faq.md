# FAQ

#### 实例的登录账号是什么？

Windows实例的账号名称是`Administrator`，Linux实例的账号名称是`root`  
更多详情本文档的 [账号密码](/zh/stack-accounts.md) 相关章节

#### 数据库账号密码是什么？

数据库账号密码默认存放在服务器中，参考本文档的[账号密码-数据库](/zh/stack-accounts.md)章节

#### 如何启用Linux系统的root账号？

阿里云默认已经开启root账号

#### 如何上传文件到服务器？

对于Windows来说，**远程桌面**登录到服务器后，通过复制/粘贴就可以上传文件

对于Linux来说，通过 **SFTP** 连接服务器即可管理文件

#### 镜像可以退款吗？

请参考[退款相关说明](/zh/business-order.html#退款)章节

#### Websoft9有免费镜像吗？

我们在阿里云的云市场上不提供免费镜像。如果您想免费使用我们的部署包，请通过 [Github](https://github.com/websoft9) 下载我们的自动化脚本，通过Ansible部署。

#### 对于Websoft9的部署包来说，通过Github脚本部署与AWS云市场的镜像部署有区别吗？

部署结果是一样的，只是部署方式不同

#### 如何列出Websoft9在阿里云云市场上的所有产品？

通过 [Websoft9阿里云店铺](https://shop658hlt17.market.aliyun.com/) 查看我们在AWS上的所有镜像，也可以通过搜索关键字“websoft9”列出

#### 实例上的镜像是否可以更换？

支持，参考[更换系统盘](/zh/stack-deployment.html#更换系统盘部署)章节

#### 已经有了服务器怎么使用你们的镜像？

可以通过更换系统盘操作来使用我们的镜像，参考[更换系统盘](/zh/stack-deployment.html#更换系统盘部署)章节

#### 我能创建ECS的操作系统账号吗？

创建ECS的时候只有默认账号名称，但采用默认账号登录到系统后，可以自行创建更多账号

#### 如何通过阿里云控制台获取镜像文档？

登录阿里云控制台，依次打开：云市场->已购买的服务，列出所有服务以及文档链接
![](https://libs.websoft9.com/Websoft9/DocsPicture/zh/aliyun/aliyun-getdocfromorder-websoft9.png)

#### 阿里云磁盘支持扩容吗？

阿里云支持在线扩容系统盘和数据盘，即无需重启ECS实例便可以完成扩容。

#### 一个服务器可以部署多个网站吗？

一个服务器支持部署多个网站，只需要为每个网站配置一个对应的虚拟主机即可

#### 你们的镜像安全吗？

我们的镜像是经过阿里云安全团队审核后才发布上架的，我认为有一定的安全保障

#### 如何试用Websoft9的镜像？

部分镜像的商品详情页面提供了官方的演示地址。如果没有演示地址，请按量购买（按小时付费）试用，只需付出几毛钱/小时的成本。
![](https://libs.websoft9.com/Websoft9/DocsPicture/zh/aliyun/alibabacloud-byhourtry-websoft9.png)