# jsoup samples

[English](README.md) | [简体中文](README.zh-CN.md)

[hello.norm](hello.norm) — Select a link from HTML and clean untrusted markup with a safelist. This is a standalone consumer with its own `Module module()` dependency.

From the repository root, run:

```sh
norm run samples/hello.norm
```

[module.norm](../jsoup/jsoup/module.norm) pins the Java artifact and defines the public API.

Expected output:

```text
Read more
/news
<b>Hi</b>
```

API reference: [module.norm](../jsoup/jsoup/module.norm) lists the exposed `Document`, `Element`, and `Safelist`. The module's `Main.norm` remains its own adapter integration entry point.
