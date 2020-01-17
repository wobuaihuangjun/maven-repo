# maven-repo

## 一、okhttp
### 1、项目添加远程Maven库
在项目的根目录的build.gradle文件中allprojects.repositories添加如下代码：
```
maven {
    url "https://raw.githubusercontent.com/wobuaihuangjun/maven-repo/master"
```

### 2、在使用aar的module的build.gradle文件的dependencies添加依赖

代码如下：
```
implementation 'com.example.okhttp.test:okhttp:0.0.3'
```
