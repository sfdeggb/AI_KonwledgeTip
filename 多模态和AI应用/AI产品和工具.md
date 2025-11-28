# AI 工具箱

> 按功能类型梳理常用 AI 工具，方便快速定位、对比与落地。每个条目都包含定位亮点、典型使用场景以及可用链接，可直接根据需求挑选。

## 快速导览
- [代码与工程效率](#代码与工程效率)：代码生成、AI IDE、自动化数据处理
- [设计与创意表达](#设计与创意表达)：原型设计、视觉创作、演示文稿
- [知识整理与写作](#知识整理与写作)：思维导图、研究写作、资料梳理
- [模型体验与平台](#模型体验与平台)：最新模型体验、长上下文、AI Studio
- [资源索引与生态](#资源索引与生态)：MCP 工具与扩展资源

---

## 代码与工程效率

| 工具 | 定位亮点 | 典型场景 | 访问 / 资源 |
| --- | --- | --- | --- |
| Blackbox | 多模型驱动的 AI 代码副驾，支持自然语言调试与补全 | 快速生成函数、补齐单测、Review 复杂代码 | [blackbox.ai](https://www.blackbox.ai/chat/WzCrMdZ) |
| GitHub Models / Codespaces | GitHub 官方模型集市，直接在 Codespaces 或 API 内调用 | 在统一环境中试用多家基础模型，评估集成效果 | [github.com/marketplace/models](https://github.com/marketplace/models) |
| Cursor | AI-first IDE，内置对话式结对编程与多文件重构 | 本地或远程仓库的代码导航、批量修改、调试 | [cursor](https://www.cursor.com/) |
| Firecrawl | AI + 爬虫框架，支持多源抓取与结构化解析 | 自动化采集网页、为 RAG/Agent 准备干净数据 | [github.com/mendableai/firecrawl](https://github.com/mendableai/firecrawl) |
| Data Formulator | 上传数据即可自动洞察、生成可视化与 SQL | 快速探索 CSV/Parquet 数据，验证业务假设 | [github.com/microsoft/data-formulator](https://github.com/microsoft/data-formulator) |

## 设计与创意表达

| 工具 | 定位亮点 | 典型场景 | 访问 / 资源 |
| --- | --- | --- | --- |
| Mockups Design | 批量生成高保真原型与展示图 | 品牌提案、产品包装、终稿展示 | [mockups-design.com](https://mockups-design.com/) |
| Lovart | 专业设计 Agent，从创意到交付全链路覆盖 | 视觉主KV、海报、品牌延展；有案例可参考 | [官网](https://www.lovart.ai/?utm_source=ai-bot.c)<br>[案例](https://mp.weixin.qq.com/s/zjgBFWUZs-XZelMKqPm5bw) |
| Napkin | 任意文本转图片，强调速度与风格一致性 | 快速探索概念草图、社交媒体视觉素材 | [napkin.ai](https://www.napkin.ai/) |
| AIPPT | 将提纲一键转换为结构化 PPT | 周会汇报、方案初稿、课程讲义 | [AIPPT 介绍](https://mp.weixin.qq.com/s/FqmGZo_PaVvT7he7B6EXrg) |

## 知识整理与写作

| 工具 | 定位亮点 | 典型场景 | 访问 / 资源 |
| --- | --- | --- | --- |
| Flowwith | 将复杂问题拆解为思维导图式步骤，辅助推理 | 多人研讨、产品方案梳理、学习路径规划 | 暂无官方链接，欢迎补充 |
| Storm | 斯坦福开源的学术写作助手，支持引用管理与草稿生成 | 论文写作、技术博客、研究报告 | [github.com/stanford-oval/storm](https://github.com/stanford-oval/storm?tab=readme-ov-file) |
| NotebookLM | 谷歌推出的资料整理工具，可上传多源素材进行总结、问答 | 深入研究某一主题，从碎片资料到系统笔记 | [notebooklm.google](https://notebooklm.google/) |

![NoteBook LM Image](../assest/notebokml.png)

## 模型体验与平台

| 工具 / 平台 | 定位亮点 | 典型场景 | 访问 / 资源 |
| --- | --- | --- | --- |
| Google Gemini 1.5 | 对标 GPT-4o 的多模态模型，可在 AI Studio 中体验 | 代码生成、多模态理解、交互式 Agent | [aistudio.google.com/app/prompts/1Pan_SpS-0tri8YCl16_EDIex3o_C2MMy](https://aistudio.google.com/app/prompts/1Pan_SpS-0tri8YCl16_EDIex3o_C2MMy) |
| Google AI Studio | Google 官方模型体验与部署平台 | 快速验证 Prompt、创建自定义 DAN 助手 | [aistudio.google.com](https://aistudio.google.com/) |
| OpenAI SearchGPT Prototype | 面向搜索的对话体验，聚合多源事实 | 获取实时资料、验证新闻、准备调研简报 | [openai.com/index/searchgpt-prototype](https://openai.com/index/searchgpt-prototype/) |
| LM Arena | 社区驱动的最新模型比武场，支持一键试用 | 第一时间体验新模型、比较模型表现 | [lmarena.ai](https://lmarena.ai/) |
| Magic LTM-2 Mini | 100M token 超长上下文模型，可一次读取海量资料 | 法务/科研等长文档理解、长程对话 | [magic.dev/blog/100m-token-context-windows](https://magic.dev/blog/100m-token-context-windows) |

## 资源索引与生态

- MCP 工具目录  
  - [smithery.ai](https://smithery.ai/)  
  - [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers?tab=readme-ov-file#browser-automation)
- `Cursor`、`Blackbox` 等工具可组合使用，配合 Firecrawl/NotebookLM 形成 “采集 → 理解 → 生成” 的闭环。
- 欢迎补充更多优质工具或案例，保持清单的鲜活度。
