# -agent-
项目基于 `learn-claude-code` 的 Agent 工程思路改造，用 Python + Aliyun DashScope/Qwen 实现一个只读 PR Review Agent：读取 Git diff 和 PR 描述，组织多个 reviewer 生成候选问题，再通过 debate loop 对 finding 进行质疑、补证、反驳、合并和裁决，最后输出标准化报告，并可用 AI Judge 做质量评估。
