1、JavaEE是一组规范的集合。

# 2、JavaEE的13种核心技术规范：
##  2.1、JDBC（Java Database）数据库连接
##  2.2、JNDI（Java Naming and Directory Interfaces）Java 的命名和目录接口
##  2.3、EJB（Enterprise JavaBean）
##  2.4、RMI（Remote Method Invoke）远程方法调用
##  2.5、Java IDL（Interface Description Language）/CORBA（Common Object Broker Architecture）Java 接口定义语言/公用对象请求代理程序体系结构
  2.6、Servlet 
  2.7、JSP（Java Server Pages）
  2.8、XML（Extensible Markup Language）可扩展白标记语言
  2.9、JMS（Java Message Service）Java 消息服务
  2.10、JTA（Java Transaction API）Java 事务 API
  2.11、JTS（Java Transaction Service）Java 事务服务
  2.12、JavaMail
  2.13、JAF（JavaBean Activation Framework）
3、JavaWeb主要指以Java语言为基础，利用JavaEE中的Servlet、JSP等技术开发动态页面，方便用户通过浏览器与服务器后台交互。JavaWeb应用程序可运行在一个轻量级的应用服务器中，比如Tomcat。。
4、Tomcat服务器 = Web服务器 + Servlet/JSP容器（Web容器）
5、Servlet是一个Java类，运行在Servlet容器中（如Tomcat），负责接收请求，调用Service处理数据，负责响应数据。
6、JSP本质上就是一个Servlet。每个JSP 页面在第一次被访问时，JSP引擎将它翻译成一个Servlet源程序，接着再把这个Servlet源程序编译成Servlet的class类文件，然后再由WEB容器像调用普通Servlet程序一样的方式来装载和解释执行这个由JSP页面翻译成的Servlet程序。
