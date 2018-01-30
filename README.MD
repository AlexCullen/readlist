- build.gradle: Gradle构建说明文件
- ReadlistApplication.java: 应用程序的启动引导类（bootstrap class），也是主要的Spring配置类
- application.properties: 用于配置应用程序和Spring Boot的属性
- ReadlistApplicationTest.java: 一个基本的集成测试类

- @SpringBootApplication: 开启了Spring的组建扫描和Spring Boot的自动配置
- @SpringBootApplication: 实际上是将 @Configuration @ComponentScan @EnableAutoConfiguration组合在一起

- @Configuration: 标明该类使用Spring基于Java的配置。
- @ComponentScan: 启用组件扫描
- @EnableAutoConfiguration: 开启Spring Boot的自动配置