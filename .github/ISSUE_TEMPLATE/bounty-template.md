---
name: 💰 Bounty Task
about: 认领此赏金任务
title: '[BOUNTY $AMOUNT] Task Name'
labels: bounty
assignees: ''
---

## 赏金金额

**$X USDT**

## 任务描述

[描述任务内容]

## 服务清单

| 服务 | 镜像 | 用途 |
|------|------|------|
| ... | ... | ... |

## 文件结构

```
stacks/xxx/
├── docker-compose.yml
├── .env.example
└── README.md
```

## 要求

1. **环境变量** — 通过 `.env` 管理，无硬编码
2. **Traefik 配置** — 子域名 + HTTPS
3. **健康检查** — 每个容器有 `healthcheck`
4. **SSO 集成** — 支持 Authentik (如适用)
5. **README 文档** — 启动步骤、配置说明、FAQ

## 验收标准

- [ ] 所有服务正常启动
- [ ] 健康检查通过
- [ ] Traefik 反代生效
- [ ] README 完整
- [ ] 无硬编码密码

## 认领方式

评论 "我来认领"。
