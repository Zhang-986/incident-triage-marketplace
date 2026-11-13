# Incident Triage

Codex 告警排查插件，关联 OpenObserve 日志、Git 代码、阿里云慢日志和 DMS 元数据，按证据给出归因和置信度。

## 安装

运行 `codex plugin marketplace add https://github.com/Zhang-986/incident-triage-marketplace.git`。在 Codex 插件目录选择 **Incident Triage Tools**，安装 **incident-triage**。

第一次使用时，在 Codex 发送下面这句话。

> 用 incident-triage 帮我完成首次配置。检查本机工具，带我登录，再用一条我能访问的告警验证。

完成配置后直接贴告警链接，或者贴环境、服务、发生时间和 trace ID。各数据源使用自己的账号和权限。
