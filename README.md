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

## LICENSE

<a href="https://www.gnu.org/licenses/agpl-3.0.en.html">
<img src="https://www.gnu.org/graphics/agplv3-155x51.png">
</a>

本项目使用 `AGPLv3` 协议开源，您可以在 [GitHub](https://github.com/yukichan-bot-module/MiraiGo-module-morning) 获取本项目源代码。为了整个社区的良性发展，我们强烈建议您做到以下几点：

- **间接接触（包括但不限于使用 `Http API` 或 跨进程技术）到本项目的软件使用 `AGPLv3` 开源**
- **不鼓励，不支持一切商业使用**
