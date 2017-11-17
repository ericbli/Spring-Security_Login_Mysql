# Spring-Security_Login_Mysql
Database authentication, using Spring-JDBC and MySQL
1.paste fol owing in pom.xml to embed tomcat
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
2. to run local tomcat
mvn clean install -DskipTests=true      
mvn tomcat7:run-war-only 




***REFmkyong
