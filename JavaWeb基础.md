1、JavaEE是一组规范的集合。

2、JavaEE的13种核心技术规范：

- 2.1、JDBC（Java Database）数据库连接
- 2.2、JNDI（Java Naming and Directory Interfaces）Java 的命名和目录接口
- 2.3、EJB（Enterprise JavaBean）
- 2.4、RMI（Remote Method Invoke）远程方法调用
- 2.5、Java IDL（Interface Description Language）/CORBA（Common Object Broker Architecture）Java 接口定义语言/公用对象请求代理程序体系结构
- 2.6、Servlet 
- 2.7、JSP（Java Server Pages）
- 2.8、XML（Extensible Markup Language）可扩展白标记语言
- 2.9、JMS（Java Message Service）Java 消息服务
- 2.10、JTA（Java Transaction API）Java 事务 API
- 2.11、JTS（Java Transaction Service）Java 事务服务
- 2.12、JavaMail
- 2.13、JAF（JavaBean Activation Framework）

3、JavaWeb主要指以Java语言为基础，利用JavaEE中的Servlet、JSP等技术开发动态页面，方便用户通过浏览器与服务器后台交互。JavaWeb应用程序可运行在一个轻量级的应用服务器中，比如Tomcat。

4、Tomcat服务器 = Web服务器 + Servlet/JSP容器（Web容器）

5、狭义的Servlet是指Java语言实现的一个接口，广义的Servlet是指任何实现了这个Servlet接口的类，一般情况下，人们将Servlet理解为后者。Servlet运行于支持Java的应用服务器中(如Tomcat)。从原理上讲，Servlet可以响应任何类型的请求，但绝大多数情况下Servlet只用来扩展基于HTTP协议的Web服务器。

6、JSP本质上就是一个Servlet。每个JSP 页面在第一次被访问时，JSP引擎将它翻译成一个Servlet源程序，接着再把这个Servlet源程序编译成Servlet的class类文件，然后再由应用服务器中(如Tomcat)像调用普通Servlet程序一样的方式来装载和解释执行这个由JSP页面翻译成的Servlet程序。

7、Spring致力于Java EE应用各层的解决方案，而不仅仅专注于某一层的方案。可以说，Spring是企业应用开发的“一站式”选择，并贯穿表现层、业务层及持久层。然而，Spring并不想取代那些已有的框架，而是要与它们无缝整合。
