<http://www.iocoder.cn/Spring-Boot/hot-swap/?github>

#2
# 基于spring
添加配置
```
        <dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-devtools</artifactId>
            <optional>true</optional> <!-- 可选 -->
        </dependency>
```
## 手动
Build -> Build Project
## 自动
Build project automatically
双击shift -> 查找Registry --> 找到并勾选compiler.automake.allow.when.app.running
# 基于idea
setting -> hotswap
Build -> Build Project