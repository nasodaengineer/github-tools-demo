# API 文档

## 概述
这是一个使用GitHub工具创建的演示项目的API文档。

## 端点

### GET /hello
返回问候消息

**响应：**
```
Hello, GitHub Tools Demo!
```

### GET /api/status
返回应用程序状态

**响应：**
```
Application is running successfully!
```

## 使用示例

```bash
# 启动应用程序
mvn spring-boot:run

# 测试端点
curl http://localhost:8080/hello
curl http://localhost:8080/api/status
```