# Clarity Coach

一个帮助 Codex 把复杂内容讲清楚的 skill：先回答问题，再按用户需要补充推理、背景或操作步骤。

A Codex skill for explaining complex topics clearly. It answers first, then adds reasoning, context, or action steps at the depth the user asks for.

## Install

Copy this folder into a Codex skills directory, for example:

```text
~/.codex/skills/clarity-coach/
```

Then invoke it with `$clarity-coach`, or let Codex select it automatically when relevant.

## What it guides

- Match explanation depth to the user's request.
- Find and explain missing prerequisites when the user is confused.
- Choose prose, steps, tables, diagrams, or charts based on the information.
- Preserve assumptions, caveats, and uncertainty while keeping the explanation concise.
- Give a complete procedure when requested instead of forcing unnecessary turns.

## Files

- `SKILL.md` — skill instructions and automatic-selection description.

## License

MIT. See [LICENSE](LICENSE).

## 中文说明

将 `clarity-coach` 文件夹复制到 Codex 的 skills 目录即可使用。`SKILL.md` 包含触发描述和行为指引；简单问题直接回答，复杂问题按需解释，用户要求完整步骤时提供完整步骤。
