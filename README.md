# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm206基于SSM的咖啡销售系统+vue

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1gn8XeNE2J?p=5)


﻿摘  要

现代社会是计算机技术普遍发展与应用的社会，甚至无网不成行，由此可见信息网络已经在商家活动或者人们生活中占据非常重要的地位，成为各行业不可割舍的重要组成。而随着网络地位的越来越突出，网络平台已经超越电视、报纸等传统媒体，成为商家宣传与发展的重要平台。网络费用低廉，只要商家建立网站、或者利用其它大众平台，就能够实现网上购物、信息更新与查询等等功能，所有这些都是在与时俱进的过程中，为商家争取更多的效益，所以对于商家来说，拥有一个属于自己的网站平台是非常重要的。

近年来，由于电子商务和网上商城的快速发展，越来越多的人在网上商城进行商品的交易，取代了传统的当面交易，这无非使交易更安全更快捷。本文以咖啡销售系统为题，进行系统开发，主要解决人们在线购物的流畅，实现计算机化管理。

本文是针对web技术进行相应研究，并在其基础之上制定了一套基于SSM三层体系结构，采用JAVA技术结合Mysql数据库来实现咖啡商品管理系统。

**关键词**：咖啡；网上商城；SSM框架；Java；Mysql

ABSTRACT

Modern society is a society with the universal development and application of computer technology, even without network, it can be seen that information network has occupied a very important position in business activities or people's life, and has become an important part of various industries. With the increasingly prominent status of the network, the network platform has surpassed traditional media such as TV and newspapers and become an important platform for business publicity and development. The network cost is low. As long as businesses establish websites or use other public platforms, they can realize the functions of online shopping, information update and query. All these are in the process of keeping pace with the times and strive for more benefits for businesses. Therefore, it is very important for businesses to have their own website platform.

In recent years, due to the rapid development of e-commerce and online shopping mall, more and more people trade goods in online shopping mall, replacing the traditional face-to-face transaction, which makes the transaction safer and faster. This paper takes the coffee sales system as the title to carry out system development, which mainly solves the fluency of people's online shopping and realizes computerized management.

This paper makes a corresponding research on Web technology, and based on it, formulates a set of three-tier architecture based on SSM, and uses Java technology combined with MySQL database to realize coffee commodity management system.

**Key words:** coffee; E-Shop; SSM framework; Java； Mysql

目  录

[第一章 绪论	5]()

[1.1 问题定义	5]()

[1.2 研究背景	6]()

[1.3研究意义	6]()

[1.4 本系统使用的方法和语言及开发工具	8]()

[1.4.1 VUE	8]()

[1.4.2 Java	8]()

[1.4.3 Mysql	8]()

[第二章 系统分析	10]()

[2.1需求分析	10]()

[2.1.1功能需求	10]()

[2.1.2性能需求	11]()

[2.2可行性分析	11]()

[2.2.1技术可行性	12]()

[2.2.2操作可行性	12]()

[2.3 业务流程分析	12]()

[第三章 概要设计	15]()

[3.1网站开发目标	15]()

[3.2功能设计	15]()

[第四章 数据库设计	16]()

[4.1数据库简介	16]()

[4.2数据库模型设计	16]()

[第五章 功能的实现	27]()

[5.1 网站界面实现	27]()

[5.2 主要功能代码	27]()

[5.2.1登录模块详细设计	27]()

[5.2.2用户注册模块	28]()

[5.2.3在线客服模块的实现	30]()

[5.2.4个人中心管理模块	31]()

[5.2.5咖啡信息管理模块的实现	31]()

[5.2.6咖啡类别管理模块的实现	31]()

[5.2.7系统管理模块的实现	32]()

[5.2.8下单流程模块的实现	32]()

[5.2.9订单管理模块设计	34]()

[5.2.10用户前台界面模块	34]()

[第六章 系统测试	35]()

[6.1 测试目的	35]()

[6.2 测试内容	35]()

[6.3 系统测试	35]()

[6.3.1 测试的数据	35]()

[6.3.2 系统测试方法	35]()

[6.3.3 系统测试项目表	35]()

[6.3.4 系统测试结果	36]()

[第七章 系统总结与展望	37]()

[参考文献	38]()

[致  谢	40]()




[第一章 绪论](#_Toc11589_#_Toc11589_)

1.1 问题定义

`    `目前，在世界社会的互联网发展中，网上购物被广泛采用，网上平台可以发布商品信息、展示商品、在线沟通、实时洽谈、关键还能在线下单，实现最终的交易，不可否认，几乎所有以往传统购物功能都可以在互联网上进行电子化的高效运作。 

`    `技术的进步对传统购物上网解决方案提出更严格的要求和挑战。为了保护传统购物的投资，购物上网解决方案应切合传统购物实际的需求和发展的趋向，使投入回报和管理效益最大化，传统购物在实施上网方案的之前，必须对一系列问题进行科学的论证，如购物上网的需求分析、购物上网总体规划、网上购物系统的功能和实施方案、网上购物的传播与推广、运行网上购物系统的软件和硬件配置、网上购物的管理系统和管理方法等等。网上购物具体实施的实现直接影响传统购物在Internet的实际效果和经济效益，这不仅是技术问题，同时也涉及到管理的因素。 

`   `发现这样一个事实，某位用户首先访问某个网站时，只对该网站的某些内容感兴趣，比如某个产品，而且对这种产品的兴趣会持续一段时间。这点产生深深的启迪，希望根据这一点，为客户设置个性化的喜好，并未其展示符合其兴趣的页面，甚至为其推荐感兴趣的相关内容，这样即为客户提供所需，节省其寻找产品的时间，还能使得页面更加的有吸引力。目前很多大型网站都具备这个功能。比如，在用户注册、登录本网站时候,提供一系列的选项，使得用户能够根据自己喜好进行设置，从而使得站点为该用户展示他感兴趣的内容，但是对于很多用户来说，过程相对麻烦，而且用户本身对该网站体验不深，并不能准确的对该网站进行定位，并且表达喜好。

首先，用户登录后，通过后台对用户的浏览、搜索途径进行跟踪、分析，发现用户的内容喜好，并且根据用户点击标题、产品先后，确立其感兴趣的先后，建立关联规则，如此，用户在点击感兴趣的页面之后，系统会为其生成另一页面，包括用户目前选择的主题相关的内容与链接，这样，用户便能收到更多自己关注的内容，而且了解的主题、产品更加的全面，该网站也实现了为用户量身定制的个性化页面与服务。

`    `任何一种功能的开发与实现，皆需要后台数据库的支撑。在用户验证信息方面，系统将跟踪、分析得出的用户点击信息、主题关联信息等大量数据反馈至数据库管理系统。本系统的数据库服务器端采用了Mysql数据库作为ODBC(Open DataBase Connectivity )数据源，并且通过使用先进的ADO（ActiveX Data Objects）技术进行数据库的存取及其他相关操作，这样形成Web与数据库的紧密联系。 

1.2 研究背景 

`    `“互联网+”时代，电子商务作为经济活动，发展势头强劲，已然是世界主要国家综合实力竞争的重要手段，能够获得全球范围内资源配置的优势。电子商务，人们通过网上各种各样的产品信息展示、越来越完善的物流配送系统和越来越安全快捷的资金结算渠道实现在线交易与买卖，而非面对面，利用店面展示货物，靠拿现金等实现产品的交易。

`    `在当前国际金融危机进一步加深的大背景下，许多企业尤其是外贸出口型中小企业面临着生存的困境，促进中小企业大规模步入电子商务首次成为各级地方政府关注的新热点。电子商务不受时间空间限制，在生产、流通、消费等各个行业领域普遍应用，有效降低商家成本，提升经济效益，为经济的转型发展所处重要贡献，极大地促进了地方、国家经济的发展。电子商务是一种与时俱进的向上发展的力量，实践性强，发展前景是前所未有的。

1.3研究意义

`    `自从中国加入WTO以后，全球经济一体化越来越深入，网上购物已是现代传统购物必不可少的经营策略之一。目前，网上购物在国际互联网上可以实现的商务功能已经多样化，可以说从最基本的对外沟通展示功能、信息发布功能，在线商品展示功能、在线洽谈功能、在线交易功能、在线采购功能、在线客户服务功能、在线网站管理功能等等，几乎以往传统购物功能都可以在互联网上进行电子化的高效运作。 

`    `技术的进步对传统购物上网解决方案提出更严格的要求和挑战。为了保护传统购物的投资，购物上网解决方案应切合传统购物实际的需求和发展的趋向，使投入回报和管理效益最大化，传统购物在实施上网方案的之前，必须对一系列问题进行科学的论证，如购物上网的需求分析、购物上网总体规划、网上购物系统的功能和实施方案、网上购物的传播与推广、运行网上购物系统的软件和硬件配置、网上购物的管理系统和管理方法等等。网上购物具体实施的实现直接影响传统购物在Internet的实际效果和经济效益，这不仅是技术问题，同时也涉及到管理的因素。 

`    `国内外现在关于电子商务方面的研究： 

（1）先进的购物流程：现在购物网站普遍采用收藏夹购物的方式，与传统的购物车相比，该种购物方式能将顾客的购物意向信息填写入数据库，并且长久保存，待购物结束之后，才自动清除相应的数据，而且可以为顾客的意向进行长久保留，以便顾客下次进行精准查找，也方便商家为顾客提供需要的产品。

（2）科学的购物管理模式：本系统采用的是主动推荐的方式，客户结合灵活多样的高级检索，或者之前留下的信息记录，就能方便快速的找到自己所需要的商品，极大的便利了客户寻找目标商品的需求，因为系统通过设置反馈和留言版面就能轻松的掌握客户的需要，进行互动交流；通过信息的发布系统，客户能够及时得到商品的最新动态以及相关新闻，掌握行业动态，系统非常的晚上；在后台的管理中，采用的是结构化管理模式，包括栏目设置，商品编辑，用户、订单管理以及其他基础信息的管理等等，为购物的电子化管理提供了一套良好的管理模式。 

（3）支持量身订制：系统采用模块化结构，支持客户自由定制包括帮助系统、购物基础信息，各类栏目相关设置等等，可自由设置管理人员各级权限，这种灵活的购物设计结构，将大大丰富购物的信息，让客户经常有全新的感觉。 

（4）人性化的操作界面：一个网站，能否吸引顾客的经常光顾，界面的美观与否、大方简洁与否很重要。该购物系统经专业美工的精心设计，进行专门的客户群体定位，使得网站最大限度保持时尚、大众、群众喜爱。 

（5）完善的安全机制：本系统采用的模式是前台与后台管理完全分离，通过密码校验功能，实现各自的独立性，并且采用md5的不可逆加密方式，通过关键程序对各类非法字符进行过滤，确保用户和购物的数据有较好的安全性。 

（6）免费的升级服务和永久性技术支持：想客户想不到的需求，只有不断的自我完善，才能做出一套经典的产品，基于这种信念，开发人员参考了大量的传统购物经营模式，研究了大量的网上购物系统，不断的对系统功能升级，尽量做到流程最新，速度最快，效率最高。而这一切将和客户共享，一旦成为客户，将获得同种平台下的免费升级服务和永久性技术支持。 

（7）专业的服务器空间：拥有高档的服务器设备，不仅能让商务数据轻松的运行，而且能够保证数据高枕无忧。

1.4 本系统使用的方法和语言及开发工具

1.4.1 VUE

Vue (读音 /vjuː/，类似于 view) 是一套用于构建用户界面的渐进式框架。与其它大型框架不同的是，Vue 被设计为可以自底向上逐层应用。Vue 的核心库只关注视图层，不仅易于上手，还便于与第三方库或既有项目整合。另一方面，当与[现代化的工具链]( )以及各种[支持类库](https://github.com/vuejs/awesome-vue#libraries--plugins)结合使用时，Vue 也完全能够为复杂的单页应用提供驱动。

1.4.2 Java

Java是一门[面向对象](https://baike.baidu.com/item/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1)编程语言，不仅吸收了[C++](https://baike.baidu.com/item/C%2B%2B)语言的各种优点，还摒弃了C++里难以理解的多继承、[指针](https://baike.baidu.com/item/%E6%8C%87%E9%92%88/2878304)等概念，因此Java语言具有功能强大和简单易用两个特征。Java语言作为静态面向对象编程语言的代表，极好地实现了面向对象理论，允许程序员以优雅的思维方式进行复杂的编程 。

Java具有简单性、面向对象、[分布式](https://baike.baidu.com/item/%E5%88%86%E5%B8%83%E5%BC%8F/19276232)、[健壮性](https://baike.baidu.com/item/%E5%81%A5%E5%A3%AE%E6%80%A7/4430133)、[安全性]( t )、平台独立与可移植性、[多线程](https://baike.baidu.com/item/%E5%A4%9A%E7%BA%BF%E7%A8%8B/1190404)、动态性等特点。Java可以编写[桌面应用程序]( t )、Web应用程序、[分布式系统](https://baike.baidu.com/item/%E5%88%86%E5%B8%83%E5%BC%8F%E7%B3%BB%E7%BB%9F/4905336)和[嵌入式系统]( t )应用程序等。

1.4.3　Mysql

MySQL是一个[关系型数据库管理系统](https://baike.baidu.com/item/%E5%85%B3%E7%B3%BB%E5%9E%8B%E6%95%B0%E6%8D%AE%E5%BA%93%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F/696511)，由瑞典[MySQL AB](https://baike.baidu.com/item/MySQL%20AB/2620844) 公司开发，属于 [Oracle](https://baike.baidu.com/item/Oracle) 旗下产品。MySQL 是最流行的[关系型数据库管理系统]( t )之一，在 [WEB](https://baike.baidu.com/item/WEB/150564) 应用方面，MySQL是最好的 [RDBMS](https://baike.baidu.com/item/RDBMS/1048260) (Relational Database Management System，关系数据库管理系统) 应用软件之一。MySQL是一种关系型数据库管理系统，关系数据库将数据保存在不同的表中，而不是将所有数据放在一个大仓库内，这样就增加了速度并提高了灵活性。MySQL所使用的 SQL 语言是用于访问[数据库](https://baike.baidu.com/item/%E6%95%B0%E6%8D%AE%E5%BA%93/103728)的最常用标准化语言。MySQL 软件采用了双授权政策，分为社区版和商业版，由于其体积小、速度快、总体拥有成本低，尤其是[开放源码](https://baike.baidu.com/item/%E5%BC%80%E6%94%BE%E6%BA%90%E7%A0%81/7176422)这一特点，一般中小型网站的开发都选择 MySQL 作为网站数据库。

1.4.4　SSM框架

SSM（Spring+SpringMVC+MyBatis）框架集由Spring、MyBatis两个开源框架整合而成（SpringMVC是Spring中的部分内容），常作为数据源较简单的web项目的框架。Spring就像是整个项目中装配bean的大工厂，在配置文件中可以指定使用特定的参数去调用实体类的构造方法来实例化对象。也可以称之为项目中的粘合剂。Spring的核心思想是IoC（控制反转），即不再需要程序员去显式地`new`一个对象，而是让Spring框架帮你来完成这一切。SpringMVC在项目中拦截用户请求，它的核心Servlet即DispatcherServlet承担中介或是前台这样的职责，将用户请求通过HandlerMapping去匹配Controller，Controller就是具体对应请求所执行的操作。SpringMVC相当于SSH框架中struts。mybatis是对jdbc的封装，它让数据库底层操作变的透明。mybatis的操作都是围绕一个sqlSessionFactory实例展开的。mybatis通过配置文件关联到各实体类的Mapper文件，Mapper文件中配置了每个类对数据库所需进行的sql语句映射。在每次与数据库交互时，通过sqlSessionFactory拿到一个sqlSession，再执行sql命令。页面发送请求给控制器，控制器调用业务层处理逻辑，逻辑层向持久层发送请求，持久层与数据库交互，后将结果返回给业务层，业务层将处理逻辑发送给控制器，控制器再调用视图展现数据。




















[第二章 系统分析](#_Toc17444_#_Toc17444_)

[2.1需求分析](#_Toc273815982)

需求的分析即将用户的需求进行分析，从而且设计网站提供指导。需求的分析是数据库设计的开始，也能够较为准确的反映出客户的实际需求，它影响着后面的一系列设计和开发，也影响着系统设计完成后是否能够得到合理的应用。

在这一阶段，设计者的主要任务是通过详实的调查，确定网站设计的定位，如顾客对象，设计目标等等，并且清楚了解原系统工作概况，明确用户的各种需求，然后在此基础上确定新系统的功能。新系统必须充分考虑近乎可能的扩充和改变，不能仅按当前应用需求来设计数据库。

2.1.1功能需求

本系统要具备的主要功能大致如下：顾客可以浏览查看商店里的商品和商品的简单信息，查看方式可以通过分类浏览进行；系统还应具备及时给顾客提供新商品等的功能。 

以上的这些功能可以概括为商品信息浏览，每一位顾客都可参与。本网站系统拥有会员注册、会员登录的功能，客户如需订购商品，那么首先要登录，因为只有会员才能在本网站进行购物。会员客户在选择自己喜欢的商品后，系统会提示将其放入购物篮里， 对于已经放置购物篮中的商品，会员可以将其“拿出”，亦可以下单并结算。 

该咖啡销售系统针对普通购物的业务范围及特点，设计了前台用户系统和后台远程管理系统。前台用户系统是面向广大购物顾客的界面，主要由咖啡信息、咖啡资讯、购物车、在线客服组成；后台远程管理系统是面向管理员的，一个站点的管理员可以有多个，它的界面由商品管理、商品分类管理、用户信息管理、 管理员属性修改、订单信息管理、购物管理和用户信息反馈等功能组成。各大功能的实现按不同的用户权限进行，管理部分只能有管理员才能进行，而用户仅具有查询、预订和选购的权力。 

开发此系统中可能遇到的困难，主要包括以下几个方面： 

（一）前台用户模块： 

商品检索：涉及到对商品的分类查询和模糊查询，目的是让顾客更容易找到他所需要的商品。 

网上销售：涉及到用户注册、购物流程， 其中又包含订单处理与交易过程，交易过程要求对客户资料的保密。 

（二）后台管理模块： 

订单信息管理：这部分要求对订单能够进行浏览、查询和修改。 购物管理：要求能够对用户正在进行的购买活动进行跟踪。 

在线客服管理：包含对客户所提出的问题进行删除、增加、修改、回复的操作。 

这些问题主要都涉及到Mysql数据库的操作，首先要能对数据库进行熟练应用，其次要对这些错综复杂的数据库有条理进行设计，结构分明，功能明确。

2.1.2性能需求

(1)系统处理的准确性和及时性：系统处理的准确性和及时性是系统的必要性能。在系统设计和开发过程中，要充分考虑系统当前和将来可能承受的工作量，使系统的处理能力和响应时间能够满足管理员对用户信息处理的需求。

(2)系统的开放性和系统的可扩充性：系统在开发过程中，需要充分考虑开发之后以及使用过程中的可扩充性。比如数据表中用户在选择字段方式时的改变，并且根据用户查询的需求不断进行更新完善。诸如此类，都需要系统在设计时候能够采用尽可能的方式进行实时的调整以及扩充。据此，系统更应该具备开放性的特征，在设计系统时，要保证系统的开放性，只要符合一定的标准，就可以简便的增加和减少系统的模块，配置系统的硬件。通过软件的修补、替换完成系统的升级和更新换代。

(3)系统的易用性和易维护性：要实现这一点，就要求系统应该尽量使用用户熟悉的术语和中文信息的界面；针对用户可能出现的使用问题，要提供足够的在线帮助，缩短用户对系统熟悉的过程。

(4) 系统的数据要求：1、数据录入和处理的准确性和实时性。2、数据的一致性与完整性。3、数据的共享与独立性。

2.2可行性分析

从系统结构的组织，功能的实现，技术的要求以及可行性等多方面进行考虑，本系统基于WEB进行开发，使用Mysql作为后台数据库。利用图像处理软件设计页面；用网页制作工具Dreamweaver进行制作。

首先应用JAVA作为开发环境，前台使用流行的网页制作工具Dreamweaver,后台的数据库则使用Mysql，最后将整个网站进行整合。

2.2.1技术可行性

从以上分析可知，该网站是一个小型的信息管理网站，是Java编程语言、html标志语言和jsp脚本语言的综合使用。

2.2.2操作可行性

操作简单，界面简洁、美观，各功能模块容易管理、扩展，并且在页面中会有许多操作提示，对于学过大学计算机基础的人和具备一定计算机操作能力的人来说都是易于掌握的，所以在操作上是可行的。

2.3 业务流程分析

本系统的业务流程图如图2-1所示：

![](/md/blog.001.png "QQ截图20150511224907")

图2-1 系统流程图

本系统管理员的业务流程图如图2-2所示：

![](/md/blog.002.png)

图2-2 管理员流程图

本系统的顾客业务流程图如图2-3所示：

![](/md/blog.003.png)

图2-3 顾客流程图

本系统是将现代化的计算机技术与在线购物平台服务模式相结合，按照业务管理的服务流程设计完成的。同时为扩展服务范围，初步设计一个管理平台以利于信息发布和管理。为了使系统在各项管理中发挥更大的作用，实现工作过程的计算机化，提高工作效率和工作质量，现提出如下系统开发目标： 

具体目标如下： 

（1）操作简单、界面友好： 

完全控件式的页面布局，使得信息的录入工作更简便；许多选项包括管理员信息、商品信息、订单信息等只需要点击鼠标就可以完成。 

（2）即时可见： 

对信息的处理（包括添加、修改、删除）将立即在对应的页面显示出来，达到"即时发布、即时见效"的功能。 

（3）功能完善： 

不仅包括常见系统的信息管理的各个方面：信息录入、浏览、删除、修改、查询等各个方面，完整地实现了系统对即时信息的管理要求。同时，为了能有效方面的更新系统的界面。 

（4）方便移植： 

系统应具有实用性、可靠性和适用性，同时注意到先进性。系统界面中所需的数据都存放于数据文件中，只要对该文件做部分修改，就能在系统界面上实现及时更新的效果，减少了更改系统源代码的复杂性。 

（5）动态管理： 

对系统数据库实行动态操作，能实现对数据库信息的动态查询、动态更新修改和动态录入数据。

[第三章 概要设计](#_Toc8006_#_Toc8006_)

[3.1网站开发目标](#_Toc273815983)

咖啡销售系统就是为了适应这种要求而设计的。集信息的显示、输入、修改、删除、查询等各种处理为一体，信息维护起来非常方便。大大减少了用户购买商品造成的麻烦和不安全，为广大人民群众带来很大的便利。

[3.2功能设计](#_Toc273815983)

前台功能有查看咖啡资讯、咖啡商品等信息，进行用户注册，登录后进行在线咨询，商品购买等。用户后台功能有个人资料管理、购物车结算管理、我的订单管理；管理员功能有系统管理员（管理员添加、管理员查询、注册用户管理、修改密码）、咖啡资讯管理（咖啡资讯添加、咖啡资讯查询）、咖啡商品信息管理（商品类别添加、商品类别查询）、所有订单管理、系统管理（在线客服、轮播图）。 

本系统的功能模块图如图3.1。

![](/md/blog.004.png)

图3.1系统功能结构图



[第四章 数据库设计](#_Toc8006_#_Toc8006_)

[4.1数据库简介](#_Toc273815984)

数据库是信息系统的基础和核心,数据库设计的质量将直接关系到信息系统开发的成败和优劣。制作数据库表首先要确定实体的属性和实体间的关系。根据关系做出数据表。

[4.2数据库模型设计](#_Toc273815986)

(1)系统E-R图

概念模型的设计是为了将现实世界信息进行抽象，实现信息世界的建模，是进行数据库设计的有力工具。数据库概念模型设计可通过E-R图来描述现实世界的概念模型。本系统的E-R图表现了系统中各个实体之间的联系。 

(2)实体属性图

管理员的实体图如图4.1。

![](/md/blog.005.png)

图4.1管理员实体图

咖啡资讯信息实体图如图4.2。

![](/md/blog.006.png)

图4.2咖啡资讯信息实体图

用户实体图如图4.3。

![](/md/blog.007.png)

图4.3用户信息实体图

订单信息的实体图如图4.4。

![](/md/blog.008.png)

图4.4订单信息实体图

留言信息实体图如图4.5。

![](/md/blog.009.png)

图4.5留言信息实体图

购买记录实体图如图4.6。

![](/md/blog.010.png)

图4.6购买记录实体图

商品类别实体图如图4.7。

![](/md/blog.011.png)

图4.7商品类别实体图

商品信息实体图4.8。

![](/md/blog.012.png)

图4.8商品信息实体图

4.3数据库逻辑设计

数据库名：ssmqi99g

表名：address

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|userid|bigint|20| | | | |否| | |
|4|address|varchar|200| | | | |否| | |
|5|name|varchar|200| | | | |否| | |
|6|phone|varchar|200| | | | |否| | |
|7|isdefault|varchar|200| | | | |否| | |

||
| :- |
表名：cart

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|tablename|varchar|200| | | | |是|kafeixinxi| |
|4|userid|bigint|20| | | | |否| | |
|5|goodid|bigint|20| | | | |否| | |
|6|goodname|varchar|200| | | | |是| | |
|7|picture|varchar|200| | | | |是| | |
|8|buynumber|int|11| | | | |否| | |
|9|price|float| | | | | |是| | |
|10|discountprice|float| | | | | |是| | |

||
| :- |
表名：chat

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|userid|bigint|20| | | | |否| | |
|4|adminid|bigint|20| | | | |是| | |
|5|ask|longtext| | | | | |是| | |
|6|reply|longtext| | | | | |是| | |
|7|isreply|int|11| | | | |是| | |

||
| :- |
表名：config

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|name|varchar|100| | | | |否| | |
|3|value|varchar|100| | | | |是| | |

||
| :- |
表名：discusskafeixinxi

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|refid|bigint|20| | | | |否| | |
|4|userid|bigint|20| | | | |否| | |
|5|nickname|varchar|200| | | | |是| | |
|6|content|longtext| | | | | |否| | |
|7|reply|longtext| | | | | |是| | |

||
| :- |
表名：kafeileixing

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|kafeileixing|varchar|200| | | | |否| | |

||
| :- |
表名：kafeixinxi

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|kafeimingcheng|varchar|200| | | | |否| | |
|4|kafeileixing|varchar|200| | | | |否| | |
|5|tupian|varchar|200| | | | |否| | |
|6|zhuliao|varchar|200| | | | |是| | |
|7|guige|varchar|200| | | | |是| | |
|8|lengreyin|varchar|200| | | | |是| | |
|9|kafeixiangqing|longtext| | | | | |是| | |
|10|clicktime|datetime| | | | | |是| | |
|11|clicknum|int|11| | | | |是|0| |
|12|price|float| | | | | |否| | |

||
| :- |
表名：news

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|title|varchar|200| | | | |否| | |
|4|introduction|longtext| | | | | |是| | |
|5|picture|varchar|200| | | | |否| | |
|6|content|longtext| | | | | |否| | |

||
| :- |
表名：orders

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|orderid|varchar|200| | | | |否| | |
|4|tablename|varchar|200| | | | |是|kafeixinxi| |
|5|userid|bigint|20| | | | |否| | |
|6|goodid|bigint|20| | | | |否| | |
|7|goodname|varchar|200| | | | |是| | |
|8|picture|varchar|200| | | | |是| | |
|9|buynumber|int|11| | | | |否| | |
|10|price|float| | | | | |否|0| |
|11|discountprice|float| | | | | |是|0| |
|12|total|float| | | | | |否|0| |
|13|discounttotal|float| | | | | |是|0| |
|14|type|int|11| | | | |是|1| |
|15|status|varchar|200| | | | |是| | |
|16|address|varchar|200| | | | |是| | |
|17|tel|varchar|200| | | | |是| | |
|18|consignee|varchar|200| | | | |是| | |

||
| :- |
表名：storeup

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|userid|bigint|20| | | | |否| | |
|4|refid|bigint|20| | | | |是| | |
|5|tablename|varchar|200| | | | |是| | |
|6|name|varchar|200| | | | |否| | |
|7|picture|varchar|200| | | | |否| | |

||
| :- |
表名：token

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|userid|bigint|20| | | | |否| | |
|3|username|varchar|100| | | | |否| | |
|4|tablename|varchar|100| | | | |是| | |
|5|role|varchar|100| | | | |是| | |
|6|token|varchar|200| | | | |否| | |
|7|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|8|expiratedtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |

||
| :- |
表名：users

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|username|varchar|100| | | | |否| | |
|3|password|varchar|100| | | | |否| | |
|4|role|varchar|100| | | | |是|管理员| |
|5|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |

||
| :- |
表名：yonghu

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|yonghuming|varchar|200| | | | |否| | |
|4|mima|varchar|200| | | | |否| | |
|5|xingming|varchar|200| | | | |否| | |
|6|xingbie|varchar|200| | | | |是| | |
|7|touxiang|varchar|200| | | | |是| | |
|8|lianxidianhua|varchar|200| | | | |是| | |
|9|money|float| | | | | |是|0| |

||
| :- |

[第五章 功能的实现](#_Toc10150_#_Toc10150_)

5.1 网站界面实现

(1)界面设计原则

用户原则。人机界面设计首先要确立用户类型。划分类型可以从不同的角度，视实际情况而定。如果进入的权限不一样，系统中菜单项中的可用的项也就相应的不一样。

信息最小量原则。人机界面设计要尽量减少用户记忆负担，采用有助于记忆的设计方案。

帮助和提示原则。要对用户的操作命令做出反应，帮助用户处理问题。在系统内部处理工作要有提示，尽量把主动权让给用户，例如删除功能，要提示用户是否确定要删除该条记录。

(2)数据输入界面设计

数据输入界面往往占终端用户的大部分使用时间，也是计算机系统中最易出错的部分之一。其总目标：简化用户的工作，并尽可能降低输入出错率，还要容忍用户错误。这些要求在设计实现时可采用多种方法：

尽可能减轻用户记忆，采用列表选择。对共同输入内容设置默认值；使用代码和缩写等；系统自动记录用户已输入过的内容，例如打印页面的设置，根据每个不同的用户有不同的值。

使界面有一致风格的数据输入界面。

防止用户出错。对删除必须再一次确认，对致命错误，要警告并退出。对空值输入，要给出提示信息；在输入框中也有限制，限制可输入的字符类型。

提供反馈。要使用户能查看已输入的内容，并提示有效的输入回答。  

数据输入界面若条件具备尽可能采用自动输入。

5.2 主要功能代码

5.2.1登录模块详细设计

本系统角色有两类，管理员、注册用户，他们都属于系统的用户，用户登录实现的过程主要有几个步骤，首先对用户输入的信息进行保存然后利用JAVA程序从数据库中进行检索看是不是有用户输入的信息在数据库中是否存在如果存在就返回正确的结果，如果不正确就返回错误的结果。如果结果数据库中存在就显示登录成功，如果数据库不存在就显示失败请重新登录。

系统登录的运行效果如图5.1。

![](/md/blog.013.png)

图5.1用户登录运行界面

系统登录模块的流程图如图5.2。

![](/md/blog.014.png)

图5.2 系统登录流程图

5.2.2用户注册模块

用户需要注册登录才能进行购买商品。所以网站提供了一个用户注册和登陆的模块，用户需要正确输入账号和密码才能登录系统。

用户注册实现的过程主要是将用户填写的数据写入数据库中即可。

用户注册的流程图如图5.3。

![](/md/blog.015.png)

图5.3用户流程图

用户注册如图5.4。

![](/md/blog.016.png)

图5.4用户注册

5.2.3在线客服模块的实现

在线客服需要用户登录后才可以实现。添加问题信息的流程图如图5.5。

![](/md/blog.017.png)

图5.5添加问题信息流程图

发布问题信息的界面如图5.6。

![](/md/blog.018.png)

图5.6发布问题信息

5.2.4个人中心管理模块

管理员登入系统，可以添加新的管理员用户，删除现有的管理员，也可以对自己的密码进行修改。修改密码，添加删除管理员实现的过程主要是将填写的数据写入数据库中即可。个人中心管理界面如图5.7 。

![](/md/blog.019.png)

图5.7个人中心管理界面

5.2.5咖啡信息管理模块的实现

管理员登录系统后，可以添加上传咖啡信息，管理员可以对咖啡信息进行增删改查，用户在前台登录后可以查询咖啡信息。

咖啡信息管理的界面如图5.8。

![](/md/blog.020.png)

图5.8咖啡信息管理界面

5.2.6咖啡类别管理模块的实现

管理员登录系统后，可以添加上传商品类别，管理员可以对商品类别进行增删改查，用户在前台登录后可以查询商品类别，商家上架商品时需要指定商品类别。

商品类别管理的界面如图5.9。

![](/md/blog.021.png)

图5.9商品类别管理界面

5.2.7系统管理模块的实现

管理员登录系统后，可以管理咖啡资讯和在线客服以及轮播图。实现界面如下图5.10所示：

![](/md/blog.022.png)

图5.10系统管理界面

5.2.8下单流程模块的实现

首先，用户经过注册登录系统前台，进行商品购买，用户选择商品和购买数量，进行添加购物车，用户进入个人后台，进行购物车结算，生成订单，商家登录后台进行用户订单审核，审核通过，进行商品发货，用户购买成功。

下单流程的界面如图5.11。

![](/md/blog.023.png)

![](/md/blog.024.png)

![](/md/blog.025.png)

图5.11下单流程界面

5.2.9订单管理模块设计

订单管理模块分为两部分：用户的订单管理和管理员的订单管理，用户在前台进行商品的在线下单，登录个人后台之后，选择购物车的订单，生成有最终订单，付款成功后，这样在管理员后台就可以看到该单子。

订单管理的界面如图5.12。

![](/md/blog.026.png)

图5.12订单管理界面

5.2.10用户前台界面模块

用户前台功能有查看咖啡资讯、商品、个人中心、购物车、在线客服等信息，进行用户注册，登录后进行在线咨询，商品购买等。用户后台功能有个人资料管理、我的收藏管理、我的订单管理等，主要是将在前台添加进行购物车的商品进行生成订单。

![](/md/blog.027.png)

图5-13用户前台界面

第六章 系统测试

6.1 测试目的

软件测试是软件代码生成后必不可少的一步，软件测试包括模块（单元）测试，功能测试、系统的完整性测试、性能测试、安全性测试、数据库的一致性测试等，测试的目的是尽可能多的发现程序中的错误，通过测试使软件的错误减少，使系统的可靠性进一步提高。在测试之初，由于数据库中的数据都是刚开始编程时随便输入的，一点实用性也没有，所以我们又把数据库中的数据全部清理了一下，输入了一些真实可用的数据，以便完成后面的数据测试。

6.2 测试内容

第一个测试阶段：测试基本信息录入及相关处理模块。测试录入数据的可靠性，数据访问的高效性以及相应的容错、纠错机制的健壮性。

第二个测试阶段：订单管理、用户管理及相关操作模块。测试购物流程时数据的正确性、完整性，保证系统正常的工作循环。

第三个测试阶段：测试查询模块。测试查询时数据的正确性、完整性。

6.3 系统测试

6.3.1 测试的数据

在进行编写调试时，我都是按照“编码→测试→修改→再测试（→再修改）”方式进行，所需的数据都是由本人自己添加，系统在设计中使用的测试数据也是由本人随机输入产生。

6.3.2 系统测试方法

首先在自己的电脑上进行多次测试，保证不能有错误和过失，其次是在安装有数据库Mysql和Eclipse的同学电脑上进行测试，测试在不同的电脑上本系统能否运行正常，以达到测试的效果。

6.3.3 系统测试项目表

测试项目表如下：





表5-1 测试项目表

|序号|测试项目|内容和目的|测试结果|
| :-: | :-: | :-: | :-: |
|1|注册用户登录|输入正确账号与密码|可以登录|
|||输入错误账号与密码|提示错误的信息|
|2|管理员登录|输入正确账号与密码|可以登录|
|||输入错误账号与密码|提示错误的信息|


|3|<p>用户管理</p><p>（添加，修改，删除）</p>|输入正确信息|成功完成|
| :-: | :-: | :-: | :-: |
|||输入错误信息|操作失败|
|4|修改登录密码|修改新的密码|成功完成|
|5|<p>咖啡管理</p><p>（添加，修改，删除）</p>|输入正确信息|成功完成|
|||输入错误信息|操作失败|
|6|<p>订单管理</p><p>（添加，修改，删除）</p>|输入正确信息|成功完成|
|||输入错误信息|操作失败|
|7|<p>咖啡资讯管理</p><p>（添加，修改，删除）</p>|输入正确信息|成功完成|
|||输入错误信息|操作失败|
|8|<p>系统管理</p><p>（修改，删除）</p>|输入正确信息|成功完成|
|||输入错误信息|操作失败|
|9|<p>购物车管理</p><p>（添加，修改，删除）</p>|输入正确信息|成功完成|
|||输入错误信息|操作失败|
6.3.4 系统测试结果

系统运行时均能执行其相应功能，均能实现查看、添加、删除、编辑等功能，且运行显示正常，后台数据库也运行良好，数据保证了一致性和稳定性。
红河学院本科毕业论文 (设计)


[第七章 系统总结与展望](#_Toc22718_#_Toc22718_)

总结：

经过几个月的努力，毕业设计终于做完了。这段时间里，我学到了很多实用的编程知识和技术，通过我不断的学习和试验，查看相关的资料和书籍，让自己头脑中已有的概念逐渐清晰，使自己的作品步步完善起来，每一次改进都是我学习的收获，每一次试验的成功不断见证了我学习的进步。从中我也充分认识到自己能够完成一个可运行与可执行的程序，感受它们给我带来的乐趣和成就感。

咖啡销售系统采用B/S交架构设计开发，采用Eclipse进行开发，编程语言采用Java语言，系统基本上实现了开始的设计目标。

因为我的水平有限，不能与那些专门从事软件开发的人相比，为此，本系统存在许多缺陷和不足的地方，如果有时间将进行进一步修改、完善，使得系统能更好的满足应用的需求。

系统展望

我开发的咖啡销售系统相比之前的需求分析还存在不少的问题，这些问题主要表现在：目前的程序只采用了JAVA技术的一些基本的开发手段和技术手段，程序还有待提高，例如看加入Ajax技术让网站变的更友好，操作更简便。



参考文献

[1]孙辉中.JAVA编程语言在计算机软件开发中的应用[J].网络安全技术与应用,2022(01):49-50.

[2]沙之洲.Java编程语言在计算机软件开发中的应用[J].电子世界,2021(24):125-127.DOI:10.19353/j.cnki.dzsj.2021.24.052.

[3]李雅琴.Java编程语言的优势及其应用实践研究[J].互联网周刊,2021(24):60-62.

[4]佟亚超.计算机软件Java编程特点及技术探析[J].技术与市场,2021,28(12):86-87+89.

[5]李弟文.应用Vue的百倍课堂Web端系统设计与实现[J].福建电脑,2021,37(12):75-81.DOI:10.16707/j.cnki.fjpc.2021.12.017.

[6]Weidong Sun,Lipeng Zhang,Xi Liu.The rotation of the Pacific Plate induced by the Ontong Java large igneous province[J/OL].Journal of Earth Science:1-20[2022-01-22].http://kns.cnki.net/kcms/detail/42.1788.P.20211126.1641.008.html.

[7]郑玉娟,张亚东.基于Vue.js的微商城前端设计与实现[J].信息技术与信息化,2021(11):101-103.

[8]单树倩,任佳勋.基于SpringBoot和Vue框架的数据库原理网站设计与实现[J].电脑知识与技术,2021,17(30):40-41+50.DOI:10.14004/j.cnki.ckt.2021.2868.

[9]曹书铭.基于Vue的数据可视化生成系统[J].信息技术与信息化,2021(10):128-130.

[10]Vincent Nijman.Tourism Developments Increase Tsunami Disaster Risk in Pangandaran, West Java, Indonesia[J].International Journal of Disaster Risk Science,2021,12(05):764-769.

[11]常佳宁,潘琳.一种基于B/S的网上购物系统设计[J].中国科技信息,2021(15):71-72.

[12]陈继磊. 高并发下购物平台系统的设计与实现[D].山东大学,2021.DOI:10.27272/d.cnki.gshdu.2021.004359.

[13]胡小春,胡凯,陈燕.基于Java的网上购物系统研发[J].信息技术与信息化,2021(01):18-21.

[14]莫竣成,田秀云.基于Java的网上购物平台系统设计[J].机电工程技术,2021,50(01):103-105.

[15]刘建奇. 互联网+咖啡在线销售系统设计与实现[D].黑龙江大学,2018.

[16]零售业现移动商机——Millstone咖啡现场销售系统[J].每周电脑报,2003(09):32.

致  谢

非常感谢我的导师给我的悉心帮助和指导，让我顺利地完成了毕业论文。当然，也感谢母校辛勤培育之恩，各位领导、老师和同学的大力帮助之情，使我学到了许多新的知识，同时也更懂得了一些做学问的道理，这是一笔宝贵的财富。

从选择毕业设计题目，到毕业设计规划，查找相关资料，设计模型，具体实施，结束论文，整个大致的流程中，我的导师都给予了我耐心的指导和默默的关心，设计为期之长，期间遇到了不少问题，也承蒙老师的照顾，真的想对老师说一声：老师，辛苦了，谢谢您。除此之外，我还要致谢我的几位同学的得力相助，我希望我能向他们学习，发扬那种百折不挠、孜孜不倦的对知识求索精神，那种至高无上的敬业精神，马上我就要走向工作单位了，我相信我会时刻用他们的平凡而不简单来鞭策自己。

最后，祝愿我的老师和学友们永远幸福，快乐！











