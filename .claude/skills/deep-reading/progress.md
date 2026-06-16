# 进度追踪

## 工作原理

系统在项目目录下创建 `.reading-progress.json` 文件，记录每本书的阅读进度。

## 进度文件格式

```json
{
  "思考快与慢": {
    "started": "2026-06-16",
    "last_activity": "2026-06-16T15:30:00",
    "mode": "standard",
    "steps": {
      "scan": { "status": "done", "timestamp": "2026-06-16T15:00:00" },
      "skip": { "status": "done", "timestamp": "2026-06-16T15:01:00" },
      "ch1": { "status": "done", "timestamp": "2026-06-16T15:05:00" },
      "ch3": { "status": "done", "timestamp": "2026-06-16T15:10:00" },
      "ch5": { "status": "pending" },
      "card": { "status": "pending" },
      "quiz": { "status": "pending" },
      "critique": { "status": "pending" }
    },
    "chapters": {
      "1": { "tag": "骨架", "title": "绪论" },
      "2": { "tag": "证据", "title": "案例分析" },
      "3": { "tag": "骨架", "title": "核心框架" }
    }
  }
}
```

## 进度命令

- `/book-progress` — 查看当前进度
- `/book-progress 《书名》` — 查看指定书的进度
- "继续读《书名》" — 从上次中断处继续

## 自动清理

- 完成的书籍进度保留 30 天
- 超过 30 天自动归档
- 用户可手动删除进度
