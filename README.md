# Deep Reading Skill v3.0

一键吃透一本书的 Claude Code Skill。

## 核心特性

- **一键读书**：发内容，自动走完全流程
- **智能跳读**：自动区分骨架章和水章
- **三种输出**：极简/标准/研究，自动切换
- **进度追踪**：中途退出可恢复
- **极简交互**：全程只需确认 2 次

## 安装

```bash
# 复制到全局目录
cp -r .claude/skills/deep-reading/ ~/.claude/skills/deep-reading/
```

## 使用

```bash
# 一键读书（推荐）
/read 《思考，快与慢》

# 或者自然语言
"帮我读这本书"
"拆解一下这本书"

# 单步命令
/book-scan    # 全局扫描
/book-skip    # 跳读标记
/book-chapter # 章节拆解
/book-quiz    # 质询检验
/book-feynman # 费曼输出
/book-critique # 批判审视
/book-card    # 知识卡片
/book-cross   # 跨书连接
/book-progress # 查看进度
```

## 文件结构

```
deep-reading/
├── SKILL.md                    # 主入口
├── README.md                   # 本文件
├── flow.md                     # 流程详解
├── output-modes.md             # 输出模式说明
├── progress.md                 # 进度追踪说明
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
    └── book-progress.md        # 进度查看
```

## v3.0 改进

- 一键读书模式，全自动流程
- 智能跳读，自动标记骨架/证据/延伸章节
- 三种输出模式（极简/标准/研究）自动切换
- 进度追踪，中途退出可恢复
- 极简交互，全程只需确认 2 次
- 微信场景优化，极简模式 3-5 行输出

## License

MIT
