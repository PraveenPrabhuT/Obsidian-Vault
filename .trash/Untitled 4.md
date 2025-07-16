<%* 
  let title = tp.file.title  
  if (title.startsWith("Untitled")) {  
title = await tp.system.prompt("Title");  
await tp.file.rename(title);  
  }

  
  tR += "---"
%>
url:
tags:
creation date: <% tp.date.now("YYYY-MM-DD") %>
modification date: <% tp.file.last_modified_date("YYYY-MM-DD") %>
---
```table-of-contents
title: Index
hideWhenEmpty: true
style: nestedOrderedList
```



