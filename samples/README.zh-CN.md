# jsoup 示例

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) —— 从 HTML 选出链接，并使用安全列表清理不可信标记。这是通过自身的 `Module module()` 声明依赖的独立消费者程序。

在仓库根目录运行：

```sh
norm run samples/hello.norm
```

[module.norm](../jsoup/jsoup/module.norm) 指定 Java 制品版本并定义公开 API。

预期输出：

```text
Read more
/news
<b>Hi</b>
```

API 入口：[module.norm](../jsoup/jsoup/module.norm) 列出公开的 `Document`、`Element` 和 `Safelist`。[适配器验收示例](../examples/sample/jsoup/jsoup/Main.norm)覆盖更多绑定行为。
