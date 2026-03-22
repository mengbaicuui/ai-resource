# AI Coding Agent 调研报告

> 热门 AI 编程工具深度分析 | 持续更新中

---

## 📚 目录

| 编号 | Agent | 公司 | 核心亮点 |
|:----:|-------|------|----------|
| 01 | [Claude Code](./01-claude-code.md) | Anthropic | MCP 协议、Tool Use |
| 02 | [Cursor](./02-cursor.md) | Anysphere | Multi-Agent、Autonomy Slider |
| 03 | [Windsurf](./03-windsurf.md) | Codeium | Memories 记忆系统 |
| 04 | [GitHub Copilot](./04-github-copilot.md) | Microsoft | GitHub 生态集成 |
| 05 | [Devin](./05-devin.md) | Cognition Labs | 端到端自主工程师 |
| 06 | [Replit Agent](./06-replit-agent.md) | Replit | 云端 IDE、一键部署 |
| 07 | [Aider](./07-aider.md) | 开源 | CLI 工具、Git 原生 |
| 08 | [JetBrains AI](./08-jetbrains-ai.md) | JetBrains | IDE 深度集成 |
| 09 | [OpenCode](./09-opencode.md) | Anomaly | 开源、多形态、隐私优先 |
| 10 | [Kiro](./10-kiro.md) | AWS | Spec驱动开发、Agent Hooks、终端优先 |

---

## 🔮 技术趋势总结

### 核心技术趋势

1. **Multi-Agent 系统成为主流**
   - 多个专业 Agent 并行/串行协作
   - 规划、编码、测试、审查分工明确

2. **MCP 协议统一工具生态**
   - Anthropic 主导的开放协议
   - 类似 USB 接口，工具即插即用

3. **自主度连续光谱**

   | 自主度 | 模式 | 适用场景 |
   |:------:|------|----------|
   | 0% | Tab 补全 | 新手、精确控制 |
   | 30% | Cmd+K 定向编辑 | 日常开发 |
   | 70% | 半自动 Agent | 复杂任务 |
   | 100% | 全自主 Agent | 端到端项目 |

4. **上下文能力持续增强**
   - 代码库全量理解
   - 跨会话记忆
   - 长期任务维持

5. **安全与权限分级**
   - 操作权限分级确认
   - 敏感操作需人工授权

### 2025 年预测

| 趋势 | 说明 |
|------|------|
| **Agent 自主化** | 从"助手"进化到"代理" |
| **多模态融合** | 代码、UI 设计、文档统一理解 |
| **专业垂直化** | 行业专属 Coding Agent |
| **实时协作** | AI 与人类平等协作编程 |
| **标准化协议** | MCP 有望成为行业标准 |

---

## 🔧 关键技术栈一览

```
┌─────────────────────────────────────────────────┐
│                  应用层                          │
│   Claude Code │ Cursor │ Windsurf │ Copilot ...  │
├─────────────────────────────────────────────────┤
│                 Agent 框架层                     │
│   规划 │ 推理 │ 工具调用 │ 记忆 │ 协作          │
├─────────────────────────────────────────────────┤
│                  模型层                          │
│   GPT-4o │ Claude 3.5 │ Gemini │ Grok │ 自研    │
├─────────────────────────────────────────────────┤
│                 协议层                           │
│   MCP (Model Context Protocol) │ Tool Use       │
├─────────────────────────────────────────────────┤
│                  工具层                          │
│   文件操作 │ Shell │ 搜索 │ API │ 数据库        │
└─────────────────────────────────────────────────┘
```

---

## 📊 对比总表

| Agent | 架构 | 协议 | 免费 | IDE集成 | 自主度 |
|-------|------|------|:----:|---------|:------:|
| Claude Code | 单 Agent | MCP | ✅ | CLI | 中 |
| Cursor | Multi-Agent | MCP | ❌ | ✅ | 高 |
| Windsurf | 单 Agent+记忆 | MCP | ✅ | ✅ | 中 |
| GitHub Copilot | Multi-Agent | 专用 | ❌ | ✅ | 中 |
| Devin | 自主 Agent | 专用 | ❌ | ❌ | 极高 |
| Replit Agent | 云端 Agent | 专用 | ✅ | 云端 | 高 |
| Aider | 单 Agent | 多模型 | ✅ | CLI | 低 |
| JetBrains AI | IDE Agent | 专用 | ❌ | ✅ | 低 |

---

*最后更新：2026-03-22*
