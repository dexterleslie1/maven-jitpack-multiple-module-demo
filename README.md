# maven-jitpack-multiple-module-demo
演示maven项目多模块发布到jitpack

##### 参考
https://github.com/jitpack/maven-modular

> 引用全部模块
```xml
<dependency>
    <groupId>com.github.dexterleslie1</groupId>
    <artifactId>maven-jitpack-multiple-module-demo</artifactId>
    <version>1.0.0</version>
</dependency>
```

> 引用module1
```xml
<dependency>
    <groupId>com.github.dexterleslie1.maven-jitpack-multiple-module-demo</groupId>
    <artifactId>module1</artifactId>
    <version>1.0.0</version>
</dependency>
```