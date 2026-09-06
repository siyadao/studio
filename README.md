# 思芽岛 Studio

原生创作工作台，将文稿、代码、日历、TODO、便签墙与开发工具放在一起。

[产品介绍](https://studio.siyadao.cn/) · [下载安装包](https://github.com/siyadao/studio/releases) · [问题反馈](https://github.com/siyadao/studio/issues)

## 下载

请在 Releases 的 **Assets** 中选择对应系统的安装包：

- **macOS（M 芯片）**：`macos-arm64.dmg`，打开后将应用拖入 Applications。
- **Windows（x64）**：`windows-x64.zip`，完整解压后运行 `siyadao.exe`。

标记为 **Pre-release** 的版本用于测试，不是稳定版。首次启动可能出现系统安全提示：macOS 测试包未进行 Apple 公证，Windows 测试包未进行代码签名。请先确认来源及 `SHA256SUMS.txt`，不要关闭系统安全防护。

Windows 便携包中的模型 Worker、MCP 桥接器、PDFium 与运行库请勿移除。其他架构以实际发布附件为准。

## 测试与反馈

请先备份工作区，使用临时文件或数据副本验证启动、文稿保存、日历、TODO、便签墙、魔法球和开发工具。详细限制、验收范围与第三方许可见包内说明及每次版本说明。

报告问题时请提供包名、操作系统版本、复现步骤和必要截图；不要上传密码、令牌、私钥或敏感工作区内容。

本仓库仅分发安装包、版本说明及问题反馈，不包含思芽岛应用源码。GitHub 自动生成的 **Source code** 附件仅对应此分发仓库，不是应用安装包。
