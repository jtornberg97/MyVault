---
title: "Resources"
type: "folder-index"
category: "Resources"
tags: [resources]
---

# Resources

## 📄 Notes
```dataview
table file.name as "Note", file.mtime as "Last Modified"
from "Resources"
where file.name != "index"
sort file.mtime desc
```
