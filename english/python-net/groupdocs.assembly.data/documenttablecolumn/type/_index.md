---
title: type property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecolumn/type/
is_root: false
weight: 60
---

## type property


Gets or sets the type of cell values in this column.

### Remarks 


For documents of non-Spreadsheet file formats, the initial type is always automatically determined 
as string. For documents of Spreadsheet file formats, the initial type is automatically determined 
depending on corresponding cell values.




If cells of a particular Spreadsheet column contain values of different types, then the column's 
initial type is also automatically determined as string.
### Definition:
```python
@property
def type(self):
    ...
@type.setter
def type(self, value):
    ...
```

### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn)
