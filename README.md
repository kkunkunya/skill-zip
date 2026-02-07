# 🧰 Skill ZIP Repository

Claude Code / Codex CLI / Gemini CLI 技能集中仓库。每个 skill 独立 ZIP 打包，按需下载安装。

> **最后同步**: 2026-02-07 | **技能总数**: 30

## 🚀 快速安装

```bash
# 方法1: 一行命令安装指定技能
curl -L "https://github.com/kkunkunya/skill-zip/raw/main/<skill-name>.zip" -o /tmp/s.zip && unzip -o /tmp/s.zip -d ~/.claude/skills/ && rm /tmp/s.zip

# 方法2: 使用下载脚本（如已安装 skill-zip-sync）
python3 ~/.claude/skills/skill-zip-sync/scripts/download_skill.py <skill-name>

# 方法3: 批量安装所有技能
for f in *.zip; do unzip -o "$f" -d ~/.claude/skills/; done
```

## 📦 技能分类索引

### 🌐 网页抓取
| 技能 | 说明 | 下载 |
|------|------|------|
| firecrawl | Web 抓取/搜索/调研首选工具（LLM优化输出） | [下载](firecrawl.zip) |

### 📄 文档处理
| 技能 | 说明 | 下载 |
|------|------|------|
| document-suite | DOCX/XLSX/PDF/PPTX 创建/编辑/提取 | [下载](document-suite.zip) |
| mineru-transfer | PDF/DOCX/PPT/图片 → Markdown（VLM高质量OCR） | [下载](mineru-transfer.zip) |

### 🔬 科研工具
| 技能 | 说明 | 下载 |
|------|------|------|
| academic-research-skills | 34子技能科研全栈（写作/可视化/文献/统计/生物信息） | [下载](academic-research-skills.zip) |
| library-researcher | 浏览器自动化检索下载PDF（需VPN） | [下载](library-researcher.zip) |
| paper-composer | 论文写作（分析→构思→撰写→反思，Opus模型） | [下载](paper-composer.zip) |
| ai-deweight | AI内容降重/论文降重 | [下载](ai-deweight.zip) |
| multi-model-collaborator | 多AI协作验证（Codex/Gemini集成） | [下载](multi-model-collaborator.zip) |

### 🎨 可视化与多媒体
| 技能 | 说明 | 下载 |
|------|------|------|
| image-generator | Gemini图像生成（含学术图表模式） | [下载](image-generator.zip) |
| ui-ux-pro-max | UI/UX设计智能（50风格+21配色+9技术栈） | [下载](ui-ux-pro-max.zip) |
| video-wrapper | 访谈视频综艺特效（花字/卡片/人物条，4种主题） | [下载](video-wrapper.zip) |

### 📝 知识管理
| 技能 | 说明 | 下载 |
|------|------|------|
| notebooklm | Google NotebookLM 完整API（播客/笔记本） | [下载](notebooklm.zip) |

### 🔄 工作流
| 技能 | 说明 | 下载 |
|------|------|------|
| req-project-dev-draft | 期望驱动开发（7阶段完整工作流） | [下载](req-project-dev-draft.zip) |
| test-driven-development | TDD方法论（红→绿→重构） | [下载](test-driven-development.zip) |
| systematic-debugging | 系统化调试（根因→模式→假设→修复） | [下载](systematic-debugging.zip) |
| best-practices-lookup | 方案设计前查询最佳实践 | [下载](best-practices-lookup.zip) |
| find-skills | 技能发现与安装 | [下载](find-skills.zip) |
| verification-before-completion | 完成前强制验证（证据驱动） | [下载](verification-before-completion.zip) |
| project-zip | 项目智能打包（含环境指南） | [下载](project-zip.zip) |
| github-uploader | 一键上传项目到GitHub | [下载](github-uploader.zip) |
| github-project-manager | GitHub全生命周期管理（初始化+Agent锁定+同步） | [下载](github-project-manager.zip) |

### ⚙️ 开发环境
| 技能 | 说明 | 下载 |
|------|------|------|
| threejs-suite | Three.js 3D全栈技能包（10子技能按需加载） | [下载](threejs-suite.zip) |
| autodl-deployer | AutoDL GPU云部署（迁移+一键脚本+国内源） | [下载](autodl-deployer.zip) |
| simulink-model-builder | MATLAB Simulink模型构建（跨版本兼容） | [下载](simulink-model-builder.zip) |
| dify-workflow-builder | Dify智能体工作流构建 | [下载](dify-workflow-builder.zip) |

### 🛠️ 系统管理
| 技能 | 说明 | 下载 |
|------|------|------|
| skill-creator | 技能创建指南 | [下载](skill-creator.zip) |
| skill-zip-sync | 技能打包同步到GitHub | [下载](skill-zip-sync.zip) |
| config-migrator | 配置迁移到Codex/Gemini CLI | [下载](config-migrator.zip) |
| hooks-manager | Claude Code Hooks管理 | [下载](hooks-manager.zip) |
| claude-md-maintainer | CLAUDE.md维护规范 | [下载](claude-md-maintainer.zip) |

## 🔧 同步说明

本仓库由 `skill-zip-sync` 技能自动维护：

```bash
# 全量同步（从本地到GitHub）
python3 ~/.claude/skills/skill-zip-sync/scripts/sync_skills.py

# 查看远程可用技能
python3 ~/.claude/skills/skill-zip-sync/scripts/download_skill.py --list

# 下载指定技能到本地
python3 ~/.claude/skills/skill-zip-sync/scripts/download_skill.py <skill-name>
```

## 📊 技能包大小一览

| 分类 | 最大技能 | 大小 |
|------|---------|------|
| 科研 | academic-research-skills | ~22MB |
| 文档 | document-suite | ~135KB |
| 可视化 | ui-ux-pro-max | ~114KB |
| 视频 | video-wrapper | ~74KB |
| 开发 | skill-creator | ~62KB |
| 3D | threejs-suite | ~43KB |

---

*自动生成 by [skill-zip-sync](skill-zip-sync.zip) | 兼容 Claude Code / Codex CLI / Gemini CLI*
