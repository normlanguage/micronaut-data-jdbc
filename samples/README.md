# Micronaut Data JDBC samples

[English](README.md) | [简体中文](README.zh-CN.md)

[H2 repository](sample/jdbc/Main.norm) starts a Micronaut context, creates an in-memory table, inserts a note through `@JdbcRepository`, then retrieves it by ID. The [consumer module](sample/jdbc/module.norm) declares the JDBC, H2, injection, and configuration dependencies.

From the repository root, run:

```sh
norm run samples/sample/jdbc/Main.norm
```

The program checks the retrieved text and prints `Hello, Norm`.
