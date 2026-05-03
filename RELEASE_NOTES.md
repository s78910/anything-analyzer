# Anything Analyzer v3.6.6

## 新功能

- **手机证书下载页面** — MITM 代理新增内置证书下载页面，手机配置代理后浏览器访问 `http://cert.anything.local` 即可下载并安装 CA 证书，类似 mitmproxy 的 `mitm.it` 机制
  - 自动识别 iOS / Android / 桌面端，显示对应安装步骤
  - 支持 `.crt` / `.pem` / `.cer` 格式下载
- **设置面板代理提示优化** — MITM 代理设置中显示手机证书安装地址，代理地址提示改为 `<本机IP>` 更便于外部设备连接

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.6.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.6-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.6-x64.dmg |
| Linux | Anything-Analyzer-3.6.6.AppImage |
