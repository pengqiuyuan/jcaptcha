# jcaptcha
移除  com.sun.image.codec 支持 OpenJDK 7


![6fd8112d-04bc-4899-a539-8c41f23b9d7e](https://cloud.githubusercontent.com/assets/4953205/9323015/1d131274-45ae-11e5-9747-99ae0a8efe09.png)

问题
```
ClassNotFoundException: com.sun.image.codec.jpeg.ImageFormatException
```

编译打包项目
```
mvn clean install
```
