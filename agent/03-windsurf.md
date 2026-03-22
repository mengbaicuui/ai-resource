# Windsurf

> AI 编程体验 by Codeium

---

## 基本信息

| 项目 | 内容 |
|------|------|
| **开发公司** | Codeium |
| **官网** | windsurf.com |
| **产品名** | Cascade (AI 引擎) |
| **用户量** | 100万+ 用户，4000+ 企业客户 |

---

## 底层技术

### 核心技术栈

| 层级 | 技术 |
|------|------|
| **底层模型** | 支持主流 LLM（具体提供商未公开） |
| **特色功能** | Memories、RULE、Cascade |
| **扩展协议** | MCP (Model Context Protocol) |
| **架构模式** | 单 Agent + 记忆系统 |

### 技术架构

```
用户指令 → Cascade (记忆上下文) → 执行 → 持续学习
                   ↓
            Memories (项目记忆)
            Rules (自定义规则)
```

---

## 核心技术特点

### 1. Cascade AI 引擎

- 理解项目上下文
- 智能记忆项目信息
- 持续学习进化

### 2. Memories (记忆系统)

- **跨会话记住**：项目结构和偏好
- **理解工作流**：开发者习惯
- **积累上下文**：越用越懂项目

### 3. Rules (规则引擎)

- 开发者可定义编码规范
- AI 严格遵循项目规范
- 支持框架特定规则（如 Next.js 模式）

### 4. MCP 支持

- 一键连接 MCP Servers
- 内置集成：Figma、Slack、Stripe、GitHub、Postgres 等
- 插件商店持续扩展

### 5. Turbo Mode

- AI 自主执行终端命令
- 自动检测并修复 lint 错误
- 自动化工作流

---

## 优势

✅ **免费使用**：对个人开发者友好  
✅ **智能记忆**：越用越懂你的项目  
✅ **JetBrains 插件**：首个官方 AI 插件入驻 JetBrains IDE  
✅ **实时预览**：内置服务器，拖拽图片即可生成 UI  

## 局限

⚠️ 企业功能相对较弱  
⚠️ 模型选择不如 Cursor 灵活  

---

## 相关链接

- [官网](https://windsurf.com)
- [Cascade on JetBrains](https://windsurf.com/blog/cascade-on-jetbrains)
