# 你好，我是 AkumaYUC

**AI Agent 与 LLM 工具方向的开发者**

围绕 DeepSeek Harness 插件生态、MCP 工具链与图像识别自动化做开源。
从使用者变成改它的人：把自己踩到的坑补回上游，把重复的录单从手上拿走。

## 当前方向

- **开发与贡献：** Agent 插件、模型 Provider 与更新链路、MCP 工具、桌面端图像识别自动化。
- **学习与探索：** 上下文工程、Pipeline 编排与调试工具、供应链计划与排程。

## 开源贡献

### [Our Free Model / OFM](https://github.com/Ebony-Vinyl/dsh-our-free-model)

开源贡献者｜面向 DeepSeek Harness 的免费模型 Provider 插件。修复更新器回退阶段的瞬时重命名失败并复用已校验的暂存目录（[PR #503](https://github.com/Ebony-Vinyl/dsh-our-free-model/pull/503)）；提交并跟进了 [Issue #475](https://github.com/Ebony-Vinyl/dsh-our-free-model/issues/475) 与 [Issue #509](https://github.com/Ebony-Vinyl/dsh-our-free-model/issues/509) 的复现与分析。

[![OFM 上游 Star](https://img.shields.io/github/stars/Ebony-Vinyl/dsh-our-free-model?style=flat&label=%E4%B8%8A%E6%B8%B8%20Star)](https://github.com/Ebony-Vinyl/dsh-our-free-model/stargazers)

### [MCP Atlassian](https://github.com/sooperset/mcp-atlassian)

使用者与反馈者｜报告 Markdown 图片语法被 `markdown_to_adf` 转换破坏的问题（[Issue #1679](https://github.com/sooperset/mcp-atlassian/issues/1679)）。

### [MaaPipelineEditor](https://github.com/kqcoxn/MaaPipelineEditor)

使用者与反馈者｜报告 `mpelb` 忽略 `config.json` 中 `file.root` 并在回退工作目录后死锁崩溃（[Issue #96](https://github.com/kqcoxn/MaaPipelineEditor/issues/96)）。

### [frePPLe](https://github.com/frePPLe/frepple)

贡献者｜补全简体中文翻译并修正机翻文案（[PR #768](https://github.com/frePPLe/frepple/pull/768)）；修复文档中失效的翻译文件链接并补齐缺失语言（[PR #766](https://github.com/frePPLe/frepple/pull/766)）。

[![frePPLe 上游 Star](https://img.shields.io/github/stars/frePPLe/frepple?style=flat&label=%E4%B8%8A%E6%B8%B8%20Star)](https://github.com/frePPLe/frepple/stargazers)

## 我的项目

### [MaaXA](https://github.com/AkumaYUC/MaaXA)

金蝶云自动化办公助手：把 Excel 调拨单拖进界面，自动逐单录入，任务全部成功后归档副本并按保留期清理过期文件。
基于 [MaaFramework](https://github.com/MaaXYZ/MaaFramework)，界面使用 [MFAAvalonia](https://github.com/MaaXYZ/MFAAvalonia)，已发布至 v1.0.4。

[![MaaXA Release](https://img.shields.io/github/v/release/AkumaYUC/MaaXA?style=flat&label=release)](https://github.com/AkumaYUC/MaaXA/releases)
[![MaaXA Top Language](https://img.shields.io/github/languages/top/AkumaYUC/MaaXA?style=flat)](https://github.com/AkumaYUC/MaaXA)

[查看代码与使用说明](https://github.com/AkumaYUC/MaaXA#readme)

## 技术与工程

**AI / LLM：** DeepSeek Harness、Agent 插件、模型 Provider、MCP 工具、更新与发布链路。

**桌面与自动化：** C# / .NET、Avalonia、MaaFramework、图像识别与 Pipeline 编排。

**工程实现：** Python · JavaScript / TypeScript · C++ · PowerShell · Git / GitHub Actions。

## 联系

项目交流与问题反馈优先开 Issue：[MaaXA Issues](https://github.com/AkumaYUC/MaaXA/issues)。
贡献 OFM 用的 Fork：[AkumaYUC/dsh-our-free-model](https://github.com/AkumaYUC/dsh-our-free-model)。
