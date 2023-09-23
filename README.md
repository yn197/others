# others
# 一：目前这个仓库主要做了以下内容

1.零碎的小文档

2.Github自带的CICD流水化操作

3.Jenkins一键式构建，通过Webhok触发此功能

4.内网使用穿透Coplar地址

# 二：主要设置如下

## jenkins回调地址:

![](https://hexo-img-oss.oss-cn-shanghai.aliyuncs.com/jenkins%E9%85%8D%E7%BD%AE1.png)

这个地址需要替换成穿透工具的地址，因为我是本机测试，如果有公网ip则可以不用管，直接公网ip访问

![](https://hexo-img-oss.oss-cn-shanghai.aliyuncs.com/jenkins%E9%85%8D%E7%BD%AE0.png)

![jenkins配置2](https://hexo-img-oss.oss-cn-shanghai.aliyuncs.com/jenkins%E9%85%8D%E7%BD%AE2.png)

![jenkins配置3](https://hexo-img-oss.oss-cn-shanghai.aliyuncs.com/jenkins%E9%85%8D%E7%BD%AE3.png)

![jenkins配置4](https://hexo-img-oss.oss-cn-shanghai.aliyuncs.com/jenkins%E9%85%8D%E7%BD%AE4.png)



## Github:

![](https://hexo-img-oss.oss-cn-shanghai.aliyuncs.com/jenkins_webhok.png)



token：相当于授权访问

![](https://hexo-img-oss.oss-cn-shanghai.aliyuncs.com/github_token.png)

# 三：效果

# 

![](https://hexo-img-oss.oss-cn-shanghai.aliyuncs.com/effect.png)