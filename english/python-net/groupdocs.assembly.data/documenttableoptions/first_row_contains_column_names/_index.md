---
title: first_row_contains_column_names property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttableoptions/first_row_contains_column_names/
is_root: false
weight: 30
---

## first_row_contains_column_names property


Gets or sets a value indicating whether column names are to be obtained from the first
extracted row of a document table. The default value is false.

### Remarks 


If column names are not set to be obtained from the first extracted row of a document table, 
default column names are used instead. For documents of Spreadsheet file formats, default 
column names are defined as A, B, C, ... Z, AA, AB, and so on. For documents of other 
file formats, default column names are defined as Column1, Column2, Column3, and so on.
### Definition:
```python
@property
def first_row_contains_column_names(self):
    ...
@first_row_contains_column_names.setter
def first_row_contains_column_names(self, value):
    ...
```

### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions)
