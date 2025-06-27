---
title: "Hub"
type: "folder-index"
category: "Hub"
tags: [hub]
---

# Hub

## 📄 Notes
```dataview
table file.name as "Note", file.mtime as "Last Modified"
from "Hub"
where file.name != "index"
sort file.mtime desc
```
