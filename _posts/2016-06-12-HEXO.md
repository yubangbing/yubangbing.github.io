---
layout: post
title: 让百度能搜索到gitpage的博客
tag: 博客
---

## 让百度能搜索到你的博客

### 为什么要使用百度搜索？

　　有人可能会说作为一个开发人员, 你不会用 `Google` 啊。 是的, Google是能搜到我们搭建在 `Github Page` 的博客, 会用`Google` 也是一个开发人员必备技能之一。但是, 我们生活在天朝, 所以百度还是总有会用到的时候, 或者是你想让更多的天朝人能搜到你。

### 为什么使用百度搜索不到 Github Page 上的博客？   

有人联系过 Github Support 部门 , 给出大致的意思就是: 百度爬虫爬得太猛烈，已经对很多 Github 用户造成了问题。所以 Github 将禁止百度爬虫的爬取。    

### 如何让百度能搜索你的博客?   

　　根据上面说的, 目前发现只是Github Page禁止了百度搜索, 所以让百度能搜索到你的博客还是有一些方法的。例如:
* 自己搞个VPS,博客部署在VPS上。
* 博客部署 `Coding.net` 上, `GitCafe`已经合并到 `Coding` 。
我使用的是第二种方法, 博客部署在 `Coding.net` 上也相对简单些。

#### 在Coding上部署你的博客。   

　　Coding同样支持Hexo、Jekyll等博客的部署, Coding 跟Github还是挺像的,而且是中文。 同样的在Coding里面建一个项目,项目名字跟你的用户名一样,这里我就不啰嗦了, 说几个需要注意的地方:     
**注意一:**       
　　在`Coding Page` 上部署博客,需要把博客推送到`coding-pages ` 分支上, 分支名字是固定的。    
**注意二:**     
　　`Coding Page` 不支持自定义CNAME, 你需要点击到Page模块,然后添加一个域名来绑定。   

更详细的请看[Coding Pages 官网介绍](https://coding.net/help/doc/pages/index.html).     

参考文章:
[解决 Github Pages 禁止百度爬虫的方法与可行性分析](http://jerryzou.com/posts/feasibility-of-allowing-baiduSpider-for-Github-Pages/)

<br>

转载请注明：[於帮兵的博客](http://yubangbing.github.io)