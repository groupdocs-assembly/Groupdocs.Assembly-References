---
title: first_row_contains_column_names property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The flag indicating whether column names are obtained from the first extracted row of a document table."
type: docs
url: /python-net/groupdocs.assembly.data/documenttableoptions/first_row_contains_column_names/
is_root: false
weight: 2010
---


## first_row_contains_column_names property

The flag indicating whether column names are obtained from the first extracted row of a document table. Defaults to False.

If column names are not set to be obtained from the first extracted row of a document table, default column names are used instead. For spreadsheet file formats, default column names are A, B, C, ... Z, AA, AB, and so on. For other file formats, default column names are Column1, Column2, Column3, and so on.

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
* class [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions/)
