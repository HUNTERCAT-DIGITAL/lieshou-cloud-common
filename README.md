# ⚠️ 已归档（Archived）

> **本仓库已停止维护。** 代码已迁移至 **lieshou-framework**（猎手云核心框架，上游同源唯一）。

| 本仓 | 迁移目标 |
| --- | --- |
| `cn.huntercat.lieshoucloudpro.common.*` | `cn.huntercat.lieshou.framework.common.*`（framework-common 模块） |
| `cn.huntercat.lieshoucloudpro.jwt.*` | `cn.huntercat.lieshou.framework.jwt.*`（framework-jwt 模块） |

## 迁移说明

- **新仓库**：[HUNTERCAT-DIGITAL/lieshou-framework](https://github.com/HUNTERCAT-DIGITAL/lieshou-framework)
- **消费方**：lieshou-boot（单体）、lieshou-cloud 系服务（auth/user/admin/approval/gateway）已全部切换依赖 framework
- **维护**：业务/通用能力改动一律到 lieshou-framework 进行，本仓只读不再更新

## 历史

本仓曾作为 lieshou-cloud-pro 后端统一异常 / JWT / 审计 / 权限注解的共享库（2026-08 core 细拆分产物）。
2026-09 随「LieShou Framework 产品线」战略升级并入 lieshou-framework，实现三套产品线（Boot/Cloud/Pro）上游同源唯一。
