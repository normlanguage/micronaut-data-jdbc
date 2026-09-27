# Micronaut Data JDBC 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[H2 仓库示例](sample/jdbc/Main.norm)启动 Micronaut 容器，创建内存数据库表，通过 `@JdbcRepository` 插入记录并按 ID 读取。[消费者模块](sample/jdbc/module.norm)声明 JDBC、H2、注入和配置依赖。

在仓库根目录运行：

```sh
norm run samples/sample/jdbc/Main.norm
```

程序校验读取的文本并输出 `Hello, Norm`。
