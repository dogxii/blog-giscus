## blog-giscus

这是 [blog.dogxi.me](https://blog.dogxi.me) 的评论仓库，见 [Discussions](./discussions)。

## Action 通知

配置了 Github Action 用于实现消息推送（email + ntfy）。

所需 Github Secrets：

- MAIL_SERVER：SMTP 服务器地址（例：smtp.gmail.com 或你的邮局服务器）
- MAIL_PORT：SMTP 端口（常见 465 或 587，与 secure/tls 设置匹配）
- MAIL_USERNAME：发信邮箱账号
- MAIL_PASSWORD：发信邮箱密码或应用专用密码
- MAIL_FROM：发件人邮箱（用于邮件 From 字段）
- MAIL_TO：收件人邮箱（可逗号分隔多个）

可选（ntfy）

- NTFY_URL：ntfy 服务器地址（例：https://ntfy.sh 或你的自建服务）
- NTFY_TOPIC：推送主题名称（你订阅的 topic）
- NTFY_TOKEN：ntfy 认证令牌（如果你的 ntfy 需要鉴权）
