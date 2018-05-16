## ashop-common
通用的工具类，打包方式jar


单元测试可有可无，如果要在common里面做测试的话可以留着 
```xml
  <!-- 单元测试 -->
    <dependency>
        <groupId>junit</groupId>
        <artifactId>junit</artifactId>
        <scope>test</scope>
    </dependency>
```

调用http服务，可能每个都能用到
```xml
 <!-- httpclient -->
    <dependency>
        <groupId>org.apache.httpcomponents</groupId>
        <artifactId>httpclient</artifactId>
    </dependency>
```

> 其他的没什么争议