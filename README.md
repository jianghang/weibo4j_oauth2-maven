# weibo4j_oauth2-maven
微博Java-SDK-Beta3.1.1 Maven工程

1. 默认编译版本为JDK 1.6
2. 使用pom.xml导入该工程，运行打包命令：mvn clean package
3. 本地其它工程引入该Jar包，运行命令：mvn install，其它工程引入该工程的坐标即可，默认坐标：

```
<dependency>
    <groupId>weibo4j</groupId>
    <artifactId>weibo4j-oauth2</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```
