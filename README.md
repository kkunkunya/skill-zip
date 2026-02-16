# Skill ZIP Repository

Claude Code Skills 压缩包仓库，每个 skill 独立打包，按需下载。

## 使用方法

### 方法1：直接下载
点击下方链接下载对应的 ZIP 文件，解压到 `~/.claude/skills/` 目录。

### 方法2：命令行下载
```bash
# 下载指定 skill
curl -L "https://github.com/kkunkunya/skill-zip/raw/main/<skill-name>.zip" -o <skill-name>.zip
unzip <skill-name>.zip -d ~/.claude/skills/
```

## 可用 Skills

| Skill | 描述 | 下载 |
|-------|------|------|
| 20-ml-paper-writing | Write publication-ready ML/AI papers for NeurIPS, ICML, ICLR... | [下载](20-ml-paper-writing.zip) |
| academic-research-skills | > | [下载](academic-research-skills.zip) |
| ai-deweight | Enhances academic writing originality and reduces AI detecti... | [下载](ai-deweight.zip) |
| ai-elements | Create new AI chat interface components for the ai-elements ... | [下载](ai-elements.zip) |
| autodl-deployer | AutoDL GPU云平台项目部署与迁移工具。默认交换路径：/root/autodl-fs/（上传下载都走这里，无dat... | [下载](autodl-deployer.zip) |
| baoyu-article-illustrator | Analyzes article structure, identifies positions requiring v... | [下载](baoyu-article-illustrator.zip) |
| baoyu-cover-image | Generates article cover images with 5 dimensions (type, pale... | [下载](baoyu-cover-image.zip) |
| baoyu-danger-x-to-markdown | Converts X (Twitter) tweets and articles to markdown with YA... | [下载](baoyu-danger-x-to-markdown.zip) |
| baoyu-format-markdown | Formats plain text or markdown files with frontmatter, title... | [下载](baoyu-format-markdown.zip) |
| baoyu-image-gen | AI image generation with OpenAI, Google and DashScope APIs. ... | [下载](baoyu-image-gen.zip) |
| baoyu-infographic | Generates professional infographics with 20 layout types and... | [下载](baoyu-infographic.zip) |
| baoyu-markdown-to-html | Converts Markdown to styled HTML with WeChat-compatible them... | [下载](baoyu-markdown-to-html.zip) |
| baoyu-post-to-wechat | Posts content to WeChat Official Account (微信公众号) via API or ... | [下载](baoyu-post-to-wechat.zip) |
| baoyu-post-to-x | Posts content and articles to X (Twitter). Supports regular ... | [下载](baoyu-post-to-x.zip) |
| baoyu-xhs-images | Generates Xiaohongshu (Little Red Book) infographic series w... | [下载](baoyu-xhs-images.zip) |
| best-practices-lookup | > | [下载](best-practices-lookup.zip) |
| claude-md-maintainer | CLAUDE.md 维护规范（添加工具/技能、修改规则、精简审计） | [下载](claude-md-maintainer.zip) |
| config-migrator | Migrates Claude Code configurations to Codex CLI with an AI-... | [下载](config-migrator.zip) |
| content-producer | > | [下载](content-producer.zip) |
| diary-companion | > | [下载](diary-companion.zip) |
| dify-workflow-builder | | | [下载](dify-workflow-builder.zip) |
| doc-coauthoring | Guide users through a structured workflow for co-authoring d... | [下载](doc-coauthoring.zip) |
| document-suite | Unified document processing for DOCX, XLSX, PDF, PPTX. Creat... | [下载](document-suite.zip) |
| find-skills | Helps users discover and install agent skills when they ask ... | [下载](find-skills.zip) |
| firecrawl | | | [下载](firecrawl.zip) |
| freelance-advisor | 学生项目及私单技术顾问（云GPU成本版）。以双重身份（对内参谋+对外合伙人）帮助评估项目、制定报价策略、生成客户方案。对... | [下载](freelance-advisor.zip) |
| github-project-manager | GitHub 项目全生命周期管理 v2：仓库初始化、README 美化、分支保护、元数据设置、质量评分、Agent 协调... | [下载](github-project-manager.zip) |
| github-uploader | Uploads current project to GitHub with one command. Automati... | [下载](github-uploader.zip) |
| hooks-manager | Manages Claude Code Hooks for creating, viewing, modifying, ... | [下载](hooks-manager.zip) |
| humanizer-skill | | | [下载](humanizer-skill.zip) |
| image-generator | > | [下载](image-generator.zip) |
| library-researcher | 学术文献搜索下载工具。确认VPN登录后，在学校发现系统批量检索下载，智能记录成功/失败文献。 | [下载](library-researcher.zip) |
| meigen-design | >- | [下载](meigen-design.zip) |
| mineru-transfer | MinerU 文档转换工具（基于 VLM 的高质量 OCR）。支持 PDF、DOCX、PPT、图片、HTML → Mar... | [下载](mineru-transfer.zip) |
| multi-model-collaborator | 多模型协作技能（Team 嵌套并行模式）。通过 Team 机制将 Codex 作为持久团队成员，支持双向通信、多轮追问、... | [下载](multi-model-collaborator.zip) |
| notebooklm | Complete API for Google NotebookLM - full programmatic acces... | [下载](notebooklm.zip) |
| paper-composer | | | [下载](paper-composer.zip) |
| playground | Creates interactive HTML playgrounds — self-contained single... | [下载](playground.zip) |
| project-zip | Intelligently compresses and packages projects into ZIP arch... | [下载](project-zip.zip) |
| req-project-dev-draft | > | [下载](req-project-dev-draft.zip) |
| results-driven-rl | 效果驱动的强化学习实验开发。优先保证训练收敛、结果好看、图表可用于论文，不深究实现细节。当用户需要：(1) 开发RL实验... | [下载](results-driven-rl.zip) |
| sci-hub-downloader | Sci-Hub文献PDF下载工具。使用Playwright浏览器MCP通过Sci-Hub镜像下载学术文献PDF，自动处理... | [下载](sci-hub-downloader.zip) |
| simulink-model-builder | Builds MATLAB Simulink models programmatically with cross-ve... | [下载](simulink-model-builder.zip) |
| skill-creator | Guide for creating effective skills. This skill should be us... | [下载](skill-creator.zip) |
| skill-zip-sync | 将 ~/.claude/skills/ 下的所有 skill 打包成独立 ZIP 并同步到 GitHub 仓库，支持按需... | [下载](skill-zip-sync.zip) |
| ssh-file-transfer | > | [下载](ssh-file-transfer.zip) |
| system-self-iterator | 系统进化引擎 ⚡ — 双入口（日记洞察 + 外部文章），通过三透镜深度分析驱动 Claude Code 系统持续进化。维... | [下载](system-self-iterator.zip) |
| systematic-debugging | Applies systematic debugging methodology when encountering b... | [下载](systematic-debugging.zip) |
| test-driven-development | > | [下载](test-driven-development.zip) |
| threejs-suite | Three.js 3D开发全栈技能包，涵盖场景搭建、几何体、材质、光照、纹理、动画、交互、模型加载、着色器、后处理。Us... | [下载](threejs-suite.zip) |
| ui-ux-pro-max | > | [下载](ui-ux-pro-max.zip) |
| vault-layer-manager | > | [下载](vault-layer-manager.zip) |
| verification-before-completion | Requires verification before claiming task completion, succe... | [下载](verification-before-completion.zip) |
| video-wrapper | 为访谈视频添加综艺特效（花字、卡片、人物条、章节标题等）。支持 4 种视觉主题，先分析字幕内容生成建议供用户审批，再渲染... | [下载](video-wrapper.zip) |

---

*最后更新: 2026-02-17 01:52:26*
