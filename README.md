# PellaFree 自动续期

| Secret | 必填 | 说明 |
|---|---|---|
| `EMAIL` | ✅ | Pella 登录邮箱 |
| `PASSWORD` | ✅（无 COOKIE_VALUE 时） | Pella 登录密码 |
| `COOKIE_VALUE` | ❌（一般不用配） | `__session` 值，优先直用，401 自动回退账密 |
| `TG_BOT_TOKEN` | ❌ | Telegram Bot Token（通知） |
| `TG_CHAT_ID` | ❌ | Telegram Chat ID（通知） |
| `NODE_LINK` | ❌ | 代理节点分享链接，不配即直连 |
