# PHP知识体系

------

## 参阅
* [php修行之路](https://github.com/GiggleAll/php)
* [PHP 及其相关工程的历史](http://php.net/manual/zh/history.php)

## 网站

### 资料
* [PHP官网](http://www.php.net/)
* [PHP中文手册](http://php.net/manual/zh/)
* [PHP源码](https://github.com/php/php-src/)
* [PHP之道](http://www.phptherightway.com/) php程序员知识体系,对应[中文版](http://laravel-china.github.io/php-the-right-way/)。
* [深入理解php内核](http://www.php-internals.com/)PHP源码阅读、分析，Zend引擎，PHP扩展，脚本语言实现
* [composer](https://getcomposer.org/)Composer 是 PHP 的一个依赖管理工具。它允许你申明项目所依赖的代码库，它会在你的项目中为你安装他们。[中文镜像](http://www.phpcomposer.com/)
* [PSR规范](https://psr.phphub.org/?from=hw798&lid=218)PSR 是 PHP Standard Recommendations 的简写，由 PHP FIG 组织制定的 PHP 规范，是 PHP 开发的实践标准。

### 工具

####  IDE

* [phpstorm](https://www.jetbrains.com/phpstorm/)【强烈推荐】  目前已知最好用的IDE,收费试用期30天,不过你懂得……
* [sublime](https://www.sublimetext.com/)支持众多编程语言，简单易用

#### 开发
* [swagger-ui](https://swagger.io/swagger-ui/) 按照其规范书写注释,即可在网页上管理调试API,需要配合[swagger-php](https://github.com/zircote/swagger-php)一起使用。[参考教程](http://www.cnblogs.com/derrck/p/5234961.html)

#### 搭建本地开发环境

* Windows系统 
    * 建议使用[WampServer](http://www.wampserver.com/en/) 安装, Wamp就是Windows Apache Mysql PHP集成安装环境，即在window下的apache、php和mysql的服务器软件。PHP扩展、Apache模块，开启/关闭鼠标点点就搞定，再也不用亲自去修改配置文件了，WAMP它会去做。再也不用到处询问php的安装问题了，WAMP一切都搞定了，这个软件在win平台上使用的较多。
* MAC系统
    * 推荐用[homebrew包管理工具](https://brew.sh/)自行单个安装每个软件,升级比较方便。[安装教程](https://github.com/Xilesun/blog/issues/1)
* 跨平台(Windows、Mac 或 Linux 系统上运行)```【推荐】```
    * [Homestead](https://d.laravel-china.org/docs/5.5/homestead) 是使用虚拟机的形式安装集成环境它包括了 Nginx Web 服务器、PHP  、MySQL、PostgresSQL、Redis、Memcached、Node 等所需的全部东西。


#### 手册

* 基础
    * [ 菜鸟手册 ](http://www.runoob.com/)
    * [ PHP ](http://php.net/manual/zh/?from=hw798&lid=105)
    * [ html ](http://www.runoob.com/html/html-tutorial.html)
    * [ JavaScript ](http://www.runoob.com/js/js-tutorial.html)
    * [ jQuery ](http://hemin.cn/jq/)
    * [ Nginx ](http://www.nginx.cn/doc/)
    * [ Linux ](http://www.runoob.com/linux/linux-command-manual.html)
* 框架 [框架排名](https://github.com/search?l=PHP&o=desc&q=php+framework&s=stars&type=Repositories&utf8=%E2%9C%93&from=hw798&lid=217)
    * [ laravel ](https://d.laravel-china.org/?from=hw798&lid=212)
    * [ CI ](http://codeigniter.org.cn/docs)    
    * [phalcon](https://docs.phalconphp.com/en/3.2)
    * [ yaf ](http://yaf.laruence.com/manual/)
    * [ Yii ](http://www.yiichina.com/doc)
    
    
### 资讯 、 论坛 

* [Laravel学院](http://laravelacademy.org/)Laravel框架学习资料,最主要还有些讲解php生态的优质文章。
* [Laravel China 是高品质的 Laravel 开发者社区](https://laravel-china.org/)


### 博客

* [惠新宸](http://www.laruence.com/)PHP开发组核心成员, Zend顾问, PHP7主要开发者, Yaf, Yar, Yac等开源项目作者.
* [韩天峰](http://rango.swoole.com/aboutme)PHP扩展开发组成员,Swoole扩展作者

### 推荐书籍

#### PHP 
* [php手册](http://php.net/manual/zh/)
* [PHP 5权威编程](https://book.douban.com/subject/2981954/)

#### 计算机基础知识

* [深入理解计算机系统](https://book.douban.com/subject/1230413/)
* [现代操作系统](https://book.douban.com/subject/3852290/)
* [C程序设计语言](https://book.douban.com/subject/1139336/)
* [数据结构与算法分析](https://book.douban.com/subject/1139426/)
* [UNIX环境高级编程](https://book.douban.com/subject/1788421/)
* [TCP/IP详解 3卷](https://book.douban.com/subject/1088054/)
* [HTTP权威指南](https://book.douban.com/subject/10746113/)

#### 面向对象
> PHP这方面的书不太多，建议看Java方面的。

* [Java面向对象编程](https://book.douban.com/subject/1837608/)
* [Java编程思想](https://book.douban.com/subject/2130190/)


### 文章精选

* [关于PHP程序员技术职业生涯规划](http://rango.swoole.com/archives/570)

### 视频教程

> 喜欢看视频学习的同学,建议多看几遍不要期望一次全部掌握,多个讲师的视频对比着看吸收各家长处
> 
> * 第一遍:  树立PHP知识体系; 快速走马观花知道大致的只是体系,不懂的跳过一个小时的视频5分钟快进看完即可;
> * 第二遍:  制定具体的学习时间表细看; 每天学那些知识点要明确到每天的每小时,任务完不成的,加班或者大致了解跳过;
> * 第三遍:  整体查漏补缺挑选着看; 前两遍那些地方不牢固的,挑选反复的看;


* [韩顺平](http://www.itbull.cn/videoDownload/159.html)
* [高洛峰](http://www.itxdl.cn/php/html/PHPvideo/php_chujishipin/) 
* [慕课网](https://www.imooc.com/course/list?c=php)
