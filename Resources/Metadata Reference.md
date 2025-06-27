---
title: "Metadata Reference"
type: "guide"
tags: [metadata, reference, yaml]
---

# 🧾 Metadata Reference

A guide to YAML frontmatter fields used throughout the vault for filtering, organizing, and querying notes with Dataview.

---

## 🏷️ Common Fields

| Field      | Purpose                                       | Example                                       |
| ---------- | --------------------------------------------- | --------------------------------------------- |
| `type`     | Defines the kind of note                      | `literature-note`, `lecture-note`             |
| `category` | Major content area                            | `Judaism`, `Christianity`                     |
| `topic`    | Thematic tag                                  | `covenant`, `messiah`, `ethics`               |
| `tags`     | Freeform topic labels                         | `[theology, christology]`                     |
| `date`     | Created or studied                            | `2025-06-26`                                  |
| `field`    | For people or sources — area of expertise     | `New Testament`, `Rabbinics`                  |
| `lifespan` | For historical figures                        | `100 BCE – 40 CE`                             |
| `citekey`  | Reference code for Zotero/BibTeX              | `wright2013`                                  |
| `source`   | Where the note comes from (book, video, etc.) | `"Wright – Paul and the Faithfulness of God"` |

---

## ✅ Example YAML

```yaml
---
type: literature-note
title: "Jesus and the Victory of God"
author: "N.T. Wright"
source: "Book"
publication_date: "1996"
topic: "Christology"
category: "Christianity"
status: in-progress
tags: [wright, synoptic, christology]
date: 2025-06-26
citekey: wright1996
---
```
