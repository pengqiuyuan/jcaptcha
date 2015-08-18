# jcaptcha
移除  com.sun.image.codec 支持 OpenJDK 7

# 效果图

# 问题

# 替代 jcaptcha-1.0 就好了
```
	<dependencies>
			<dependency>
				<groupId>com.octo.captcha</groupId>
				<artifactId>jcaptcha</artifactId>
				<version>1.0</version>
			</dependency>
	</dependencies>
	
	<repositories>
		 <!-- JCaptcha -->
		<repository>
            <id>atlassian-m2-repository</id>
            <name>atlassian m2 Snapshot Repository</name>
            <url>https://maven.atlassian.com/repository/public/</url>
            <releases><enabled>true</enabled></releases>
            <snapshots><enabled>true</enabled></snapshots>
        </repository>
	</repositories>
```
