# 源码包结构

## 核心包

- java.lang: 核心语言功能，包含基本类型、String、Object、Thread、Exception 等基础类
- java.util: 集合框架、日期时间工具和各种工具类，如 ArrayList、HashMap 等
- java.io: 输入输出操作，文件访问和序列化功能
- java.net: 网络编程功能，包括 Socket、URL 等
- java.nio: 增强的 I/O API，提供通道和选择器等特性
- java.math: 高精度计算（BigInteger 和 BigDecimal）
- java.time: Java 8 引入的日期时间 API
- java.text: 文本处理工具
- java.sql: 数据库连接和操作
- java.security: 安全框架和加密功能
- java.rmi: 远程方法调用
- 
## 扩展包

- javax: Java 标准扩展包
  - javax.swing: Java GUI 开发组件
  - javax.xml: XML 处理 API
  - javax.sql: 数据库扩展 API
  - javax.sound: 音频处理
  - javax.management: Java 管理扩展
  - javax.script: 脚本语言支持
  - javax.security: 安全服务扩展

# 常用的包有哪些
## 核心包（最常用）
- java.lang: 基础类型、String、Object、Thread、Exception 等核心类
- java.util: 集合框架（ArrayList、HashMap）、日期时间、工具类
- java.io: 文件和流操作
- java.net: 网络编程（Socket、URL）
- java.sql: 数据库连接和操作
- java.time: Java 8 日期时间 API（比旧的 Date/Calendar 更好用）
- java.text: 文本格式化和解析
## 扩展包（按需使用）
- javax.swing: 桌面 GUI 应用开发
- javax.xml: XML 处理
- javax.sql: 数据库连接池等高级功能
- javax.servlet: Web 应用开发（通常通过 Web 框架使用）
## 常用新特性（Java 8）
- java.util.function: 函数式接口
- java.util.stream: 流处理 API
## 专业领域（按需了解）
- java.security: 加密和安全
- java.nio: 高性能 I/O 操作
- javax.management: JMX 监控管理


# 对比
## java.util包（**传统**）与java.time包（**现代**）
java.time主要的类：
- LocalDate：仅日期，无时间
- LocalTime：仅时间，无日期
- LocalDateTime：日期和时间，无时区
- ZonedDateTime：完整的日期、时间和时区
- Instant：时间线上的一点
- Duration：时间段
- Period：日期段
- DateTimeFormatter：日期格式化
