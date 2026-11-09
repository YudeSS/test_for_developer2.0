# test_for_developer2.0

软件工厂 2.0「伴随式 Agent」的联调测试仓库。

本仓库用于本地部署的 [dsh-superagent](https://github.com/deepseek-ai/dsh-superagent-prototype) 冒烟测试：飞书群或 GitHub 中 @ agent 账号提出请求后，superagent 会创建工单，在 `agent/` 前缀的分支上完成改动并提交 Pull Request，由人工评审、合并。

## 约定

- 默认分支 `main` 只接受经人工评审的合并，agent 不直接推送 `main`。
- agent 的分支统一以 `agent/` 开头。
- 本仓库内容仅用于测试，可随时清理。

## 快速开始

这是一个测试仓库，仅用于软件工厂 2.0 伴随式 Agent 的联调与冒烟测试。
