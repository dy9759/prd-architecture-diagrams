# PRD 架构图集

基于 2026-04-16/17 四份 PRD 的架构可视化，由 `architecture-diagram` skill 生成。

🌐 **Live**: https://dy9759.github.io/prd-architecture-diagrams/

## Diagrams

### 参考模型 · Reference

| # | 图 | 范围 |
|---|---|---|
| 00 | [AI Agent Platform · 7-Layer 参考架构](agent-platform-architecture.html) | 通用 Agent 平台 7 层参考模型 |

### 模块架构 · Per-PRD

| # | 图 | PRD |
|---|---|---|
| 01 | [Project 模块架构](01-project-architecture.html) | Project 重构 PRD |
| 02 | [Account 模块架构](02-account-architecture.html) | Account 重构 PRD |
| 03 | [Cross-cutting 架构](03-cross-cutting-architecture.html) | 跨模块补充 PRD |
| 04 | [Session/Channel 重构](04-session-channel-architecture.html) | Session/Channel 重构 PRD |
| 05 | [整体集成架构](05-overall-architecture.html) | 四 PRD 统一视图 |

## 技术细节

- 纯 HTML + 内联 SVG，无外部依赖
- 深色主题 (`#020617` 背景)
- JetBrains Mono 字体
- 语义颜色：青=前端/身份 · 绿=服务/执行 · 紫=数据/产物 · 玫红=安全/身份 · 黄=云/执行 · 橙=事件/通知
