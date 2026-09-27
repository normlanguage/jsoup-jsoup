# jsoup

[English](README.md) | [简体中文](README.zh-CN.md)

The adapter declaration and runnable example are in `jsoup/jsoup`. It pins jsoup 1.23.2 and defines its package coordinates in [module.norm](jsoup/jsoup/module.norm). The public API covers HTML parsing, CSS selection, DOM queries and modification, output settings, cleaning, and HTTP connections. The API census and reasons for unsupported APIs are in the NAR's `binding/java-api.json`.

`JsoupBindingIntegrationTest` covers standalone NAR consumption, the real JAR, DOM behavior, Safelist, and local HTTP acceptance.

[Runnable samples](samples/README.md) demonstrate the library as an external Norm dependency.
