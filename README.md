# clash-rules

公开规则名单（仅域名，零秘密），供个人 Clash / Mihomo 配置以 rule-providers / RULE-SET 方式拉取。
主配置在私有仓库 clash-config，本仓库不需要任何令牌即可读取。

同一名单有两种格式，内容一致、改名单时同步改两份：.yaml 给 Mihomo，.list 给 Shadowrocket。

- rules/ai-domains.yaml / .list — AI 服务域名（走 ai 组）
- rules/media-v4.yaml / .list — 强制走 v4 的域名
- rules/strict-surface.yaml — 严格风控敏感面清单（休眠，未被引用）
