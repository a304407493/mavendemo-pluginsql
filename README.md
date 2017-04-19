# mavendemo-pluginsql
支持servlet2.3：增加jetty9插件和tomcat插件（没有日志） 
  1.jetty9可以正常启动(webapp未生效，shutdown未生效) 
  2.tomcat8无法正常启动(全部未生效) 
  3.没有配置slf4j 
  4.增加maven的sql插件 
    执行方式：
      1.在mysql中创建yourdb的数据库 
      2.执行命令mvn test（sql:execute不起作用） 
      注： 1.记得修改pom.xml的配置文件 2.创建yourdb的数据库
