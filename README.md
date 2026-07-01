# ZotLite — Zotero AI 阅读助手

> 为 Zotero 打造的一体化 AI 文献阅读助手：智能问答、PDF 高精度解析、影响因子与引用量展示、元数据一键补全。

ZotLite 把大语言模型、MinerU 文献解析、影响因子数据集和元数据抓取整合进 Zotero 的工作流，让你在阅读、整理、写作时不再频繁切换窗口。

---

## 核心功能

### 🤖 AI 智能问答

- 内置 **DeepSeek、OpenAI、Google Gemini** 三大提供商，可在设置中一键切换。
- 支持流式输出、Markdown 渲染、LaTeX 公式（KaTeX）。
- 主界面侧边栏 + PDF 阅读器侧边栏双入口，路由中心自动识别当前标签页。
- 自定义「快捷提示词」胶囊，常用指令一键发送。
  <img width="554" height="1322" alt="image" src="https://github.com/user-attachments/assets/05a176cf-b6b5-49bc-a38f-499c023b4cf3" />


### 📄 MinerU 高精度 PDF 解析

- 调用 MinerU 官方云 API，把文献 PDF 转换为结构化 Markdown。
- 完整保留公式、表格、图注等复杂结构，显著提升 AI 阅读理解质量。
- 本地缓存机制，重复解析零成本，支持一键清理。
- 点击跳转原文位置。
- 

### 📊 影响因子 & 引用量

- 文献库列表新增 **IF（影响因子）** 和 **CC（引用量）** 列，内置 2025 年 JCR 数据集。
- 文献详情面板同步显示，无需联网查询。
- 支持期刊名称模糊匹配（含常见缩写归一化）。
  <img width="423" height="239" alt="image" src="https://github.com/user-attachments/assets/0fc64bd4-2345-48ec-8af1-7649d3d017d8" />


### 🧹 元数据管理

- 右键菜单一键 **更新元数据与引用量**（数据源：Crossref / Semantic Scholar）。
- 一键 **清理元数据排版**：把 JATS 标签转换为上下标、斜体等 Unicode 字符。
- 批量处理选中文献。

### 🌐 其他特性

- 中英双语界面，首选项中实时切换。
- 工具栏按钮 + 右键菜单 + 侧边栏多入口。
- 兼容 Zotero 8 的 `MenuManager`，同时保留 Zotero 7 的传统菜单注入。
- 自动打开侧边栏、可调侧边栏宽度。
