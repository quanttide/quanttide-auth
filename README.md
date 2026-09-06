# quanttide-auth
量潮身份认证

## 概述

量潮身份认证（quanttide-auth）是量潮知识管理体系中的**身份认证与权限管理**领域，涵盖统一身份管理、认证协议、授权模型、权限策略等核心能力。

## 领域边界

- **身份生命周期管理**：用户、组织、角色的创建、同步、注销
- **认证协议与实现**：OAuth 2.0、OIDC、SAML、LDAP 等标准协议
- **授权与权限模型**：RBAC、ABAC、ReBAC 等权限模型
- **安全策略**：多因素认证、会话管理、令牌管理

## 子模块

| 路径 | 说明 |
|------|------|
| `apps/qtcloud-auth` | 量潮身份云 (git submodule → qtcloud-auth) |
| `apps/qtaccount` | 量潮账号中心（前台：账号/钱包管理，复用 qtcloud-auth/qtcloud-pay）(git submodule → qtaccount) |
| `packages/quanttide-auth-toolkit` | 身份认证工具箱 (git submodule → quanttide-auth-toolkit) |
| `examples/default` | 身份认证实验室 (git submodule → quanttide-laboratory-of-authorization-engineering) |
| `data/context` | 身份认证语境 (git submodule → quanttide-context-of-authorization-engineering) |
| `data/journal` | 身份认证日志 (git submodule → quanttide-journal-of-authorization-engineering) |
| `data/profile` | 身份认证档案 (git submodule → quanttide-profile-of-authorization-engineering) |
| `data/intention` | 身份认证意图 (git submodule → quanttide-intention-of-authorization-engineering) |
| `data/roadmap` | 身份认证路线图 (git submodule → quanttide-roadmap-of-authorization-engineering) |
| `data/insight` | 身份认证洞察 (git submodule → quanttide-insight-of-authorization-engineering) |
| `data/brochure` | 身份认证宣传册 (git submodule → quanttide-brochure-of-authorization-engineering) |
| `data/report` | 身份认证报告 (git submodule → quanttide-report-of-authorization-engineering) |
| `data/library` | 身份认证参考 (git submodule → quanttide-library-of-authorization-engineering) |
| `data/history` | 身份认证历史 (git submodule → quanttide-history-of-authorization-engineering) |
| `data/archive` | 身份认证归档 (git submodule → quanttide-archive-of-authorization-engineering) |
| `docs/bylaw` | 身份认证章程 (git submodule → quanttide-bylaw-of-authorization-engineering) |
| `docs/handbook` | 身份认证手册 (git submodule → quanttide-handbook-of-authorization-engineering) |
| `docs/specification` | 身份认证标准 (git submodule → quanttide-specification-of-authorization-engineering) |
| `docs/tutorial` | 身份认证教程 (git submodule → quanttide-tutorial-of-authorization-engineering) |
| `docs/essay` | 身份认证札记 (git submodule → quanttide-essay-of-authorization-engineering) |
| `docs/gallery` | 身份认证案例集 (git submodule → quanttide-gallery-of-authorization-engineering) |

## 许可

[CC BY 4.0](LICENSE)
