# LCML

LCML 是一款现代化的 Minecraft 启动器（Windows）。本仓库只用于发布安装包、说明文档与收集反馈，不包含源码。

## 下载

在 [Releases](https://github.com/LRCZCM/LCML-release/releases/latest) 下载最新的 `LCML-<版本>.exe`。版本号为发布日期加当天序号，例如 `26.11.10.1` 是 2026 年 11 月 10 日的第 1 版。每个版本的更新内容见 [更新日志](CHANGELOG.md)。

可用 `SHA256SUMS.txt` 核对下载的文件是否完整：

```powershell
Get-FileHash LCML-<版本>.exe -Algorithm SHA256
```

## 使用

- 系统：Windows 10 / 11（64 位）。不需要安装 Java，启动器自带运行环境。
- 把 exe 放进一个单独的文件夹后双击运行。首次运行会在 exe 旁边生成 `LCML/`（启动器数据）与 `.minecraft/`（默认游戏目录）。
- 更新：下载新版 exe 替换旧的即可，原有数据保留。

## 反馈

在 [Issues](https://github.com/LRCZCM/LCML-release/issues/new/choose) 提交问题或建议。Issues 是公开的，上传日志或诊断包前请检查其中是否有不想公开的信息。

## 使用条款

- LCML 免费使用，不提供任何形式的担保。
- 未经许可，不得出售、改动后分发或捆绑分发本软件，不得冒用 LCML 的名称发布。
- LCML 与 Mojang Studios、Microsoft 没有关联。
