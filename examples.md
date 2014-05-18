---
layout: default
title: Examples
weight: 99
---

##Sortable Sidebar

**Requirements**

- Config: [sidebar config](https://github.com/Jako/multiTV/blob/master/assets/tvs/multitv/configs/sidebar.config.inc.php)
- Template Variable: sidebar
- Extras: [Quill](http://modx.com/extras/package/quill)

**Usage**

```
[!Ditto?
&documents=`[[multiTV? &tvName=`sidebar`]]`
&outputSeparator=`,`
&extenders=`@FILE assets/tvs/multitv/dittoExtender/customsort.extender.inc.php`
&tpl=`…`!]
```
