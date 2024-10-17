# Vaultwarden

用 Rust 编写的 Bitwarden 服务器 API 的替代实现，占用极低，与Bitwarden 客户端兼容，非常适合运行官方资源密集型服务的自托管部署。

**该项目与 Bitwarden 项目或 Bitwarden，Inc. 无关。**

## 注意

第一次部署请务必保证用户注册和邀请注册功能正常开启，否则无法新建管理员账号！

后续可以按需要关闭注册和邀请功能（在应用的参数设置里进行设置）

## 特征

基本上提供了 Bitwarden API 的完整实现，包括：

- 组织支持
- 附件和发送
- Vault API 支持
- 为 Vault 接口提供静态文件
- 网站图标 API
- Authenticator 和 U2F 支持
- YubiKey 和 Duo 支持
- 紧急访问

## 速评

相比于Bitwarden，它的占用很低，而且完全兼容Bitwarden的相关API，很适合个人部署使用。

如果你的服务器配置不是很高，又想拥有一个强大的密码管理器，那么Vaultwarden就是你的心头好！