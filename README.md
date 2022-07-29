# MiraiGo-module-morning

ID: `com.aimerneige.morning`

Module for [MiraiGo-Template](https://github.com/Logiase/MiraiGo-Template)

## 功能

在 UTC 时间 12:00 AM（北京时间早上 8 点）向全部的群发送“早上好啊！”。

## 使用方法

在适当位置引用本包

```go
package example

imports (
    // ...

    _ "github.com/yukichan-bot-module/MiraiGo-module-morning"

    // ...
)

// ...
```

如果需要，在全局配置文件中填入如下配置过滤指定的群聊：

```yaml
aimerneige:
  morning:
    ignored:
      - 519821281
      - 982715633
```
