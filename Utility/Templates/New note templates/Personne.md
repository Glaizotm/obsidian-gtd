---
name: <% tp.file.title.replace('@', '') %>
tags: person
created: <% moment().format() %>
template_title: "👤"
template_destination_folder: 04 👤 People
---
# <% tp.file.title.replace('👤', '') %>



```dataviewjs
await dv.view("Scripts/Dataview/mentions-table", 3)
```

