<h1>
    <img src="worldedit-logo.svg" alt="WorldEdit" width="400" />
</h1>

**WorldEdit，但是汉化版。**

本仓库是 [EngineHub/WorldEdit](https://github.com/EngineHub/WorldEdit) 的简体中文本地化分支，在原版基础上新增了 `strings_zh_CN.json` 语言文件，其余代码保持不变。

> 原版 WorldEdit 是一款运行在游戏内的 Minecraft 地图编辑器，支持选区、原理图、复制粘贴、笔刷与脚本等功能，可在创造/生存模式的单人或服务器中使用。

## 下载

如需直接使用（无需汉化），请从 Modrinth 获取官方版本：

https://modrinth.com/plugin/worldedit/versions

如需使用汉化版，请在本仓库 [Releases](../../releases) 页面下载，或自行从源码构建。

## 汉化说明

| 文件 | 说明 |
|------|------|
| `worldedit-core/src/main/resources/lang/strings_zh_CN.json` | 简体中文翻译，覆盖全部界面字符串 |

服务端启用方式：在 JVM 启动参数中添加 `-Duser.language=zh -Duser.country=CN`，WorldEdit 会自动加载中文语言文件。

## 从源码构建

需要 Java 21+，在项目根目录执行：

```
# Linux / macOS
./gradlew :worldedit-bukkit:build

# Windows（命令提示符）
gradlew :worldedit-bukkit:build

# Windows（PowerShell）
.\gradlew :worldedit-bukkit:build
```

详细说明参见 [COMPILING.md](COMPILING.md)。

## 相关链接

* [官方网站](https://enginehub.org/)
* [Discord 社区](https://discord.gg/enginehub)
* [问题追踪（原版）](https://github.com/EngineHub/WorldEdit/issues)
* [持续集成](https://builds.enginehub.org) [![Build Status](https://ci.enginehub.org/app/rest/builds/buildType:bt10,branch:master/statusIcon.svg)](https://ci.enginehub.org/viewType.html?buildTypeId=bt10&guest=1)
* [官方文档](https://worldedit.enginehub.org/en/latest/)

## 许可证

WorldEdit 遵循 [GPL v3](LICENSE.txt) 开源协议，本汉化分支同样适用。
