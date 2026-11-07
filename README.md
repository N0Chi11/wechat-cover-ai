# wechat-cover-ai

AI-powered Codex skill for creating WeChat Official Account covers, including wide covers and matching dual-cover sets.

一个用于生成微信公众号头图的 Codex skill，支持横版单图和风格统一的双封面套图。

## 功能

- 横版头图：默认参考 900 × 383 像素，约 2.35:1。
- 双封面套图：生成横版、方版及横图在左、方图在右的拼接图。
- 内含可画模板参考链接和尺寸资料。

## 使用方法

将仓库中的 `wechat-cover-ai` 文件夹复制到 Codex 的 skills 目录（通常为 `~/.codex/skills/`），然后在 Codex 中输入：

> 使用 $wechat-cover-ai，根据这篇文章生成公众号双封面套图。

生成图片需要当前环境支持图像生成。成品应检查文字、实际尺寸和微信后台裁切效果；参考模板及素材的可用性和授权以对应平台为准。
