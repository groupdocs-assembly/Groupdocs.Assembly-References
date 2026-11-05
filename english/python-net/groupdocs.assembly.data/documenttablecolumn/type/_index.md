---
title: type property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The type of cell values in this column."
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecolumn/type/
is_root: false
weight: 2040
---


## type property

The type of cell values in this column.

For documents of non‑Spreadsheet file formats, the initial type is always automatically determined as `str`. For documents of Spreadsheet file formats, the initial type is automatically determined depending on corresponding cell values.

If cells of a particular Spreadsheet column contain values of different types, then the column's initial type is also automatically determined as `str`.

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
* class [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn/)
