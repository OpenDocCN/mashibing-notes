<!--
    需要填充的占位符：
    
    README.md
    
        马士兵课程笔记：文档中文名
        {nameEn}：文档英文名
        {urlEn}：文档原始链接
        msb：域名前缀
        飞龙：负责人名称
        wizardforcel：负责人 Github 用户名
        562826179：负责人 QQ
        mashibing-notes：ApacheCN 的 Github 仓库名称
        mashibing-notes：DockerHub 仓库名称
        mashibing-notes：PYPI 包名称
        mashibing-notes：NPM 包名称
    
    CNAME
    
        msb：域名前缀

    index.html
    
        马士兵课程笔记：文档中文名
        #333：显示颜色
        mashibing-notes：ApacheCN 的 Github 仓库名称

    asset/docsify-flygon-footer.js
    
        mashibing-notes：ApacheCN 的 Github 仓库名称
-->

# 马士兵课程笔记

> 原文：[{nameEn}]({urlEn})
> 
> 协议：[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)
> 
> 阶段：机翻（1）
> 
> 真相一旦入眼，你就再也无法视而不见。——《黑客帝国》

* [在线阅读](https://msb.flygon.net)

## 下载

### Docker

```
docker pull apachecn0/mashibing-notes
docker run -tid -p <port>:80 apachecn0/mashibing-notes
# 访问 http://localhost:{port} 查看文档
```

### NPM

```
npm install -g mashibing-notes
mashibing-notes <port>
# 访问 http://localhost:{port} 查看文档
```

## 赞助我

![](https://img-blog.csdnimg.cn/20200112005920729.png)
