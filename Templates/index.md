---
title: "Templates"
type: "folder-index"
category: "Templates"
tags: [templates]
---

# Templates

## 📄 Notes
```dataview
table file.name as "Note", file.mtime as "Last Modified"
from "Templates"
where file.name != "index"
sort file.mtime desc
```
