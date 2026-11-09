# 盘匣 PanDesk · Windows 发行

本仓库仅用于发布盘匣 Windows 安装包、更新说明、签名清单和校验和，不公开应用源码。源码保存在私有仓库。

- [下载最新正式版](https://github.com/maojian92-crypto/PanDesk-Releases/releases/latest) · [v0.22.67](https://github.com/maojian92-crypto/PanDesk-Releases/releases/tag/v0.22.67)
- 首次安装带更新功能的版本后，可在「设置与数据 → 服务与关于 → 版本更新」检查和下载新版。
- 安装更新需明确确认，等待当前请求和受保护任务结束，完整备份后再安装。v0.22.67 更新保护可原样保留有效的未来定时计划；既有暂停和未知任务不会自动恢复。账号和任务记录保存在本机，不随更新检查上传。
- 更新清单使用 Ed25519 签名，安装包以 SHA256 核对；客户端不内置 GitHub 令牌。
- Windows 安装包目前没有 Authenticode 商业代码签名。清单签名与 Windows 发布者签名是不同机制。

此仓库不接收用户数据库、Cookie、密钥或运行日志。
