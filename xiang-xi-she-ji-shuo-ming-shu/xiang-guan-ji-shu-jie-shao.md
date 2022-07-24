# 相关技术介绍

### 2.1深度学习方面

在深度学习的内容上，项目主要使用的平台是百度AI Studio平台，该平台为模型训练提供了充足的算力支持；深度学习用到的框架是百度飞浆（PaddlePaddle），主要使用了飞浆提供的PaddleRS, PPYolo等模型。

#### **AI Studio：** <a href="#ai-studio" id="ai-studio"></a>

百度AI Studio是针对AI学习者的在线一体化学习与实训社区。平台集合了AI教程, 深度学习样例工程, 各领域的经典数据集, 云端的超强运算及存储资源, 以及比赛平台和社区。

#### **PaddlePaddle：** <a href="#paddlepaddle" id="paddlepaddle"></a>

飞桨 (PaddlePaddle)以百度多年的深度学习技术研究和业务应用为基础，集深度学习核心框架、基础模型库、端到端开发套件、工具组件和服务平台于一体，2016 年正式开源，是中国首个自主研发、技术领先、功能完备、开源开放的产业级深度学习平台。

### **2.2 web开发方面** <a href="#22web-kai-fa-fang-mian" id="22web-kai-fa-fang-mian"></a>

Web平台的搭建使用到的技术是Vue + Django + Restful AP(Django Restframework) + MySQL

#### **Django：** <a href="#django" id="django"></a>

Django是一个开放源代码的Web应用框架，由Python写成。采用了MTV(model–template–views)的软件设计模式，即模型（Model），视图（View）和模板（Template）。Django的主要目标是简化数据库驱动的网站的开发。Django注重组件的重用性和“可插拔性”，敏捷开发和DRY法则（Don't Repeat Yourself）。在Django中普遍使用的语言是Python，甚至包括配置文件和数据模型。Django框架的核心包括：一个对象关系映射器，用作数据模型（以Python类的形式定义）和关系型数据库间的介质；一个基于正则表达式的URL分发器；一个视图系统，用于处理请求；以及一个模板系统。核心框架中还包括：一个轻量级的、独立的Web服务器，用于开发和测试；一个表单序列化及验证系统，用于HTML表单和适于数据库存储的数据之间的转换；一个缓存框架，并有几种缓存方式可供选择；中间件支持，允许对请求处理的各个阶段进行干涉；内置的分发系统允许应用程序中的组件采用预定义的信号进行相互间的通信；一个序列化系统，能够生成或读取采用XML或JSON表示的Django模型实例；一个用于扩展模板引擎的能力的系统。

#### **Vue：** <a href="#vue" id="vue"></a>

Vue.js（或简称为Vue）是一个用于创建用户界面的开源的前端JavaScript框架，也是一个创建单页应用的Web应用框架。vue旨在更好地组织与简化Web开发。Vue所关注的核心是MVC模式中的视图层，同时，它也能方便地获取数据更新，并通过组件内部特定的方法实现视图与模型的交互。

#### **RESTful:** <a href="#restful" id="restful"></a>

REST 指的是一组架构约束条件和原则。满足这些约束条件和原则的应用程序或设计就是 RESTful。RESTFUL特点包括：

* 每一个URL代表1种资源；
* 客户端使用GET、POST、PUT、DELETE4个表示操作方式的动词对服务端资源进行操作：GET用来获取资源，POST用来新建资源（也可以用于更新资源），PUT用来更新资源，DELETE用来删除资源；
* 客户端与服务端之间的交互在请求之间是无状态的，从客户端到服务端的每个请求都必须包含理解请求所必需的信息；

#### **MySQL:** <a href="#mysql" id="mysql"></a>

MySQL是一个开源的关系型数据库管理系统，由瑞典MySQL AB 公司开发，属于 Oracle 旗下产品,MySQL 是最流行的关系型数据库管理系统之一。
