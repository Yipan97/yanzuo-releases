# yanzuo-releases
# 研作 Windows 发布频道
这个仓库用于分发研作 Windows 安装包、离线更新包和经过签名的应用更新。

## 安装
从 [发布附件](https://github.com/Yipan97/yanzuo-releases/releases/tag/updates) 下载 `Yanzuo-Setup-x64.exe` 并安装。当前稳定版为 **0.4.1**。

## 配置在线更新
在应用的「帮助 → 关于与更新」中填写以下目录地址并检查更新：

```text
https://github.com/Yipan97/yanzuo-releases/releases/download/updates/
```

客户端验证发布签名与包内容后，才允许更新。下载后由用户选择重启安装。

## 离线更新
下载 `Yanzuo-Offline-Updates-x64.zip`，完整解压后在同一窗口选择解压目录。当前离线包支持从 0.3.2 更新到 0.4.1，并保留旧版恢复包。

## 发布维护
固定使用 `updates` 标签。后续先上传新包，再更新签名清单；清单引用的旧版恢复包继续保留。此频道需要允许维护附件。仓库只接收审核过的发布文件，不接收用户工作区、API 凭据或发布签名私钥。
