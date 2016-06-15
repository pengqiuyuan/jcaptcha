# jcaptcha
移除  com.sun.image.codec 支持 OpenJDK 5 6 7 8


![6fd8112d-04bc-4899-a539-8c41f23b9d7e](https://cloud.githubusercontent.com/assets/4953205/9323015/1d131274-45ae-11e5-9747-99ae0a8efe09.png)

问题
```
ClassNotFoundException: com.sun.image.codec.jpeg.ImageFormatException
```

编译打包项目
```
mvn clean install
mvn clean package -Dmaven.test.skip=true
target 下的 jcaptcha-1.0.jar 替换 .m2/repository/com/octo/captcha/jcaptcha/1.0 下的jar 就ok了
```
