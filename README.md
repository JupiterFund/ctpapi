# CTP Java API

[![](https://jitpack.io/v/JupiterFund/ctpapi.svg)](https://jitpack.io/#JupiterFund/ctpapi)
[![](https://jitci.com/gh/JupiterFund/ctpapi/svg)](https://jitci.com/gh/JupiterFund/ctpapi)

CTP API是用swig方法在官方C++ API上编译得到。

## 如何使用

* 通过`Maven`或者`Gradle`自动管理依赖，并添加此仓库作为依赖
* 直接下载release中的jar文件，手动加入依赖。

添加依赖

```gradle
dependencies {
  implementation 'com.github.JupiterFund:ctpapi:{{Release}}'
}
```

```maven
<dependency>
    <groupId>com.github.JupiterFund</groupId>
    <artifactId>ctpapi</artifactId>
    <version>{{Release}}</version>
</dependency>
```
