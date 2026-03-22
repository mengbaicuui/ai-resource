# Kiro

> Agentic AI 开发环境 by AWS

---

## 基本信息

| 项目 | 内容 |
|------|------|
| **开发公司** | AWS (Amazon Web Services) 内置团队 |
| **官网** | kiro.dev |
| **产品定位** | Agentic Development Environment |
| **名称由来** | Kiro（日语"城"的意思），发音与"hero"押韵 |

---

## 核心定位

> *"What would a development environment look like if it could take full advantage of AI?"*

Kiro 是一个**Agentic 开发环境**，让开发者能够在 AI 代理的帮助下完成真正的工程工作。

---

## 底层技术

### 核心技术栈

| 层级 | 技术 |
|------|------|
| **底层模型** | Claude Sonnet 4.5 / Auto (多模型混合) |
| **交互形式** | 终端 (Terminal-first) |
| **协议** | MCP (Model Context Protocol) 原生支持 |
| **架构模式** | Spec-Driven Development + Agent Hooks |

### 技术架构

```
用户指令 / Spec
       ↓
┌─────────────────────────────────────────────┐
│           Kiro Agentic Engine                │
├─────────────────────────────────────────────┤
│  Spec 驱动开发 │ Steering │ Agent Hooks       │
│  自动驾驶模式 │ 上下文管理 │ MCP 集成        │
├─────────────────────────────────────────────┤
│        Claude Sonnet 4.5 / Auto             │
└─────────────────────────────────────────────┘
```

---

## 核心技术特点

### 1. Spec-Driven Development (规范驱动开发)

- 将自然语言 prompt 转换为结构化需求
- 设计文档和任务分解
- Agent 执行实现

### 2. Advanced Steering

- **Steering Files**：配置文件定义 Agent 与项目的交互方式
- 添加上下文、编码标准、偏好工作流
- 简单命令即可配置

### 3. Agent Hooks (代理钩子)

- 文件保存等事件触发 Agent 执行
- 后台自主执行任务
- 应用场景：
  - 自动生成文档
  - 自动生成单元测试
  - 代码性能优化

### 4. Autopilot Mode (自动驾驶模式)

- Agent 自主执行大型任务
- 无需逐步指令
- 保持人类控制（尤其在运行脚本或命令时）

### 5. MCP 原生集成

- 连接文档、数据库、API 等
- 支持远程 MCP
- 标准化协议

### 6. 模型选择

| 模式 | 说明 |
|------|------|
| **Claude Sonnet 4.5** | 可靠的先进编码和推理能力 |
| **Auto** | 智能混合多个前沿模型，优化质量/延迟/成本 |

---

## 核心功能

### 开发流程全覆盖

- **对话 → 代码 → 部署**：终端直接完成
- **SSH 支持**：远程开发
- **多模型路由**：质量/速度/成本平衡

### 智能辅助

| 功能 | 说明 |
|------|------|
| **错误诊断** | 读取和解析语法、类型、语义错误 |
| **代码 Diff** | 实时查看代码变更，逐个审批 |
| **图片理解** | 拖入 UI 设计图或架构草图，引导实现 |
| **Commit 消息** | AI 生成 Git 提交信息 |
| **上下文管理** | 智能上下文管理，理解 prompt 意图 |

---

## 安装与使用

```bash
# 安装 (macOS / Linux)
curl -fsSL https://cli.kiro.dev/install | bash
```

---

## 定价

| 计划 | 价格 | 额度 |
|------|------|------|
| **Free** | $0 | 50 credits/月 |
| **Pro** | $20/月 | 1,000 credits + 按量超额 |
| **Pro+** | $40/月 | 2,000 credits + 按量超额 |
| **Power** | $200/月 | 10,000 credits + 按量超额 |
| **Enterprise** | 定制 | 团队计费、SSO、SAML/SCIM |

---

## 优势

✅ **AWS 内置团队**：可靠的技术背书  
✅ **Spec 驱动开发**：结构化 AI 协作范式  
✅ **终端优先**：开发者友好的工作流  
✅ **Agent Hooks**：事件驱动的自动化  
✅ **Auto 模型路由**：质量/成本/延迟平衡  
✅ **MCP 原生支持**：生态扩展性强  

---

## 局限

⚠️ 相对较新，社区和生态还在成长  
⚠️ 主要面向 CLI，GUI 相对弱  
⚠️ 定价按 credits 计费，长期使用成本需关注  

---

## 相关链接

- [官网](https://kiro.dev)
- [GitHub](https://github.com/kirodotdev/Kiro)
- [文档](https://kiro.dev/docs/)
- [Discord](https://discord.gg/kirodotdev)
- [Twitter](https://x.com/kirodotdev)
