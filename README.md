## 剑来社区

##资料
 
 [Spring文档](https://spring.io/guides)
 
 [Spring MVC](https://spring.io/guides/gs/serving-web-content/)
 
 [BootStrap](https://v3.bootcss.com/)
 ##工具
 
 [GitHub](https://git-scm.com/downloads)
 
 [FlyWay](https://flywaydb.org/getstarted/firststeps/maven)
 
 
 CREATE TABLE USER
 (
   ID int AUTO_INCREMENT PRIMARY KEY NOT NULL,
   ACCOUNT_ID VARCHAR(100),
   USERNAME VARCHAR(50),
   TOKEN VARCHAR(36),
   GMT_CREATE BIGINT,
   GMT_MODIFIED BIGINT
 );