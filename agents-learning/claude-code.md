# 资源

- https://www.aitmpl.com/：claude-code相关的skills，plugins，Commands，Settings，Hooks等相关的资源





# skills推荐

- Frontend Design
- Code Reviewer





# 插件推荐

## Context Monitor

> Real-time Claude Code context usage monitor with visual progress bars, color-coded alerts, session analytics (cost, duration, lines changed), and auto-compact warnings. Tracks conversation context consumption and provides visual feedback to prevent session interruptions.

1. **安装**

```
npx claude-code-templates@latest --setting statusline/context-monitor
```

2. **编辑 settings.json 添加配置**

```Bash
nano ~/.claude/settings.json
```

3. **在文件最外层的 { ... } 中添加以下内容（如果文件是空的，就直接写下面这个）：**

```Bash
{
  "statusLine": {
    "type": "command",
    "command": "python3 ~/.claude/plugins/.claude/scripts/context-monitor.py"
  }
}
```



