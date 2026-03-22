# Haystack

> 开源 RAG 框架 by deepset

---

## 基本信息

| 项目 | 内容 |
|------|------|
| **公司** | deepset |
| **官网** | deepset.ai/haystack |
| **GitHub** | github.com/deepset-ai/haystack |
| **Star** | 25,000+ |
| **类型** | 开源框架 |

---

## 核心定位

Haystack 是由 **deepset** 开发的开源**端到端 RAG 框架**，用于构建复杂的问答系统和知识库应用。

---

## 核心功能

### 1. RAG Pipeline 构建

- 模块化组件设计
- 灵活组合 Retriever + Reader/Generator
- 支持自定义 Pipeline

### 2. 多种检索器

| 检索器 | 说明 |
|--------|------|
| **Dense Passage Retrieval** | 密集段落检索 |
| **BM25** | 关键词检索 |
| **Embedding** | 向量检索 |
| **Hybrid** | 混合检索 |

### 3. Reader/Generator

- **FARM**: 基于 BERT 的阅读理解
- **Transformers**: Hugging Face 模型集成
- **GPT/Claude**: 大模型生成

### 4. 数据源集成

- **Document Store**: FAISS, Milvus, Weaviate, Pinecone
- **File Formats**: PDF, TXT, DOCX, Markdown
- **APIs**: Slack, Confluence, Notion

---

## 技术架构

```
┌─────────────────────────────────────────────────┐
│              Haystack Pipeline                     │
├─────────────────────────────────────────────────┤
│  Preprocessing → Retrieval → Reader → Output      │
│       ↓           ↓          ↓                   │
│   File Loader   Retriever   LLM Generator        │
│   Markdown     BM25        Reader                │
│   PDF          DPR         Transformers          │
└─────────────────────────────────────────────────┘
```

---

## 优势

✅ **完全开源**：社区活跃，持续迭代  
✅ **高度模块化**：组件可自由替换  
✅ **丰富集成**：多种向量库和数据源  
✅ **生产就绪**：支持大规模部署  
✅ **专业团队**：deepset 提供企业支持  

---

## 局限

⚠️ 需要技术能力搭建和维护  
⚠️ 无原生可视化界面  
⚠️ 组件版本兼容性需注意  

---

## 相关链接

- [官网](https://deepset.ai/haystack)
- [GitHub](https://github.com/deepset-ai/haystack)
- [文档](https://docs.haystack.deepset.ai)
