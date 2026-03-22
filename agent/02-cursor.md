# Cursor

> 最强 AI 代码编辑器 by Anysphere

---

## 基本信息

| 项目 | 内容 |
|------|------|
| **开发公司** | Anysphere |
| **官网** | cursor.com |
| **融资** | Y Combinator 孵化，估值超10亿美元 |
| **用户量** | 超50万开发者，财富500强广泛采用 |

---

## 底层技术

### 核心技术栈

| 层级 | 技术 |
|------|------|
| **底层模型** | OpenAI GPT-4o、Anthropic Claude 3.5、xAI Grok、Google Gemini、Cursor 自研 |
| **架构模式** | Multi-Agent 多智能体系统 |
| **上下文** | Whole Codebase Understanding |
| **扩展协议** | MCP 支持 |

### 技术架构

```
┌─────────────────────────────────────────────┐
│              Cursor IDE                       │
├─────────────────────────────────────────────┤
│  Tab Completion    Cmd+K     Agent Mode       │
│      ↓              ↓           ↓          │
│  单行补全      定向编辑    自主执行任务       │
├─────────────────────────────────────────────┤
│           Multi-Agent Orchestrator           │
│    (协调多个 Agent 并行/串行工作)            │
├─────────────────────────────────────────────┤
│  Model Router (智能路由，选择最佳模型)       │
├─────────────────────────────────────────────┤
│  GPT-4o │ Claude 3.5 │ Gemini │ Grok │ 自研  │
└─────────────────────────────────────────────┘
```

---

## 核心技术特点

### 1. Multi-Agent 架构

- 多个专业 Agent 并行工作
- 代码编写、测试、调试、重构各有分工
- Agent 间可通信协作

### 2. Codebase Intelligence

- 支持任意规模的代码库理解
- 语义索引，快速定位相关代码
- 学习项目模式和编码风格

### 3. Autonomy Slider (自主度滑块)

| 模式 | 自主度 | 说明 |
|------|--------|------|
| Tab | 0% | 仅补全 |
| Cmd+K | 30% | 定向编辑 |
| Agent | 70-100% | 完全自主执行 |

---

## 优势

✅ 首个将多 Agent 集成到 IDE 的产品  
✅ 支持几乎所有顶级 LLM  
✅ 企业级安全，Fortune 500 信任  
✅ 预览模式：自动启动服务器，实时预览效果  

## 局限

⚠️ 付费产品（Pro 订阅）  
⚠️ 部分功能需要 Copilot++ 订阅  

---

## 相关链接

- [官网](https://cursor.com)
- [Self-Driving Codebases Blog](https://cursor.com/blog/self-driving-codebases)
