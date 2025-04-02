---
tags:
  - journal
---
```dataview
table without id link(file.link, aliases[1]) as Study, summary as Summary
where contains(journal, "{{title}}")
```
