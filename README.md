# Spring_Security_Login_Mysql
Database authentication, using Spring-JDBC and MySQL

1. run script mysql.sql  to create tables to store the users and roles detail

2.paste fol owing in pom.xml to embed tomcat
_______________________________________________
			<plugin>
				<groupId>org.apache.tomcat.maven</groupId>
				<artifactId>tomcat7-maven-plugin</artifactId>
				<version>2.2</version>
				<configuration>
					<port>8080</port>
					<path>/</path>
				</configuration>
			</plugin>
____________________________________________




3. to run local tomcat

mvn clean install -DskipTests=true      

mvn tomcat7:run-war-only 

http://localhost:8080/login

4. login with 'ericli','123456' to be admin
   login with 'alex','123456' as normal user

checked!

***REFmkyong
