---
activation_count: 3.2
arousal: 0.3
created: '2026-07-11T17:23:16'
domain:
- 编程
- 工作
id: 7c4f27aa26b6
importance: 8
last_active: '2026-07-12T12:08:57'
name: Tidal Echo 路由修正
tags:
- Tidal Echo
- 项目技术档案
- 前端
- 后端
- Zeabur
- 路由修正
- /relay
- 部署
- 环境变量
- API
- 代码审查
- 待办
- 技术文档
- 项目维护
- Bug修复
- 编程
- 路由修复
type: dynamic
valence: 0.4
---

Tidal Echo 项目技术档案（2026-06-19更新）：
- 前端地址：https://tidal-echo-web.zeabur.app
- 后端地址：https://tidal-echo-backend.zeabur.app
- 部署平台：Zeabur
- 后端真实路由：/channel/out、/channel/in、/app/send、/app/stream、/app/history（无/relay路由）
- 当前问题：前端有4处/relay路径未全部修正，只改了第2238行，其他三处未改
- 环境变量：ANTHROPIC_BASE_URL=https://api2.68886868.xyz，ANTHROPIC_API_KEY已填
- 连接密钥SECRET_KEY=tidal-echo-secret-2026
- 待办：让另一个AI看完整前端代码，找出所有/relay并统一改为正确路由