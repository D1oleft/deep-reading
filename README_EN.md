<div align="center">

# 📚 Deep Reading Skill

**AI-Powered Deep Reading System · Master Books, Don't Just Read Them**

![Version](https://img.shields.io/badge/version-4.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Claude%20Code-purple)
![Stars](https://img.shields.io/github/stars/D1oleft/deep-reading?style=social)

English | [中文](README.md)

</div>

---

## 🎯 One-Line Pitch

> **Other tools are "reading assistants" — they compress books for you**
> **We are a "learning system" — we help you master them**

<div align="center">

```
📖 Input a book
    ↓
🔍 Smart Scan → Find core chapters
    ↓
📝 Chapter Breakdown → Extract key points
    ↓
🃏 Generate Cards → Easy review
    ↓
📊 Quiz Test → Verify understanding
    ↓
🎯 Feynman Output → Can you explain it?
    ↓
🔄 Periodic Review → True internalization
```

</div>

---

## ✨ Core Features

<table>
<tr>
<td width="50%">

### 📖 Deep Breakdown
- Identify core chapters, skip fluff
- Extract 3-5 key points per chapter
- Preserve original wisdom

</td>
<td width="50%">

### 🃏 Knowledge Cards
- Auto-generate Anki-friendly cards
- Spaced repetition for memory
- Export to CSV format

</td>
</tr>
<tr>
<td width="50%">

### 📊 Quiz Testing
- 3-5 comprehension questions
- Tests understanding, not memorization
- Immediate feedback

</td>
<td width="50%">

### 🎯 Feynman Output
- Explain in simple terms
- Verify true understanding
- "If you can't explain it simply, you don't understand it"

</td>
</tr>
<tr>
<td width="50%">

### 📝 Note Export
- One-click export to `~/笔记/`
- Markdown format, universal
- Batch export supported

</td>
<td width="50%">

### 🔄 Periodic Review
- 1-day quick recall
- 1-week deep review (scored)
- 1-month application

</td>
</tr>
</table>

---

## 🚀 Quick Start

### Install (30 seconds)

```bash
cd ~/.claude/skills
git clone https://github.com/D1oleft/deep-reading.git
```

### Usage

```bash
# Method 1: Send content directly
"Help me read this book: [paste content]"

# Method 2: Use commands
/deep-reading:read

# Check progress
/deep-reading:book-progress

# Export notes
/deep-reading:book-export

# Periodic review
/deep-reading:book-review

# Cross-book comparison
/deep-reading:book-cross
```

---

## 📊 Complete Workflow

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│                    📚 Deep Reading Flow                     │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ┌──────────┐    ┌──────────┐    ┌──────────┐              │
│  │ Step 0   │───→│ Step 1   │───→│ Step 2   │              │
│  │ Get      │    │ Quick    │    │ Skim     │              │
│  │ Content  │    │ Scan     │    │ Confirm  │              │
│  └──────────┘    └──────────┘    └──────────┘              │
│                                       │                     │
│                                       ▼                     │
│  ┌──────────┐    ┌──────────┐    ┌──────────┐              │
│  │ Step 5   │←───│ Step 4   │←───│ Step 3   │              │
│  │ Export   │    │ Generate │    │ Chapter  │              │
│  │ Notes    │    │ Cards    │    │ Breakdown│              │
│  └──────────┘    └──────────┘    └──────────┘              │
│       │                                                     │
│       ▼                                                     │
│  ┌──────────┐    ┌──────────┐                              │
│  │ Done!    │───→│ Periodic │                              │
│  │          │    │ Review   │                              │
│  └──────────┘    └──────────┘                              │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

</div>

---

## ⏱️ Time Estimates

| Book Size | Time | Example |
|-----------|------|---------|
| 📄 Small (<50 pages) | 3 min | Blog posts, reports |
| 📕 Medium (50-200 pages) | 7 min | Regular books |
| 📚 Large (200+ pages) | 12 min | Classic works |

---

## 🆚 Why Choose Us?

| Feature | Deep Reading | Others |
|---------|-------------|--------|
| Learning Loop | ✅ Read→Test→Review→Apply | ❌ Analysis only |
| Zero Dependencies | ✅ Pure Markdown | ❌ Requires Python/Node |
| Chinese Optimized | ✅ Native Chinese | ⚠️ Generic |
| Knowledge Cards | ✅ Anki Compatible | ❌ None |
| Periodic Review | ✅ Scored Tracking | ❌ None |
| Feynman Test | ✅ Explain = Understand | ❌ None |

---

## 💡 Use Cases

### 📖 Reading Classic Works
```
"Help me read 'The Prince', I want to truly understand it"
→ Auto-identifies 177 teachings
→ Chapter-by-chapter breakdown
→ Quiz to test understanding
→ Feynman output to verify mastery
```

### 📄 Analyzing Long Reports
```
"This 30,000-word industry report, help me extract key points"
→ Quick scan for core data
→ Generate key point cards
→ Export notes for review
```

### 🎓 Learning专业知识
```
"This textbook is too thick, help me learn efficiently"
→ Skip known content
→ Focus on core difficulties
→ Quiz to test learning效果
```

---

## 📁 Output Example

### Generated Note Structure
```
~/笔记/
└── The_Prince_Reading_Notes.md
    ├── 📖 Book Info
    ├── 🎯 Key Points (by chapter)
    ├── 🃏 Knowledge Cards (Anki-compatible)
    ├── 📊 Quiz Questions & Answers
    └── 💭 Personal Reflections
```

### Quiz Example
```
Q1: According to Machiavelli, should a prince be loved or feared?
A. Can only choose one, choose fear
B. Best to have both, but if must choose, choose fear
C. Love is more important than fear
D. Fear is better than love, but must avoid being hated

Answer: D
Analysis: Chapter 17 core idea - love and fear can coexist, 
the key is avoiding hatred.
```

---

## 🔧 Commands

| Command | Function |
|---------|----------|
| `/deep-reading:read` | Start reading |
| `/deep-reading:book-progress` | Check progress |
| `/deep-reading:book-export` | Export notes |
| `/deep-reading:book-review` | Periodic review |
| `/deep-reading:book-cross` | Cross-book comparison |

---

## 🌟 User Feedback

> "I used to forget what I read. With quizzes and reviews, I actually remember now."
> — User Feedback

> "The Feynman output is so useful. If you can explain it clearly, you truly understand it."
> — Learner

---

## 📈 Project Status

- ⭐ If you find it useful, please give a Star!
- 🐛 Found an issue? Open an Issue
- 💡 Have suggestions? Welcome PRs

---

## 📜 License

MIT License - Free to use, free to modify

---

<div align="center">

**📚 Reading isn't hard. Mastering is.**

[Quick Start](#quick-start) · [View Docs](flow.md) · [中文](README.md)

</div>
