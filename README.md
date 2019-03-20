# how-to-learn-go
想写这篇文章很久了，因为各种原因还有自身的拖延症，一直迟迟未下笔，现在终于鼓起勇气来写这么一篇关于 Golang 入门的教程，这是我一路走来的经历，大家可以借鉴参考来学习 Golang 这门语言。



我将从书籍、博客网站、社区、框架、项目、视频等这几个方向去一一阐述，这些里面，大部分我都有看过，还有一些是别人介绍的好的教程，希望想学习的可以一字不漏的看完，然后按需挑选。



## 书籍

**入门版**



**《The Way To Go》**

这是很多人都推荐的一本书，推荐如果可以就直接看原版，页数不算多，而且书中英文的难度还算可以，配合谷歌翻译，应该能看得下去，是新接触 Go 这门语言的必看书籍之一。



**《Go语言实战》**

这本书的另一个名字叫《Go in action》，也是笔者看过的书籍之一，书中除了讲 Go 的一些基础语法外，还会比较深入地讲一些 Go 里的坑和原理性的知识，有时间的都可以看看。



**《Go Web 编程》谢大版本**

我们学习一门语言，不能光看不练吧，我们可以对着上面两本的书中代码敲一下，但如果说要想慢慢培养对这门语言的熟练程序，还得做下项目对吧。



我接触的 Go 的第一个 Web 框架，就是谢大写的 beego 框架，这是一个大而全的框架，对新手十分友好，而且文档也相当齐全的，这本书也是基于 beego 框架而写成的，想要一个项目进行练手的，可以看一下。

附上 beego 官网： https://beego.me/

以及我自己学习 beego 时写的小项目： 

https://github.com/Janetyu/mygogogo/tree/master/Beego



**进阶版**



**《Go语言圣经》**

相信接触过 Go 的人都对这本书有所耳闻或已阅读，我在这郑重推荐一下，这是一本很经典的 Go 语言学习的书籍，但我不推荐新手直接看，而是在已经接触并了解过之后，再进行阅读，这样能有助于你更全面地去学习 Go 这门语言的艺术。



**《Go高级编程》**

如果说《Go语言圣经》是经典之作，那这本书就可以当作对 Go 的深入理解的补充，这本书可以让你去了解更多 Go 里面的语言特性，特别是 Go 汇编语言、RPC 、分布式等话题都有涉及，让我不得不拱手推荐，但更建议是先看完了《Go语言圣经》之后再细细品味。



**《Go并发之道/Concurrency in Go》**

这本书的主题就比较明确，整个篇幅都以并发为主题，以及详细描述用 Go 是怎么去做一些并发的骚操作的，而且前不久也开始有中文版翻译的书出售了，是笔者认识的一位很厉害的小姐姐翻译的，觉得不错的可以去买一本回去好好看下。



说完了推荐的书籍，就说一下笔者收藏和时常浏览的一些网站和博客，偶尔能在上面收获到不少的新知识，毕竟一个人学习，没有多个人学习吸收来得快嘛，借鉴大神的学习笔记和心得，也是成长的一种捷径。



## 网站

**官网**

https://golang.org/



**Go 官方博客**

https://blog.golang.org/



**Go 指南**

https://tour.go-zh.org/welcome/1



**Golang 知识社区**

https://learnku.com/golang



**GoCN**

https://gocn.vip/



**Go标准库**

https://studygolang.com/static/pkgdoc/main.html



**菜鸟教程**

http://www.runoob.com/go/go-tutorial.html



## 博客

**Big Sky**

http://mattn.kaoriya.net/



**飞雪无情**

https://www.flysnow.org/



**博客 - PingCAP**

https://pingcap.com/blog/



**七牛云 - 七牛团队博客**

https://blog.qiniu.com/archives/category/5



## 框架

我用过的框架不多，姑且说几个了解和用过的框架，评价都是挺好的，用的时候也是很舒心。



**Beego**

https://beego.me/



**Gin**

https://github.com/gin-gonic/gin



**iris**

https://github.com/kataras/iris



**grpc-go**

https://github.com/grpc/grpc-go



**fasthttp**

https://github.com/valyala/fasthttp



**httprouter**

https://github.com/julienschmidt/httprouter



Go 还是有很多不错的框架的，很多组件、中间件都有相应的轮子，大家到工作的时候有需要的话，可以去 google 一下和 github 上找找，而这也是 Go 里的一个优势。



## 项目实践

这块应该是很多人想关注的吧，我就放几个项目，供大家参考学习吧。



**在线聊天室**

https://github.com/beego/samples/tree/master/WebIM



**Go 实现网络爬虫-爬豆瓣 T250 和珍爱网**

https://github.com/Janetyu/go-crawler



**拼多少团购网项目**

https://github.com/Janetyu/PDSgroupon



**Go 博客系统**

https://github.com/zachrey/my-blog-by-go



**Go 实现世界杯管理系统**

https://github.com/GopherCoder/FIFA-World-Cup



## 视频课程

我只推荐我看过的，没看过的，我不好说，自己去判断吧。



**无闻大佬的 Go 基础讲解**

https://edu.51cto.com/course/2038.html



**Go 语言实战流媒体视频网站**

https://coding.imooc.com/class/227.html



**Google 资深工程师深度讲解 Go 语言**

https://coding.imooc.com/class/180.html



**搭建并行处理管道，感受 GO 语言魅力**

https://www.imooc.com/learn/927



PS：因为网盘链接不稳定，经常失效，因此想要一些上面书籍的 pdf 的，可以加我微信 jwl120717 , 我私发给你们吧。



我能帮你们的，也只有这么多了，这些只能说给你辅助的作用，真正进步还是要靠花时间去学习和理解，期待你加入 Go 语言大军！



![img](https://mmbiz.qpic.cn/mmbiz_jpg/QhiaEpmLXYbnwcI7oNM1fdVibKoLM3yQM8WqndjtbDmcLsIib9JvBzINzkyZyTSEqibXTPMQxYEic9HyibfnibQnLsftw/640?wx_fmt=jpeg)