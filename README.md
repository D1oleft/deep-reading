# 📚 Deep Reading

<p align="center">
  <strong>一键吃透一本书的 Claude Code Skill</strong>
</p>

<p align="center">
  <a href="https://github.com/D1oleft/deep-reading/stargazers"><img src="https://img.shields.io/github/stars/D1oleft/deep-reading?style=social" alt="Stars"></a>
  <a href="https://github.com/D1oleft/deep-reading/issues"><img src="https://img.shields.io/github/issues/D1oleft/deep-reading" alt="Issues"></a>
  <a href="https://github.com/D1oleft/deep-reading/blob/main/LICENSE"><img src="https://img.shields.io/github/license/D1oleft/deep-reading" alt="License"></a>
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-blue" alt="Claude Code Skill">
  <img src="https://img.shields.io/badge/Version-4.0.0-green" alt="Version">
</p>

---

## 🤔 这是什么？

一个 Claude Code / MiMo Code 的 Skill，让你用 AI 高效阅读书籍。

**核心能力**：发一本书的内容 → 自动扫描 → 智能跳读 → 拆解核心章节 → 生成知识卡片 → 导出笔记 → 定期复盘

## ⚡ 效果对比

| | 普通阅读 | 用 Deep Reading |
|---|---|---|
| 读完一本 300 页的书 | 6-8 小时 | 30 分钟 |
| 理解深度 | 看过 ≠ 理解 | 苏格拉底质询检验 |
| 知识留存 | 1 周后忘 80% | 知识卡片 + 定期复盘 |
| 跨书连接 | 手动整理 | 自动求同存异 |
| 输出 | 无 | 结构化笔记 + 行动清单 |
| 笔记管理 | 散落各处 | 自动导出到文件 |

## 🚀 快速开始

### 安装

```bash
# 方法 1：克隆仓库
git clone https://github.com/D1oleft/deep-reading.git
cp -r deep-reading/.claude/skills/deep-reading/ ~/.claude/skills/deep-reading/

# 方法 2：直接下载 SKILL.md 到项目目录
mkdir -p .claude/skills/deep-reading
curl -o .claude/skills/deep-reading/SKILL.md https://raw.githubusercontent.com/D1oleft/deep-reading/master/.claude/skills/deep-reading/SKILL.md
```

### 使用

```
# 一键读书（推荐）
/read 《思考，快与慢》

# 或者自然语言
"帮我读这本书"
"拆解一下这本书"

# 单步命令
/book-scan     # 全局扫描
/book-skip     # 智能跳读标记
/book-chapter  # 章节拆解
/book-quiz     # 苏格拉底质询
/book-feynman  # 费曼输出检验
/book-critique # 批判性审视
/book-card     # 知识卡片
/book-cross    # 跨书连接
/book-progress # 查看进度
/book-export   # 导出笔记
/book-review   # 定期复盘
```

## 📖 工作流程

```
发书 → 扫描 → 跳读标记 → 拆核心章 → 出卡片 → 导出笔记 → 完成
         ↓         ↓           ↓         ↓         ↓
      10秒     自动标记    每章10秒    自动生成    自动保存
```

**极简交互**：全程只需确认 2 次（扫描后 + 每章后）

## 🎯 三档阅读计划

| 模式 | 时间 | 流程 | 适合场景 |
|------|------|------|---------|
| ⚡ 速读 | 30 分钟 | 扫描 → 卡片 | 决定要不要读这本书 |
| 📖 精读 | 2 小时 | 扫描 → 拆核心章 → 质询 → 卡片 | 真正理解一本书 |
| 🔬 研究 | 不限时 | 全部 7 步 | 学术研究 / 写书评 |

## 📊 输出示例

### 知识卡片（极简版）

```
📚 《思考，快与慢》

一句话：人类有两套思维系统，快思考省力但常犯错，慢思考准确但懒惰。

框架：系统1/系统2 → 识别当前用哪个系统 → 判断是否需要切换

最反直觉：你以为你在理性思考，其实95%的决定是系统1自动做的。

立即行动：
1. 做重要决定前，问自己"这是系统1还是系统2在判断？"
2. 遇到复杂问题，强制启动系统2（写下来/画图）
3. 警惕锚定效应：先看价格前先自己估价

金句："懒惰是人类的天性，连思考也不例外。"
```

### 苏格拉底质询

```
📊 理解评分：18/25

事实 4/5 | 理解 4/5 | 应用 3/5 | 批判 4/5 | 迁移 3/5

等级：掌握
建议：加强应用和迁移能力，尝试用这个框架分析其他领域
```

## 🛠️ 特性

- ✅ **一键读书**：发内容，自动走完全流程
- ✅ **智能跳读**：自动区分骨架章 / 证据章 / 延伸章
- ✅ **三种输出**：极简（手机）/ 标准（电脑）/ 研究（论文）
- ✅ **进度追踪**：中途退出可恢复
- ✅ **原文锚定**：每个判断引用原文，不编造
- ✅ **苏格拉底检验**：主动检验理解程度
- ✅ **费曼输出**：用自己的话讲明白才算懂
- ✅ **跨书连接**：多本书求同存异
- ✅ **笔记导出**：自动保存到文件
- ✅ **定期复盘**：读完一周后自动复盘
- ✅ **阅读目的**：根据目的调整分析重点

## 📁 文件结构

```
deep-reading/
├── SKILL.md                    # 主入口
├── README.md                   # 本文件
├── flow.md                     # 流程详解
├── output-modes.md             # 输出模式说明
├── progress.md                 # 进度追踪说明
├── export.md                   # 笔记导出说明
├── review.md                   # 复盘机制说明
├── reading-plans.md            # 三档阅读计划
├── templates.md                # 输出模板参考
└── commands/
    ├── read.md                 # 一键读书
    ├── book-scan.md            # 全局扫描
    ├── book-skip.md            # 跳读标记
    ├── book-chapter.md         # 章节拆解
    ├── book-quiz.md            # 质询检验
    ├── book-feynman.md         # 费曼输出
    ├── book-critique.md        # 批判审视
    ├── book-card.md            # 知识卡片
    ├── book-cross.md           # 跨书连接
    ├── book-progress.md        # 进度查看
    ├── book-export.md          # 笔记导出
    └── book-review.md          # 定期复盘
```

## 🤝 支持的工具

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code)
- [MiMo Code](https://mimo.xiaomi.com/mimocode)
- 任何支持 Agent Skills 标准的 AI 工具

## 💡 为什么用这个而不是直接问 ChatGPT？

| | 直接问 AI | 用 Deep Reading |
|---|---|---|
| 流程 | 每次都要描述需求 | 自动走完全流程 |
| 深度 | AI 随便总结 | 7 步系统化分析 |
| 检验 | 看过就完了 | 苏格拉底质询检验 |
| 输出 | 一次性的 | 知识卡片可复用 |
| 进度 | 没有 | 中途可退出恢复 |
| 跳读 | 不会 | 自动标记骨架/水章 |
| 笔记 | 散落对话里 | 自动导出到文件 |
| 复盘 | 没有 | 定期复盘检验记忆 |

## 📜 License

MIT

---

<p align="center">
  如果这个项目帮到了你，请给个 ⭐ Star 支持一下！
</p>
