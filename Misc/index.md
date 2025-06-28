---
title: "Topics"
type: "folder-index"
category: "Topics"
tags: [topics]
---

# Topics

## 📄 Notes
```dataview
table file.name as "Note", file.mtime as "Last Modified"
from "Topics"
where file.name != "index"
sort file.mtime desc
```
