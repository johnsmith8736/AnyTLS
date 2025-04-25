# AnyTLS Proxy Server

一个基于 AnyTLS 的高性能代理服务器配置。

## 项目说明

本项目提供了 AnyTLS 代理服务器的完整配置方案，包括服务器端和客户端（Linux/Android）的配置文件。

## 配置说明

### 服务器配置 (server-config-anytls-1.12.0.json)

- 监听端口：443
- 使用 TLS 1.2/1.3
- 支持 Reality 协议
- 内置 DNS 配置（阿里 DNS 和 Cloudflare）
- 智能路由规则（支持中国直连和广告拦截）

### 客户端配置

- Linux 客户端配置 (client-config-anytls-1.12.0(Linux).json)
- Android 客户端配置 (client-config-anytls-1.12.0(Android).json)

## 使用方法

1. 服务器部署：
   - 将 `server-config-anytls-1.12.0.json` 配置部署到服务器
   - 确保 443 端口可访问
   - 配置域名和证书

2. 客户端使用：
   - Linux 用户使用 `client-config-anytls-1.12.0(Linux).json`
   - Android 用户使用 `client-config-anytls-1.12.0(Android).json`

## 安全说明

- 请及时修改配置文件中的密码和密钥
- 建议定期更新配置文件和规则集
- 使用强密码和安全的密钥

## 许可证

MIT License 