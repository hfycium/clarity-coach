# Clarity Coach

一组帮助 Codex 清楚解释问题和撰写文档的 skills：总入口按目标分流到解释或写作 skill。

A small skill suite: the router chooses between clear explanations and document writing, while each specialist contains its own focused instructions.

## Install

Copy the root folder into a Codex skills directory, then copy the two specialist folders alongside it:

```text
~/.codex/skills/clarity-coach/
~/.codex/skills/clarity-explain/
~/.codex/skills/document-writer/
```

Invoke `$clarity-coach` for routing, or invoke `$clarity-explain` and `$document-writer` directly. Codex can also select them automatically from their descriptions.

## What it guides

- `clarity-coach/SKILL.md` — router and shared principles.
- `clarity-explain/SKILL.md` — explanation guidance.
- `document-writer/SKILL.md` — document drafting and revision guidance, including date and author metadata.

## Files

- Each skill folder contains a `SKILL.md` with its trigger description and instructions.

## License

MIT. See [LICENSE](LICENSE).

## 中文说明

将三个文件夹并列复制到 Codex 的 skills 目录即可使用。`clarity-coach` 是总入口；解释和写文档 skill 也可以直接调用。每个 skill 都有自己的触发描述和指引，避免在不相关任务中加载过多细节。
