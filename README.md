# mavendemo-pluginsql
1.基于https://github.com/a304407493/mavendemo-log4j.git 创建maven骨架的java项目<br/>
2.支持servlet2.3：增加jetty9插件和tomcat插件（没有日志）<br/> 
  2.1.jetty9可以正常启动(webapp未生效，shutdown未生效)<br/> 
  2.2.tomcat8无法正常启动(全部未生效)<br/> 
  2.3.没有配置slf4j<br/> 
  2.4.增加maven的sql插件<br/> 
    执行方式：<br/>
      2.4.1.在mysql中创建yourdb的数据库<br/> 
      2.4.2.执行命令mvn test（sql:execute不起作用）<br/> 
      注： 2.4.2.1.记得修改pom.xml的配置文件 2.4.2.2.创建yourdb的数据库<br/>
