# 🧩 Skill ZIP Repository

![skills](https://img.shields.io/badge/skills-60-blue) ![updated](https://img.shields.io/badge/updated-2026--2--24-green) ![size](https://img.shields.io/badge/total-101MB-orange)

Claude Code / Codex / Gemini CLI 技能集中仓库 — 每个 skill 独立 ZIP 打包，按需下载安装。

## 📥 安装方法

### 方法 1：脚本下载（推荐）
```bash
# 列出所有可用 skills
curl -sL "https://raw.githubusercontent.com/kkunkunya/skill-zip/main/index.json" | python3 -c "import sys,json; [print(s['name']) for s in json.load(sys.stdin)['skills']]"

# 下载并安装指定 skill
SKILL=ui-ux-pro-max && curl -L "https://github.com/kkunkunya/skill-zip/raw/main/${SKILL}.zip" -o /tmp/${SKILL}.zip && unzip -o /tmp/${SKILL}.zip -d ~/.claude/skills/
```

### 方法 2：直接下载
点击下方表格中的「下载」链接，解压到 `~/.claude/skills/` 目录即可。

## 📋 技能列表

### 🎓 学术科研

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| academic-research-skills | 学术科研综合技能包。整合 34 个核心科研技能，来源：K-Dense-AI (7800+ stars) + ChineseResearchLaTeX (7... | 21.7MB | [下载](academic-research-skills.zip) |
| paper-composer | 学术论文写作与构思技能。基于核心参考论文分析，结合 academic-research-skills 生成详细写作思路，按章节推进论文撰写并进行反思优化。... | 8KB | [下载](paper-composer.zip) |
| ai-deweight | Enhances academic writing originality and reduces AI detection scores using B... | 37KB | [下载](ai-deweight.zip) |
| library-researcher | 学术文献搜索下载工具。确认VPN登录后，在学校发现系统批量检索下载，智能记录成功/失败文献。 | 7KB | [下载](library-researcher.zip) |
| sci-hub-downloader | Sci-Hub文献PDF下载工具。使用Playwright浏览器MCP通过Sci-Hub镜像下载学术文献PDF，自动处理镜像切换、PDF提取和文件重命名。... | 3KB | [下载](sci-hub-downloader.zip) |
| mineru-transfer | MinerU 文档转换工具（基于 VLM 的高质量 OCR）。支持 PDF、DOCX、PPT、图片、HTML → Markdown。当用户需要：(1) 提... | 5KB | [下载](mineru-transfer.zip) |
| 20-ml-paper-writing | Write publication-ready ML/AI papers for NeurIPS, ICML, ICLR, ACL, AAAI, COLM... | 721KB | [下载](20-ml-paper-writing.zip) |
| results-driven-rl | 效果驱动的强化学习实验开发。优先保证训练收敛、结果好看、图表可用于论文，不深究实现细节。当用户需要：(1) 开发RL实验代码并产出论文级结果；(2) 诊断... | 11KB | [下载](results-driven-rl.zip) |

### 📝 内容创作

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| content-producer | 采访式内容生产技能（L0/L1/L2 三层架构）。 核心方法：AI 做编辑不做作者——通过采访捕捉用户原声，整理为平台适配内容。 一次采访，多平台分发。V... | 25KB | [下载](content-producer.zip) |
| diary-companion | 日记伴侣（显微镜 🔬）— 深度阅读一篇日记，通过采访式对话和三角度深度思考，与用户碰撞产生有价值的洞察。 触发词：日记分析、阅读建议、洞察提炼、思考伙伴、... | 10KB | [下载](diary-companion.zip) |
| vault-layer-manager | 思考花园的园丁 🔭 — 从 diary-companion 的深度对话记录中提炼 L1 知识资产， 与用户深度讨论选题方向和知识组织。主要由 diary-... | 4KB | [下载](vault-layer-manager.zip) |
| humanizer-skill | Remove signs of AI-generated writing from text. Use when editing or reviewing... | 14KB | [下载](humanizer-skill.zip) |
| doc-coauthoring | Guide users through a structured workflow for co-authoring documentation. Use... | 6KB | [下载](doc-coauthoring.zip) |
| baoyu-format-markdown | Formats plain text or markdown files with frontmatter, titles, summaries, hea... | 16KB | [下载](baoyu-format-markdown.zip) |
| baoyu-markdown-to-html | Converts Markdown to styled HTML with WeChat-compatible themes. Supports code... | 50KB | [下载](baoyu-markdown-to-html.zip) |

### 🎨 设计与图像

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| ui-ux-pro-max | UI/UX design intelligence for web and AI-native interfaces. Covers style plan... | 123KB | [下载](ui-ux-pro-max.zip) |
| image-generator | Generates AI images using Gemini API with requirement confirmation workflow. ... | 14KB | [下载](image-generator.zip) |
| baoyu-image-gen | AI image generation with OpenAI, Google and DashScope APIs. Supports text-to-... | 14KB | [下载](baoyu-image-gen.zip) |
| meigen-design | 创意设计图像生成技能（基于 MeiGen MCP）。用于产品图、Logo、海报、品牌设计、 社交媒体配图等创意类图像生成。提供 1300+ prompt ... | 2KB | [下载](meigen-design.zip) |
| baoyu-infographic | Generates professional infographics with 20 layout types and 17 visual styles... | 33KB | [下载](baoyu-infographic.zip) |
| baoyu-xhs-images | Generates Xiaohongshu (Little Red Book) infographic series with 10 visual sty... | 38KB | [下载](baoyu-xhs-images.zip) |
| baoyu-cover-image | Generates article cover images with 5 dimensions (type, palette, rendering, t... | 46KB | [下载](baoyu-cover-image.zip) |
| baoyu-article-illustrator | Analyzes article structure, identifies positions requiring visual aids, gener... | 39KB | [下载](baoyu-article-illustrator.zip) |
| playground | Creates interactive HTML playgrounds — self-contained single-file explorers t... | 14KB | [下载](playground.zip) |

### 📱 社交媒体发布

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| baoyu-post-to-wechat | Posts content to WeChat Official Account (微信公众号) via API or Chrome CDP. Suppo... | 78KB | [下载](baoyu-post-to-wechat.zip) |
| baoyu-post-to-x | Posts content and articles to X (Twitter). Supports regular posts with images... | 34KB | [下载](baoyu-post-to-x.zip) |
| baoyu-danger-x-to-markdown | Converts X (Twitter) tweets and articles to markdown with YAML front matter. ... | 33KB | [下载](baoyu-danger-x-to-markdown.zip) |

### 🛠️ 开发工具

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| systematic-debugging | Applies systematic debugging methodology when encountering bugs, test failure... | 7KB | [下载](systematic-debugging.zip) |
| test-driven-development | Enforces test-driven development methodology before implementing features or ... | 3KB | [下载](test-driven-development.zip) |
| verification-before-completion | Requires verification before claiming task completion, successful fixes, or p... | 3KB | [下载](verification-before-completion.zip) |
| skill-creator | Guide for creating effective skills. This skill should be used when users wan... | 69KB | [下载](skill-creator.zip) |
| hooks-manager | Manages Claude Code Hooks for creating, viewing, modifying, and debugging eve... | 4KB | [下载](hooks-manager.zip) |
| find-skills | Helps users discover and install agent skills when they ask questions like "h... | 2KB | [下载](find-skills.zip) |
| threejs-suite | Three.js 3D开发全栈技能包，涵盖场景搭建、几何体、材质、光照、纹理、动画、交互、模型加载、着色器、后处理。Use when working wi... | 43KB | [下载](threejs-suite.zip) |
| simulink-model-builder | Builds MATLAB Simulink models programmatically with cross-version compatibili... | 50KB | [下载](simulink-model-builder.zip) |
| ai-elements | Create new AI chat interface components for the ai-elements library following... | 360KB | [下载](ai-elements.zip) |

### 📦 项目与仓库管理

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| github-project-manager | GitHub 项目全生命周期管理 v2：仓库初始化、README 美化、分支保护、元数据设置、质量评分、Agent 协调、定时同步、PR/Issue 管理... | 28KB | [下载](github-project-manager.zip) |
| github-uploader | Uploads current project to GitHub with one command. Automatically initializes... | 3KB | [下载](github-uploader.zip) |
| project-zip | Intelligently compresses and packages projects into ZIP archives with environ... | 4KB | [下载](project-zip.zip) |
| skill-zip-sync | 将 ~/.claude/skills/ 下的所有 skill 打包成独立 ZIP 并同步到 GitHub 仓库，支持按需下载。触发词：同步 skill、s... | 8KB | [下载](skill-zip-sync.zip) |
| req-project-dev-draft | Guides projects from requirements to development through an outcome-driven wo... | 21KB | [下载](req-project-dev-draft.zip) |
| best-practices-lookup | 方案设计前自动查询相关最佳实践，保存到项目 docs/best-practices/。 触发词："查找最佳实践"、"best practices"、"最佳... | 3KB | [下载](best-practices-lookup.zip) |

### 🔧 系统与基础设施

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| claude-md-maintainer | CLAUDE.md 维护规范（添加工具/技能、修改规则、精简审计） | 2KB | [下载](claude-md-maintainer.zip) |
| system-self-iterator | 系统进化引擎 ⚡ — 双入口（日记洞察 + 外部文章），通过三透镜深度分析驱动 Claude Code 系统持续进化。维护系统状态快照，确认后自动执行改进... | 6KB | [下载](system-self-iterator.zip) |
| config-migrator | Migrates Claude Code configurations to Codex CLI with an AI-first workflow (u... | 14KB | [下载](config-migrator.zip) |
| autodl-deployer | AutoDL GPU云平台项目部署与迁移工具。默认交换路径：/root/autodl-fs/（上传下载都走这里，无data/子目录）。当用户需要：(1) ... | 19KB | [下载](autodl-deployer.zip) |
| ssh-file-transfer | 通用 SSH 操作技能（LLM 规划 + Python 编译校验）。用于任何 SSH 任务：远端命令执行、上传下载、目录增量同步、发布与回滚、日志排障、端... | 12KB | [下载](ssh-file-transfer.zip) |
| firecrawl | Firecrawl handles all web operations with superior accuracy, speed, and LLM-o... | 5KB | [下载](firecrawl.zip) |
| document-suite | Unified document processing for DOCX, XLSX, PDF, PPTX. Create, read, edit doc... | 146KB | [下载](document-suite.zip) |
| notebooklm | Complete API for Google NotebookLM - full programmatic access including featu... | 8KB | [下载](notebooklm.zip) |

### 🤖 AI 协作

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| multi-model-collaborator | 多模型协作技能（Team 嵌套并行模式）。通过 Team 机制将 Codex 作为持久团队成员，支持双向通信、多轮追问、Squad Leader 裂变并行... | 4KB | [下载](multi-model-collaborator.zip) |
| dify-workflow-builder | Dify 智能体工作流创建与优化专家。用于：(1) 创建新的 Dify Workflow/Chatflow 应用 YAML 配置；(2) 优化现有 Dif... | 9KB | [下载](dify-workflow-builder.zip) |

### 🎬 视频

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| video-wrapper | LLM-first 的访谈视频特效与双语字幕工作流。LLM 负责采访、审批、语义翻译与多 Agent 编排；CLI 仅执行下载/渲染等确定性步骤。支持 4... | 75.5MB | [下载](video-wrapper.zip) |

### 💼 商务

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| freelance-advisor | 学生项目及私单技术顾问（云GPU成本版）。以双重身份（对内参谋+对外合伙人）帮助评估项目、制定报价策略、生成客户方案。对内：评估 Claude 胜任度、云... | 10KB | [下载](freelance-advisor.zip) |

### 📎 其他

| Skill | 描述 | 大小 | 下载 |
|-------|------|------|------|
| closed-loop-thinking | 闭环思维框架——指导 LLM 在任何技能执行中建立"做了→验了→对了/改了"的反馈闭环。 核心问题：你怎么知道自己做对了？有验收标准就复用，没有就创造一个... | 3KB | [下载](closed-loop-thinking.zip) |
| customer-delivery-doc | 客户交付文档生成技能。AI做笔杆子不做作者——读取项目成果，采访用户确认重点，用用户口吻写客户看得懂的交付说明书。 触发词：交付说明书、写交付文档、客户说... | 5KB | [下载](customer-delivery-doc.zip) |
| delivery-quality-gate | Cross-deliverable customer handoff quality gate. Use before any client demo o... | 3KB | [下载](delivery-quality-gate.zip) |
| nanobanana-ppt-skills | 基于 AI 自动生成高质量 PPT 图片和视频，支持智能转场和交互式播放。 | 2.6MB | [下载](nanobanana-ppt-skills.zip) |
| project-handoff-closedloop | Prompt-led project cleanup and customer handoff workflow. Use when a project ... | 3KB | [下载](project-handoff-closedloop.zip) |
| remotion | Best practices for Remotion - Video creation in React | 47KB | [下载](remotion.zip) |

---

*最后更新: 2026-02-24 01:18:51*
