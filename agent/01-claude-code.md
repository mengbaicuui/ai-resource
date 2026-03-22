# Claude Code

> AI 编程助手 by Anthropic

---

## 基本信息

| 项目 | 内容 |
|------|------|
| **开发公司** | Anthropic |
| **官网** | claude.ai/claude-code |
| **定位** | CLI 编程助手 |
| **发布时间** | 2024年 |

---

## 底层技术

### 核心技术栈

| 层级 | 技术 |
|------|------|
| **底层模型** | Claude 3.5 Sonnet / Opus |
| **核心协议** | MCP (Model Context Protocol) |
| **工具调用** | 自主 Tool Use 框架 |
| **架构模式** | 单 Agent 循环执行 |

### 技术架构

```
用户指令 → Claude (Haiku/Sonnet/Opus) → Tool Execution → 循环直到完成
                ↓
         MCP Server (扩展工具生态)
```

---

## 核心技术特点

### 1. MCP (Model Context Protocol)

- **开放协议**：Anthropic 主导开发，定义 LLM 如何与外部工具交互
- **Server-Client 架构**：可扩展性强
- **类 JSON-RPC**：专为 AI 场景优化

### 2. Tool Use 框架

- **内置工具**：Search、Bash、Read、Write、Edit、Notebook
- **权限分级**：每次敏感操作需用户确认
- **沙箱执行**：安全的代码执行环境

### 3. 文件操作

- 支持 glob 模式匹配
- 增量编辑（diff-based）
- 多文件协同修改

---

## 优势

✅ 强大的代码理解和生成能力  
✅ 开放的 MCP 生态，方便扩展  
✅ 支持多种 Claude 模型（Haiku 高效 / Sonnet 平衡 / Opus 最强）  
✅ 完善的测试和构建流程自动化  

## 局限

⚠️ 主要面向 CLI，IDE 集成较弱  
⚠️ 需要手动确认每个敏感操作  
⚠️ 上下文窗口受模型限制  

---

## 相关链接

- [官网](https://claude.ai/claude-code)
- [MCP 协议文档](https://modelcontextprotocol.io)
