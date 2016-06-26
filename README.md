# spring_mybatis
<h3 background="red">spring + springmvc + mybatis + log4j  整合</h3><br>
log4j-1.2.15.jar<br>
log4j-web-2.6.1.jar <br>
mybatis-3.1.1.jar <br>
mybatis-spring-1.3.0.jar <br>  
mysql-connector-java-5.1.7-bin.jar <br>


以下是4.3.0全部spring jar包<br>
spring-aop-4.3.0.RELEASE-sources.jar <br>
spring-aop-4.3.0.RELEASE.jar <br>
spring-aspects-4.3.0.RELEASE-sources.jar <br>
spring-aspects-4.3.0.RELEASE.jar <br>
spring-beans-4.3.0.RELEASE-sources.jar <br>
spring-beans-4.3.0.RELEASE.jar <br>
spring-context-4.3.0.RELEASE-sources.jar <br>
spring-context-4.3.0.RELEASE.jar <br>
spring-context-support-4.3.0.RELEASE-sources.jar <br>
spring-context-support-4.3.0.RELEASE.jar <br>
spring-core-4.3.0.RELEASE-sources.jar <br>
spring-core-4.3.0.RELEASE.jar <br>
spring-expression-4.3.0.RELEASE-sources.jar <br>
spring-expression-4.3.0.RELEASE.jar <br>
spring-instrument-4.3.0.RELEASE-sources.jar <br>
spring-instrument-4.3.0.RELEASE.jar <br>
spring-instrument-tomcat-4.3.0.RELEASE-sources.jar <br>
spring-instrument-tomcat-4.3.0.RELEASE.jar <br>
spring-jdbc-4.3.0.RELEASE-sources.jar <br>
spring-jdbc-4.3.0.RELEASE.jar <br>
spring-jms-4.3.0.RELEASE-sources.jar <br>
spring-jms-4.3.0.RELEASE.jar <br>
spring-messaging-4.3.0.RELEASE-sources.jar <br>
spring-messaging-4.3.0.RELEASE.jar <br>
spring-orm-4.3.0.RELEASE-sources.jar <br>
spring-orm-4.3.0.RELEASE.jar <br>
spring-oxm-4.3.0.RELEASE-sources.jar <br>
spring-oxm-4.3.0.RELEASE.jar <br>
spring-test-4.3.0.RELEASE-sources.jar <br>
spring-test-4.3.0.RELEASE.jar <br>
spring-tx-4.3.0.RELEASE-sources.jar <br>
spring-tx-4.3.0.RELEASE.jar <br>
spring-web-4.3.0.RELEASE-sources.jar <br>
spring-web-4.3.0.RELEASE.jar <br>
spring-webmvc-4.3.0.RELEASE-sources.jar <br>
spring-webmvc-4.3.0.RELEASE.jar <br>
spring-webmvc-portlet-4.3.0.RELEASE-sources.jar <br>
spring-webmvc-portlet-4.3.0.RELEASE.jar <br>
spring-websocket-4.3.0.RELEASE-sources.jar <br>
spring-websocket-4.3.0.RELEASE.jar <br>


在工作单位没有遇到问题,
移植到家里的电脑,在展示视图数据时,报了如下错误:

NoClassDefFoundError: javax/servlet/jsp/jstl/core/Config
 
使用spring4.0.5 mvc进行开发，使用tomcat容器，通过url映射寻找view的时候，会报错NoClassDefFoundError: javax/servlet/jsp/jstl/core/Config，如果随便去找个jstl包过来放入web-inf/lib会报错，正确的下载地址 <br>
http://archive.apache.org/dist/jakarta/taglibs/standard/binaries/  <br> 在这里，下载jakarta-taglibs-standard-1.1.2.zip这个包，解压缩后将standard和jstl两个包放入lib下即可 
