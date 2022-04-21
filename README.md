# research-spring

## MVN　バージョン確認
```
$ mvn -version
Apache Maven 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)
Maven home: /usr/local/Cellar/maven/3.6.3_1/libexec
Java version: 1.8.0_202, vendor: Oracle Corporation, runtime: /Library/Java/JavaVirtualMachines/jdk1.8.0_202.jdk/Contents/Home/jre
Default locale: ja_JP, platform encoding: UTF-8
OS name: "mac os x", version: "10.16", arch: "x86_64", family: "mac"
```

## JAVA バージョン確認
```
$ java -version
java version "1.8.0_202"
Java(TM) SE Runtime Environment (build 1.8.0_202-b08)
Java HotSpot(TM) 64-Bit Server VM (build 25.202-b08, mixed mode)
```

## Springプロジェクト作成

### Springプロジェクト作成ガイドライン
https://start.spring.io/

### 作成された圧縮ファイルを解凍
`unzip demo.zip`

### ビルド

`mvn clean install`


### Maven setting.xmlの置き場

```
$ pwd
/usr/local/Cellar/maven/3.6.3_1/libexec/conf

$ ls -ltr
total 32
-rw-r--r--  1 jinghuizhen  admin   3747 11  7  2019 toolchains.xml
-rw-r--r--  1 jinghuizhen  admin  10468 11  7  2019 settings.xml
drwxr-xr-x  3 jinghuizhen  admin     96 11  7  2019 logging
```

### RUN IT!

`$ mvn spring-boot:run`

BUT! whitpage error has occurred!

# OfficeWebSite Sample

`cd hika/hika-sample/complete`

## compile

`$ mvn clean install`

## run it

`$./mvnw spring-boot:run`

## test

`$ curl http://localhost:8080/greeting`

```
<!DOCTYPE HTML>
<html>
<head> 
    <title>Getting Started: Serving Web Content</title> 
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
</head>
<body>
    <p >Hello, World!</p>
</body>
</html>
```


