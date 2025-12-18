# jitai-ai

**JitAI生产级AI能力集成框架**

[🇺🇸 English](README.md) | [🇨🇳 中文](README_ZH.md)

---

> ⚠️ **重要提示**
>
> **jitai-ai**是JitAI开发框架的组成部分之一。
>
> 如需搭建完整的开发环境，请访问 **[jitai-team/quickstart](https://github.com/jitai-team/quickstart)** 仓库。

---

## ✨ 核心特性

- **统一 LLM 集成**: 无缝连接各种大模型（OpenAI、Anthropic、本地模型等）
- **ReAct Agent**: 强大的 ReAct 范式 Agent 运行时支持
- **RAG 支持**: 内置 Chroma 向量库，开箱即用的检索增强生成能力
- **AI 助理**: 标准 AI 助理运行时能力
- **知识库管理**: 知识库创建、向量化存储与检索

### 🌟 AI原生架构优势

JitAI 基于 **[JAAP (Jit AI Application Protocol)](https://jit.pro/zh/docs/reference/runtime-platform/JAAP)**，实现了真正的 AI 驱动：

| 能力 | 说明 |
|:---|:---|
| **🧠 全栈模块感知** | 系统中的所有模块都具备自描述能力，AI 能够实时感知并理解它们的功能、参数和用法 |
| **🎮 智能驱动与编排** | AI 通过统一语法动态调用和编排任何模块，实现业务流程的自主规划与执行 |
| **🤝 人智协同** | AI 与人类在同一 UI 界面上协作，AI 可操作前端组件（生成图表、填写表单等） |

## 🆚 社区版 vs 商业版

| 功能模块 | 具体能力 | 🟢 社区版 | 🔵 商业版 |
| :--- | :--- | :---: | :---: |
| **大模型基础** | 所有类型模型支持 | ✅ | ✅ |
| **向量数据库** | Chroma DB 支持 | ✅ | ✅ |
| **ReAct Agent** | 运行时执行 | ✅ | ✅ |
| | 可视化编辑器 | ❌ | ✅ |
| **AI 助理** | 标准助理运行时 | ✅ | ✅ |
| | 标准助理可视化编辑器 | ❌ | ✅ |
| | 嵌入式 AI 助理 | ❌ | ✅ |
| **知识库** | 标准知识库运行时 | ✅ | ✅ |
| | 标准知识库可视化编辑器 | ❌ | ✅ |

**注**: 部分可视化编辑器未开源，但开发者在[桌面客户端](https://jit.pro/download)中可以免费使用全部可视化开发能力。

## 🤝 参与贡献

我们欢迎任何形式的贡献！请参阅[quickstart](https://github.com/jitai-team/quickstart)了解如何开始。

