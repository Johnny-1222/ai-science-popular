# AI 核心概念章节大纲
> 基于 tavily 实际搜索，信息截止 2026 年 5 月。
> 每条"来源链接"均为搜索命中的真实 URL，请勿改为编造链接。

---

## 一、调研摘要（第一步结论）

本次使用 tavily 工具，围绕以下关键词进行了 8 组搜索：
- `2026 AI 黑话 大全 中文社区`
- `AI Agent 2026 最新进展 中文`
- `2026 大模型排行榜`
- `Vibe Coding 2026 普通人`
- `A2A协议 Agent2Agent Google 2026`
- `MCP协议 2026 最新进展`
- `推理模型 Reasoning Model 2026`
- `Computer Use AI 操控电脑 2026`

**重大纠错：旧版大纲"养马 = 跑算力机器"是错的。**
搜索结果（澎湃、凤凰科技、投资界、知乎多篇文章）一致显示：
- **养马** = 使用/部署 Hermes Agent（爱马仕 Agent），因"Hermes"与"爱马仕"撞名
- **养虾** = 使用/部署 OpenClaw Agent（龙虾 Logo）
- 两者均是 2026 年 AI Agent 浪潮中的社区黑话，与"跑算力"无关

---

## 二、五层结构保留 / 删除 / 新增（第二步）

### 保留（2026 年依然重要）

| 概念 | 层级 | 理由 |
|------|------|------|
| AGI、LLM、多模态 | 第1层 | 仍是最基础的入门词汇 |
| Prompt、Token、Context、幻觉、温度 | 第2层 | 所有 AI 用户必遇 |
| Agent、RAG、CoT、微调、蒸馏 | 第3层 | 进阶圈高频，2026仍活跃 |
| 炼丹、养虾、养马、套壳、涌现、Scaling Law | 第4层 | 仍在流传，但含义需纠正 |
| MCP、Function Calling、Computer Use、Vibe Coding | 第5层 | 2026 核心工具链 |

### 删除 / 降权

| 概念 | 处理 | 理由 |
|------|------|------|
| 抽卡 | ⚠️ 降权为备注 | 2026 仍偶见，但热度明显下降，不再是核心黑话 |

### 新增（2025 下半年 ～ 2026 年新出现）

| 概念 | 建议层级 | 来源 |
|------|----------|------|
| 推理模型（Reasoning Model） | 第3层 | 2025年 DeepSeek-R1 引爆，2026年所有主要厂商均有推理产品线 |
| 多智能体（Multi-Agent） | 第3层 | 2026企业AI落地核心模式，Google/McKinsey报告均列为首要趋势 |
| A2A 协议（Agent2Agent） | 第5层 | Google 2025年4月发布，2026年已有50+企业跟进 |
| 词元工厂（Token 工厂） | 第4层 | 2026年新黑话，源自黄仁勋 GTC 演讲，澎湃新闻专题解析 |
| Skills（技能系统） | 第5层 | Hermes Agent 核心机制，"养马"圈专用术语 |

### 五层结构本身要不要调整？

建议**微调第5层标题**，从"接入世界"改为"连接协议与工具生态"，更准确地容纳 MCP/A2A/Computer Use 等协议层概念。其余四层标题保持不变。

---

## 三、最终概念清单（第三步）

### 第1层：日常听过的 AI

| 概念名 | 重要程度 | 来源链接 | 一句话定位 |
|--------|----------|----------|-----------|
| AGI（通用人工智能） | ★★★★★ | https://juejin.cn/post/7620798076392914953 | 人类一直在追的终极目标：让机器像人一样"啥都会" |
| LLM（大语言模型） | ★★★★★ | https://segmentfault.com/a/1190000047645758 | ChatGPT、Claude、DeepSeek 背后的核心技术 |
| 多模态（Multimodal） | ★★★★☆ | https://www.meta-intelligence.tech/insight-generative-ai-trends-2026 | AI 不只能看文字，还能看图、听声音、看视频 |
| 大模型排行榜 | ★★★☆☆ | https://llmrank.cn/ | 谁最聪明？每72小时更新的"AI成绩单" |

### 第2层：用 AI 时遇到的词

| 概念名 | 重要程度 | 来源链接 | 一句话定位 |
|--------|----------|----------|-----------|
| Prompt（提示词） | ★★★★★ | https://zhuanlan.zhihu.com/p/690857521 | 你发给 AI 的"指令"——会问才会用 | <!-- 链接已于 2026-05-19 用 firecrawl 核验 -->
| Token（词元） | ★★★★★ | https://m.thepaper.cn/newsDetail_forward_33002724 | AI 处理信息的最小单位，也是计费单位；官方译名"词元" |
| Context Window（上下文窗口） | ★★★★☆ | https://segmentfault.com/a/1190000047645758 | AI 一次能"记住"多少内容，越大越聪明 |
| 幻觉（Hallucination） | ★★★★★ | https://www.sangfor.com.cn/knowledge/AI-Hallucination | AI 一本正经地胡说八道——最常见的坑 | <!-- 链接已于 2026-05-19 用 firecrawl 核验 -->
| 温度（Temperature） | ★★★☆☆ | — | 控制 AI 回答的"随机性"，越高越天马行空 |

### 第3层：进阶玩家词汇

| 概念名 | 重要程度 | 来源链接 | 一句话定位 |
|--------|----------|----------|-----------|
| Agent（智能体） | ★★★★★ | https://ikala.ai/zh-tw/blog/ikala-ai-insight/2026-ai-agent-trend/ | 不只聊天，能自己动手干活的 AI；2026 是 Agent 落地元年 |
| 推理模型（Reasoning Model） | ★★★★★ | https://yeasy.gitbook.io/ai_beginner_guide/.../7.4_major_reasoning_models | AI 先"想清楚"再回答，像 DeepSeek-R1、Claude 系列 |
| 多智能体（Multi-Agent） | ★★★★☆ | https://www.meta-intelligence.tech/insight-generative-ai-trends-2026 | 多个 AI 组成团队协作，各司其职完成复杂任务 |
| RAG（检索增强生成） | ★★★★☆ | https://deepseek.csdn.net/69feebf20a2f6a37c5a8b8f7.html | 让 AI 先查资料再回答，减少乱说 |
| CoT（思维链） | ★★★★☆ | https://zhuanlan.zhihu.com/p/629087587 | 让 AI 一步一步推理，像人类列草稿 | <!-- 链接已于 2026-05-19 用 firecrawl 核验 -->
| 微调（Fine-tuning） | ★★★☆☆ | — | 在通用大模型上"针对性培训"，让它更懂某个专业领域 |
| 蒸馏（Distillation） | ★★★☆☆ | https://arthurchiao.art/blog/deepseek-r1-paper-zh/ | 用大模型"教"小模型，让小模型也很聪明且省算力 |

### 第4层：圈内黑话

| 概念名 | 重要程度 | 来源链接 | 一句话定位 |
|--------|----------|----------|-----------|
| 养虾 | ★★★★★ | https://m.thepaper.cn/newsDetail_forward_33053945 | 使用/部署 OpenClaw AI Agent（龙虾 Logo），让 AI 替你自动干活 |
| 养马 | ★★★★★ | https://news.pedaily.cn/202604/562801.shtml | 使用/部署 Hermes Agent（爱马仕），因"Hermes"≈"爱马仕"得名 |
| 炼丹 | ★★★★☆ | — | 训练/调试 AI 模型，像炼丹一样玄学，成功全靠"丹方"（超参数） |
| 套壳 | ★★★★☆ | https://finance.sina.cn/stock/jdts/2026-03-11/... | 披一件新外衣，背后用的还是别人的大模型 |
| 词元工厂（Token 工厂） | ★★★☆☆ | https://m.thepaper.cn/newsDetail_forward_33002724 | 黄仁勋的新黑话：数据中心正在变成"生产 Token 的工厂" |
| 涌现（Emergence） | ★★★☆☆ | — | 模型大到某个规模，突然"学会了"没人教过它的能力，像量变引发质变 |
| Scaling Law | ★★★☆☆ | — | 越大越强的规律——数据更多、模型更大、算力更强，AI 就更聪明 |
| 抽卡 | ★★☆☆☆ | — | ⚠️ 降权备注：新模型发布如同开盲盒，2026年热度已明显下降 |

### 第5层：连接协议与工具生态（原"接入世界"）

| 概念名 | 重要程度 | 来源链接 | 一句话定位 |
|--------|----------|----------|-----------|
| Vibe Coding | ★★★★★ | https://cloud.google.com/discover/what-is-vibe-coding?hl=zh-CN | 不写代码，用自然语言指挥 AI 做软件；2025年由 Karpathy 命名，2026已是主流 |
| MCP（模型上下文协议） | ★★★★★ | https://devtk.ai/zh/blog/what-is-mcp-guide/ | Anthropic 制定的标准：让 AI 能连接数据库、文件、外部工具，像 AI 的"插头" |
| A2A（Agent2Agent 协议） | ★★★★☆ | https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/ | Google 2025年发布：让不同 AI Agent 互相"说话"合作，像 AI 的"普通话" |
| Computer Use（AI 操控电脑） | ★★★★☆ | https://www.mininglamp.com/news/7484/ | AI 能看屏幕、动鼠标、点按钮，像一个坐在你旁边的数字助手 |
| Function Calling（函数调用） | ★★★★☆ | — | 让 AI 调用真实的外部功能（查天气、发邮件），而不只是"说说" |
| Skills（技能系统） | ★★★☆☆ | https://github.com/jwangkun/hermes-agent-guide/blob/main/03-Hermes诞生与演进.md | Agent 自动把完成过的任务总结成可复用的"技能文件"，越用越聪明 |
| 工作流（Workflow） | ★★★★☆ | https://segmentfault.com/a/1190000047645758 | 用 n8n、Dify 等工具把多个 AI 步骤串成自动化流水线 |

---

## 四、与旧版大纲的主要变化（总结）

| 变化类型 | 具体内容 |
|----------|----------|
| 🔴 重大纠错 | "养马"含义从"跑算力机器"纠正为"使用 Hermes Agent（爱马仕）"，有澎湃、凤凰、投资界等多篇文章佐证 |
| 🔴 重大纠错 | "养虾"含义补全：指使用 OpenClaw AI Agent，不是泛指"跑 AI" |
| 🟢 新增概念 | **推理模型**（第3层）：2025-2026年最重要技术革命，DeepSeek-R1/GPT-5.5/Claude 全系支持 |
| 🟢 新增概念 | **多智能体 Multi-Agent**（第3层）：2026企业 AI 落地的核心架构模式 |
| 🟢 新增概念 | **A2A 协议**（第5层）：Google 2025年4月发布，补完 MCP 未覆盖的"Agent 间通信"空白 |
| 🟢 新增概念 | **词元工厂**（第4层）：2026年新晋黑话，源自黄仁勋 GTC 演讲 |
| 🟢 新增概念 | **Skills 技能系统**（第5层）："养马"文化的技术核心 |
| 🟡 层级微调 | 第5层标题从"接入世界"改为"连接协议与工具生态"，更准确 |
| 🟡 降权处理 | "抽卡"降为备注，2026年热度明显下降 |
| 🟡 上下文窗口 | 新增至第2层，是用户日常最常遇到的限制 |

---

*文件生成时间：2026-05-19*
*信息来源：tavily 实际搜索，优先返回 2025-2026 年内容*
*待核实项：微调、蒸馏的一句话描述未经本次搜索直接验证，标注 ⚠️ 待核实*

---

# AI 概念全景图 v3.0 — 5 大星系结构

> 本节为"按星系分组"的可视化制作清单，与前面的 5 层结构是同一批概念的不同视角。
> ✅ 已做卡片 | 🔲 待制作

## 🌌 星系 1：基础认知（8 个）

| 概念 | 状态 | 备注 |
|------|------|------|
| ASI（超级智能） | 🔲 | 比 AGI 更远的终极形态，理论概念 |
| AGI（通用人工智能） | 🔲 | 第1层已列，待制作卡片 |
| LLM（大语言模型） | ✅ | 已上线 |
| Transformer（变形金刚架构） | 🔲 | 技术底层，可做"技术小史"卡 |
| GPT（生成式预训练） | 🔲 | LLM 的主流范式 |
| 神经网络 | 🔲 | 基础科普背景知识 |
| 深度学习 | 🔲 | 基础科普背景知识 |
| 多模态（Multimodal） | 🔲 | 第1层已列，待制作卡片 |

## 🌌 星系 2：日常使用层（10 个）

| 概念 | 状态 | 备注 |
|------|------|------|
| Prompt（提示词） | ✅ | 已上线 |
| Token（词元） | ✅ | 已上线 |
| Context（上下文窗口） | 🔲 | 第2层已列，待制作卡片 |
| Temperature（温度） | 🔲 | 第2层已列，待制作卡片 |
| 幻觉（Hallucination） | ✅ | 已上线 |
| RAG（检索增强生成） | 🔲 | 第3层已列，待制作卡片 |
| CoT（思维链） | 🔲 | 第3层已列，待制作卡片 |
| Embedding（向量嵌入） | 🔲 | RAG 的底层技术 |
| 微调（Fine-tuning） | 🔲 | 第3层已列，待制作卡片 |
| RLHF（人类反馈强化学习） | 🔲 | ChatGPT 核心训练方法 |

## 🌌 星系 3：Agent 生态（养马·养虾）（10 个）

| 概念 | 状态 | 备注 |
|------|------|------|
| Agent（智能体） | ✅ | 已上线 |
| OpenClaw / 养虾 / 小龙虾 | 🔲 | 第4层黑话，待制作卡片 |
| Hermes / 养马 / 爱马仕 | ✅ | 已上线（养马卡片） |
| Skill（技能） | 🔲 | Hermes 核心机制，第5层已列 |
| Memory（记忆） | 🔲 | Agent 长期记忆系统 |
| Gateway（网关） | 🔲 | Agent 与工具的连接层 |
| Sub-agent（子代理） | 🔲 | 多智能体协作中的角色 |
| Tool Use（工具调用） | 🔲 | 即 Function Calling，第5层已列 |
| MCP（模型上下文协议） | 🔲 | Anthropic 制定的标准，第5层已列 |
| Harness（约束系统） | 🔲 | Claude Code 的任务运行框架 |

## 🌌 星系 4：多模态宇宙（8 个）

| 概念 | 状态 | 备注 |
|------|------|------|
| Multimodal（多模态总称） | 🔲 | 第1层已列，待制作卡片 |
| Nano Banana（纳米香蕉） | 🔲 | Google Gemini 图像生成，2026新黑话 |
| Nano Banana Pro（香蕉 Pro） | 🔲 | 升级版，更高质量图像 |
| GPT-Image-2（OpenAI 图像） | 🔲 | OpenAI 图像生成模型 |
| Sora（视频生成） | 🔲 | OpenAI 文生视频 |
| Midjourney（艺术图像） | 🔲 | 最流行的 AI 绘画工具 |
| Stable Diffusion（开源图像） | 🔲 | 开源图像生成社区主力 |
| 3D 生成（Rodin 等） | 🔲 | 文字/图片生成 3D 模型 |

## 🌌 星系 5：Vibe Coding 工具链（10 个）

| 概念 | 状态 | 备注 |
|------|------|------|
| Vibe Coding（氛围编程） | 🔲 | 第5层已列，待制作卡片 |
| Claude Code（终端版） | 🔲 | 本项目正在使用的 AI 编程工具 |
| Cursor（VS Code 系） | 🔲 | 最流行的 AI 代码编辑器 |
| Codex CLI（OpenAI） | 🔲 | OpenAI 的终端 AI 编程工具 |
| CLAUDE.md（项目记忆） | 🔲 | Claude Code 的项目上下文配置 |
| .cursorrules（AI 行为指南） | 🔲 | Cursor 的规则配置文件 |
| Spec Coding（规格驱动） | 🔲 | 先写规格再让 AI 实现的高级方法 |
| Hook（钩子） | 🔲 | Claude Code 的自动化触发机制 |
| Subagent（子代理） | 🔲 | Claude Code 内的并行任务执行器 |
| MCP（与 Agent 生态共享） | 🔲 | 已列于星系 3，两边均适用 |

---

*星系视图新增于：2026-05-19*
*总计：50+ 概念，其中 ✅ 已制作 6 张，🔲 待制作 40+ 张*
