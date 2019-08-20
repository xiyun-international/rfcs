# 摘要

为了避免单独维护路由配置文件，可以在业务文件内部用写注解的方式，声明路由信息。

# 动机

在开发业务页面时，每次都需要维护一个路由关系影射文件，为了避免这种情况，我们要像 Java 语言一样，通过[注解](http://www.ityouknow.com/springboot/2016/01/06/spring-boot-quick-start.html)的方式，在文件内部来声明路由。

### 调研方向

- Babel Plugin
- Webpack Plugin

