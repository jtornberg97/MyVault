---
title: "Podcast"
type: "folder-index"
category: "Podcast"
tags: [podcast]
---

# Podcast

## 📄 Notes
```dataview
table file.name as "Note", file.mtime as "Last Modified"
from "Podcast"
where file.name != "index"
sort file.mtime desc
```
