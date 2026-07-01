# Ale Forensic Suite Toolkit V1.0

## 📥 下载链接

**百度网盘下载**（推荐使用百度网盘会员下载）

链接: https://pan.baidu.com/s/58cp13CUptMWZHFJZmwQqFg

来自百度网盘超级会员 v10 的分享

---

## 🎉 版本说明

这是 Ale Forensic Suite Toolkit（阿乐取证工具集，简称 AFST）的首个正式版本 V1.0。

### 💎 核心特性

- **AI 赋能**：集成 Claude Code + IDA MCP + JADX MCP + CTF/安全 Skills，AI 辅助逆向分析与取证
- **开箱即用**：无需繁琐配置，一键启动所有取证工具
- **环境隔离**：虚拟机环境 + Python venv，避免工具污染主机系统
- **场景全覆盖**：支持电子数据取证、应急响应、CTF 取证、恶意代码分析
- **持续更新**：基于真实 WP 调研，优先更新高频实战工具

### 🛠️ 包含工具

- **500+ 取证与安全工具**
- **100+ CTF 与安全技能库**
- **AI 辅助逆向分析**（IDA Pro + JADX + MCP）
- **移动端取证**（iLEAPP、ALEAPP、Frida）
- **内存取证**（Volatility 2/3、MemProcFS）
- **密码恢复**（Passware Kit 2022、Hashcat、John the Ripper）
- **恶意代码分析**（IDA Pro、Ghidra、Capa、PEStudio）
- **Windows 取证**（Eric Zimmerman Tools、Hayabusa、Plaso）
- **网络流量分析**（Wireshark、NetworkMiner、Zui）

### 💻 系统环境

- **操作系统**：Windows 11 Workstation 24H2 x64
- **WSL 子系统**：Kali Linux 2025.1（完整安装）
- **推荐配置**：
  - VMware 17.x 或更高版本
  - 内存：8 GB 以上
  - 硬盘：300 GB SSD
  - 处理器：支持 CPU 虚拟化（Intel VT-x / AMD-V）

---

## 📚 使用指南

### 快速开始

1. **下载镜像**：从上方百度网盘链接下载
2. **导入 VMware**：使用 VMware 17.x 打开虚拟机
3. **启动系统**：首次启动建议分配 8GB+ 内存
4. **开始使用**：所有工具已预配置，开箱即用

### AI 辅助分析工作流

```
1. 启动 JADX-GUI / IDA Pro
2. 打开待分析的 APK / EXE 文件
3. 配置 CC Switch 连接 AI 中转站/API 接口
4. 在 Claude Code 中直接询问：
   - "分析这个 APK 的主要功能"
   - "查找可疑的加密函数"
   - "列出所有网络请求"
5. Claude 自动调用 MCP 工具，返回分析结果
```

---

## 🎯 适用场景

- **电子数据取证**：手机取证、计算机取证、网络取证
- **应急响应**：入侵排查、日志分析、恶意代码分析
- **CTF 取证竞赛**：Misc、Forensics 方向题目环境
- **取证比武**：公安、司法、企业安全取证演练
- **安全培训**：取证技能培训、实验室环境搭建

---

## 📖 文档资源

- **GitHub 仓库**：https://github.com/saa1028/Ale-Forensic-Suite-Toolkit
- **完整 README**：https://github.com/saa1028/Ale-Forensic-Suite-Toolkit/blob/main/README.md
- **工具使用手册**：https://github.com/saa1028/Ale-Forensic-Suite-Toolkit/blob/main/docs/afst-forensics-tools.md
- **贡献指南**：https://github.com/saa1028/Ale-Forensic-Suite-Toolkit/blob/main/docs/CONTRIBUTING.md

---

## 📧 技术支持

- **公众号**：阿乐取证工具集（获取更新通知、使用技巧、案例分享）
- **邮箱**：alenm1208@gmail.com
- **微信**：jgotea
- **GitHub Issues**：https://github.com/saa1028/Ale-Forensic-Suite-Toolkit/issues

---

## ⚠️ 免责声明

1. 本镜像仅面向合法授权的企业安全建设行为，如您需要测试本镜像，请自行搭建环境
2. 在使用本镜像时，您应确保相关行为符合当地的法律法规，且已经取得了足够的授权
3. 如果您在使用本镜像中产生任何非法行为，需自行承担相应后果，作者不承担任何法律连带责任
4. 本镜像所使用的工具资源均来自于互联网整理，如果侵犯了您的知识产权，作者将第一时间删除

---

## ☕ 打赏与捐赠

如果这个项目对您有帮助，欢迎请阿乐喝杯咖啡 ☕

您的支持是我持续更新的动力！感谢每一位支持者 🙏

---

<p align="center">
  <strong>🎉 开箱即用，取证必备，AI 加持 🎉</strong>
</p>

<p align="center">
  Made with ❤️ by Alenm
</p>
