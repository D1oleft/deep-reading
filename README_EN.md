# 📚 Deep Reading

<p align="center">
  <strong>Read and truly understand any book with AI — a Claude Code Skill</strong>
</p>

<p align="center">
  <a href="https://github.com/D1oleft/deep-reading/stargazers"><img src="https://img.shields.io/github/stars/D1oleft/deep-reading?style=social" alt="Stars"></a>
  <a href="https://github.com/D1oleft/deep-reading/issues"><img src="https://img.shields.io/github/issues/D1oleft/deep-reading" alt="Issues"></a>
  <a href="https://github.com/D1oleft/deep-reading/blob/main/LICENSE"><img src="https://img.shields.io/github/license/D1oleft/deep-reading" alt="License"></a>
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-blue" alt="Claude Code Skill">
</p>

<p align="center">
  <a href="README.md">中文文档</a> | English
</p>

---

## What is this?

A Claude Code / MiMo Code Skill that helps you read books efficiently with AI.

**Core ability**: Send book content → Auto scan → Smart skimming → Analyze key chapters → Generate knowledge cards

## Quick Comparison

| | Regular Reading | With Deep Reading |
|---|---|---|
| Read a 300-page book | 6-8 hours | 30 minutes |
| Understanding depth | Read ≠ Understand | Socratic quiz verification |
| Knowledge retention | Forget 80% in 1 week | Knowledge cards for review |
| Cross-book connections | Manual | Automatic |
| Output | Nothing | Structured notes + action items |

## Quick Start

### Install

```bash
git clone https://github.com/D1oleft/deep-reading.git
cp -r deep-reading/.claude/skills/deep-reading/ ~/.claude/skills/deep-reading/
```

### Use

```
# One-click reading (recommended)
/read "Thinking, Fast and Slow"

# Or natural language
"Help me read this book"

# Individual commands
/book-scan     # Full scan
/book-skip     # Smart skimming marks
/book-chapter  # Chapter analysis
/book-quiz     # Socratic quiz
/book-feynman  # Feynman technique
/book-critique # Critical review
/book-card     # Knowledge card
/book-cross    # Cross-book analysis
/book-progress # Check progress
```

## Workflow

```
Send book → Scan → Mark chapters → Analyze key ones → Card → Done
```

Only 2 confirmations needed throughout the entire process.

## Features

- ✅ One-click reading — send content, auto-complete
- ✅ Smart skimming — auto-detect key vs filler chapters
- ✅ Three output modes — minimal / standard / research
- ✅ Progress tracking — resume where you left off
- ✅ Source-grounded — every claim references原文
- ✅ Socratic verification — actively test understanding
- ✅ Feynman technique — explain in your own words
- ✅ Cross-book synthesis — find patterns across books

## Supported Tools

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code)
- [MiMo Code](https://mimo.xiaomi.com/mimocode)
- Any AI tool supporting Agent Skills standard

## License

MIT

---

<p align="center">
  If this project helped you, please give it a ⭐ Star!
</p>
