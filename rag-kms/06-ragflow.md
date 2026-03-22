# RAGFlow

> 领先的开源 RAG 引擎 by InfiniFlow

---

## 基本信息

| 项目 | 内容 |
|------|------|
| **开发公司** | InfiniFlow |
| **官网** | ragflow.io |
| **GitHub** | github.com/infiniflow/ragflow |
| **Star** | 开源流行 RAG 引擎 |
| **类型** | 开源 + 云服务 |
| **最新版本** | v0.24.0 |

---

## 核心定位

> *"RAGFlow is a leading open-source Retrieval-Augmented Generation (RAG) engine that fuses cutting-edge RAG with Agent capabilities to create a superior context layer for LLMs."*

RAGFlow 是将**前沿 RAG 技术与 Agent 能力融合**的开源 RAG 引擎，为 LLMs 提供卓越的上下文层。

---

## 底层技术

### 核心技术栈

| 层级 | 技术 |
|------|------|
| **文档理解** | Deep Document Understanding (深度文档理解) |
| **检索策略** | Vector Search + BM25 + 混合检索 + Re-ranking |
| **Agent** | Multi-Agent 编排 + MCP 支持 |
| **部署** | Docker 一键部署 |

### 技术架构

```
┌─────────────────────────────────────────────────────────────┐
│                     RAGFlow 系统架构                            │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  【数据摄入层 (Ingestion)】                                   │
│  ┌─────────┐  ┌──────────┐  ┌────────────┐                │
│  │ PDF/   │  │ DeepDoc  │  │ Chunking  │                │
│  │ Word/  │→ │ 深度解析  │→ │ 可视化分块  │                │
│  │ Excel  │  │          │  │            │                │
│  └─────────┘  └──────────┘  └────────────┘                │
│                                                              │
│  【检索层 (Retrieval)】                                      │
│  ┌─────────┐  ┌──────────┐  ┌────────────┐                │
│  │ BM25   │  │ Vector   │  │ Re-rank   │                │
│  │ 关键词  │+ │ Search  │+ │ 融合重排   │                │
│  └─────────┘  └──────────┘  └────────────┘                │
│                                                              │
│  【Agent 层】                                               │
│  ┌─────────┐  ┌──────────┐  ┌────────────┐                │
│  │ RAG    │  │ Tools   │  │ MCP       │                │
│  │ Agent  │  │ 调用     │  │ 集成       │                │
│  └─────────┘  └──────────┘  └────────────┘                │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

---

## 核心功能

### 1. 深度文档理解 (Deep Document Understanding)

- 从复杂格式的非结构化数据中提取知识
- 支持：**Word、PPT、Excel、TXT、图片、扫描件、结构化数据、网页**等
- 多模态模型理解 PDF/DOCX 中的图片

### 2. 高级检索能力

| 策略 | 说明 |
|------|------|
| **Vector Search** | 语义向量检索 |
| **BM25** | 关键词检索 |
| **混合检索** | 向量 + BM25 融合 |
| **Re-ranking** | 融合重排序提升精度 |

### 3. 可视化分块 (Visual Chunking)

- 分块过程可视化
- 支持人工干预调整
- 智能分块策略

### 4. Agent 工作流

- 预置 Agent 模板
- 可视化工作流编排
- RAG + Tools + MCP 一体化

### 5. 数据源集成

| 数据源 | 说明 |
|--------|------|
| **Confluence** | 企业知识库同步 |
| **S3** | AWS S3 文件同步 |
| **Notion** | Notion 页面同步 |
| **Discord** | 社区数据集成 |
| **Google Drive** | 云盘文件同步 |

---

## 核心亮点

### "数据海洋中的针" - 无限 Token 检索

```
海量文档 → 精准定位 → 可靠上下文
```

- 支持**无限 Token** 的精确检索
- explainable（可解释的检索过程）
- traceable citations（可追溯的引用）

### 预置 Agent 模板

| 模板 | 场景 |
|------|------|
| **金融分析** | 股票分析、投资报告 |
| **法律案例** | 相似案例检索 |
| **设备维护** | 维护指南生成 |
| **通用 RAG** | 通用问答 |

---

## 安装与部署

### 系统要求

| 要求 | 规格 |
|------|------|
| **CPU** | >= 4 cores |
| **RAM** | >= 16 GB |
| **Disk** | >= 50 GB |
| **Docker** | >= 24.0.0 |
| **Docker Compose** | >= v2.26.1 |

### 快速启动

```bash
# 克隆仓库
git clone https://github.com/infiniflow/ragflow.git
cd ragflow/docker

# 启动服务 (CPU 版本)
docker compose -f docker-compose.yml up -d

# 检查状态
docker logs -f docker-ragflow-cpu-1

# 访问
# 浏览器打开 http://IP_OF_YOUR_MACHINE
```

### GPU 加速

```bash
cd ragflow/docker
sed -i '1i DEVICE=gpu' .env
docker compose -f docker-compose.yml up -d
```

---

## 最新更新 (2025)

| 日期 | 功能 |
|------|------|
| 2025-12 | Agent Memory 支持 |
| 2025-11 | Gemini 3 Pro 支持、Confluence/S3/Notion/Discord/Google Drive 同步 |
| 2025-10 | MinerU & Docling 文档解析方法 |
| 2025-08 | GPT-5 系列模型支持、Agentic Workflow + MCP |
| 2025-05 | Python/JS 代码执行器 |
| 2025-03 | 多模态模型理解 PDF/DOCX 中的图片 |

---

## 优势

✅ **开源免费**：GitHub 开源，持续迭代  
✅ **深度文档理解**：复杂格式精准提取  
✅ **无限上下文**：处理海量文档无压力  
✅ **混合检索**：Vector + BM25 + Re-ranking  
✅ **可视化分块**：人工干预可控  
✅ **Agent 原生**：RAG + Agent 一体化  
✅ **MCP 支持**：生态扩展性强  
✅ **一键部署**：Docker 简化运维  

---

## 局限

⚠️ 需要 16GB+ RAM，硬件要求较高  
⚠️ ARM64 平台需要自行构建镜像  
⚠️ 主要面向技术团队，UI 相对基础  

---

## 相关链接

- [官网](https://ragflow.io)
- [GitHub](https://github.com/infiniflow/ragflow)
- [在线演示](https://cloud.ragflow.io)
- [文档](https://ragflow.io/docs)
- [Docker Hub](https://hub.docker.com/r/infiniflow/ragflow)
