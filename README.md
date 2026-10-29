# siyadao/studio · 安装包发行

**只发布桌面安装包、校验文件与版本说明。** 不含应用源码（GitHub 的 Source code zip 是本仓快照，不能当安装包用）。

| 找什么 | 去哪 |
| --- | --- |
| 装哪个文件 | 本页 **[Releases](https://github.com/siyadao/studio/releases)** → Assets |
| 官网介绍 / 在线选平台 | https://studio.siyadao.cn/#download |
| 源码与构建 | https://github.com/siyadao/ai-studio |
| 缺陷与使用问题 | [Issues](https://github.com/siyadao/studio/issues) |

## 选包

以**该次 Release 实际挂出的附件**为准（不同版本平台可能不全）。文件名通常为：

```text
siyadao-v<version>-macos-arm64.dmg
siyadao-v<version>-macos-x64.dmg
siyadao-v<version>-windows-x64-setup.exe
siyadao-v<version>-windows-arm64-setup.exe
siyadao-v<version>-linux-…   # 若该版已发布
```

同目录若有 `SHA256SUMS` / `SHA256SUMS-*.txt`，下载后请先校验再安装。

- **macOS**：打开 DMG，拖入 Applications。  
- **Windows Setup**：运行安装程序；便携 zip 需完整解压后启动 `siyadao.exe`，勿删包内 Worker / 桥接 / PDFium。  
- **Pre-release**：测试通道。未公证或未签名时系统可能告警——核对来源与校验和，不要关闭系统防护。

## 反馈前

备份工作区；用临时数据复现。Issue 请写：**包名、系统版本、步骤**；可附图。勿贴密码、令牌、私钥或整份敏感工作区。
