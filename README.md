# compact-plus-plus (cpp)

A Claude Code skill that protects your context before `/compact` throws away the middle of it.

## English

`/compact` drops the middle of the conversation, and with it the one-off facts you confirmed along the way: how to reach your servers, the current branch and push target, the half-finished task, environments and paths, the gotchas you hit. `cpp` writes those to a file, prints a copy-ready handoff, and gives you a `/compact` command with the focus instruction inlined. If compaction drops the history, a single `Read` of the snapshot brings it back.

The handoff is written for two readers: future you, who needs exact detail to resume, and someone taking over, who has none of your context and must see the current state and next step at a glance.

Install:

```bash
git clone https://github.com/Tigerdwgth/Compact-Plus-Plus.git ~/.claude/skills/cpp
```

Then type `/cpp` in Claude Code, no arguments. Use it when context is getting long before `/compact`, or when you want a handoff to pass to a teammate or a future session.

The skill can't press `/compact` for you — only you can. It gets the info saved and the command ready.

## 中文

`/compact` 会压掉中间历史,顺手丢掉你一路确认的一次性信息:服务器怎么连、当前在哪个分支推去哪、跑到一半的任务、环境和路径、踩过的坑。`cpp` 在压缩前把这些写进文件、打印一份可直接复制的交接文档,再给你一条带好 focus 指令的 `/compact` 命令。压缩丢了历史,`Read` 一下快照就全回来。

交接文档给两种人看:压缩后的你自己(要精确细节续上),和接手的另一个人(没你的上下文,得一眼看懂现在啥状态、下一步干啥)。

安装:

```bash
git clone https://github.com/Tigerdwgth/Compact-Plus-Plus.git ~/.claude/skills/cpp
```

然后在 Claude Code 里敲 `/cpp`,不带参数。上下文长了准备 `/compact` 前用,或想要一份甩给同事、未来自己的交接说明时用。

技能碰不到 `/compact` 那个按钮,真正的压缩得你自己按;它只负责把信息存好、命令备好。

## License

[MIT](./LICENSE)
