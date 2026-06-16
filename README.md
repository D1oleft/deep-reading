# Deep Reading Skill v2.0

7步吃透一本书的 Claude Code Skill。

## 安装

```bash
# 方法1：复制到全局目录（所有项目可用）
cp -r deep-reading/.claude/skills/deep-reading/ ~/.claude/skills/deep-reading/

# 方法2：复制到项目目录
cp -r deep-reading/.claude/skills/deep-reading/ your-project/.claude/skills/deep-reading/
```

## 使用

```bash
# 全局扫描
/book-scan 《思考，快与慢》

# 逐章拆解
/book-chapter 第3章：惰性思维与冲动

# 苏格拉底质询
/book-quiz 《思考，快与慢》第3章

# 费曼输出
/book-feynman 系统1和系统2

# 批判性审视
/book-critique 《思考，快与慢》

# 知识卡片
/book-card 《思考，快与慢》

# 跨书连接
/book-cross 《思考，快与慢》《穷查理宝典》《噪声》
```

## 文件结构

```
deep-reading/
├── SKILL.md                    # 主入口（必需）
├── README.md                   # 本文件
├── reading-plans.md            # 三档阅读计划详情
├── templates.md                # 各命令输出模板参考
└── commands/
    ├── book-scan.md            # 全局扫描
    ├── book-chapter.md         # 逐章拆解
    ├── book-quiz.md            # 苏格拉底质询
    ├── book-feynman.md         # 费曼输出
    ├── book-critique.md        # 批判性审视
    ├── book-card.md            # 知识卡片
    └── book-cross.md           # 跨书连接
```

## v2.0 改进

- 适配 Claude Code 官方 skill 格式（SKILL.md + frontmatter）
- 每个命令增加前置检查和边界情况处理
- 丰富输出模板和格式规范
- 增加质量自检机制
- 参考 Superpowers（229k⭐）的最佳实践
- 增加支持文件（阅读计划、输出模板）

## 设计原则

1. **原文锚定**：每个判断必须引用原文
2. **主动检验**：用苏格拉底质询反向检验
3. **输出倒逼**：能用自己的话讲明白才算理解
4. **批判思维**：每本书都要找到弱点
5. **知识复利**：读完的书要产生连接

## License

MIT
