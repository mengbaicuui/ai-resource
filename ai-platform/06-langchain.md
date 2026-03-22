# LangChain

> LLM 应用开发框架

---

## 基本信息

| 项目 | 内容 |
|------|------|
| **开发公司** | LangChain |
| **官网** | langchain.com |
| **GitHub** | github.com/langchain-ai/langchain |
| **Star** | 90,000+ |
| **定位** | LLM 应用开发框架 |
| **类型** | 开源 + 企业版 |

---

## 核心定位

LangChain 是一个用于**开发 LLM 应用的开源框架**，提供构建基于大语言模型应用的必要工具和组件。

---

## 核心功能

### 1. 模块化组件

| 组件 | 说明 |
|------|------|
| **Models** | 多模型支持 |
| **Prompts** | 提示词管理和优化 |
| **Indexes** | 文档加载、分割、检索 |
| **Memory** | 对话历史管理 |
| **Chains** | 链式调用编排 |
| **Agents** | Agent 策略执行 |

### 2. Agent 框架

- 基于 LLM 的自主决策 Agent
- 多种 Agent 类型支持
- 工具调用和执行

### 3. RAG 支持

- 文档加载和处理
- 多种向量存储支持
- 检索和生成管道

### 4. 企业版 LangSmith

- 应用追踪和调试
- 评估和监控
- Prompt 版本管理

---

## 技术架构

```
┌─────────────────────────────────────────────────┐
│              LangChain 应用                       │
├─────────────────────────────────────────────────┤
│  Prompts │ Models │ Agents │ Chains │ Memory     │
├─────────────────────────────────────────────────┤
│              LangSmith (企业版)                    │
│         追踪 │ 评估 │ 监控                        │
└─────────────────────────────────────────────────┘
```

---

## 版本体系

| 版本 | 说明 |
|------|------|
| **LangChain** | 核心开源框架 |
| **LangChain.js** | JavaScript/TypeScript 版本 |
| **LangSmith** | 企业级观测和评估平台 |
| **LangServe** | 部署 LLM 应用为 API |

---

## 优势

✅ **生态丰富**：GitHub 9万星，活跃社区  
✅ **模块化设计**：高度可复用组件  
✅ **多语言支持**：Python 和 JavaScript  
✅ **企业级工具**：LangSmith 提供生产级观测  

---

## 局限

⚠️ 学习曲线较陡  
⚠️ 快速迭代导致 API 变化频繁  
⚠️ 生产部署需要额外配置  

---

## 相关链接

- [官网](https://langchain.com)
- [GitHub](https://github.com/langchain-ai/langchain)
- [文档](https://python.langchain.com)
