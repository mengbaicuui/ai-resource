# RAG 知识管理平台调研报告

> RAG (Retrieval-Augmented Generation) 知识管理平台整理 | 持续更新中

---

## 📚 目录

| 编号 | 平台 | 公司 | 核心亮点 |
|:----:|-------|------|----------|
| 01 | [Glean](./01-glean.md) | Glean | 企业级 AI 搜索 |
| 02 | [Dify](./02-dify.md) | LangGenius | 开源 Agentic Workflow（含 RAG） |
| 03 | [LlamaIndex](./03-llamaindex.md) | LlamaIndex | RAG 与 Agent 框架 |
| 04 | [Haystack](./04-haystack.md) | deepset | 开源 RAG 框架 |
| 05 | [Notion AI](./05-notion-ai.md) | Notion | 知识库 AI Q&A |

---

## 🔮 RAG 知识管理平台核心概念

### 什么是 RAG？

```
检索增强生成 (Retrieval-Augmented Generation)

用户查询 → 检索 → 增强 → 生成
              ↓
         私有知识库
```

**RAG** 将检索系统与生成模型结合：
1. 从私有知识库中检索相关信息
2. 将检索结果作为上下文注入 prompt
3. LLM 基于增强后的 context 生成答案

### 核心组件

| 组件 | 说明 |
|------|------|
| **Embedding** | 将文本向量化 |
| **Vector DB** | 向量数据库存储和检索 |
| **Retriever** | 检索算法（语义/关键词/混合） |
| **Ranker** | 结果重排序 |
| **Generator** | LLM 生成答案 |

### 企业级 KMS 核心需求

| 需求 | 说明 |
|------|------|
| **数据安全** | 私有数据全程不外泄 |
| **权限控制** | 基于角色的访问控制 |
| **多数据源** | 支持文档、数据库、API 等 |
| **可观测性** | 检索质量监控 |
| **评估工具** | RAG pipeline 性能评估 |

---

## 📊 平台对比

| 平台 | 类型 | RAG 原生 | 向量数据库 | 可视化 | 企业级 |
|-------|------|:---------:|:----------:|:------:|:------:|
| Glean | SaaS | ✅ | 托管 | ✅ | ✅ |
| Dify | 开源+SaaS | ✅ | 多选 | ✅ | ✅ |
| LlamaIndex | 开源 | ✅ | 多选 | ❌ | ✅ |
| Haystack | 开源 | ✅ | 多选 | ❌ | ❌ |
| Notion AI | SaaS | ✅ | 托管 | ✅ | ✅ |

---

*最后更新：2026-03-22*
