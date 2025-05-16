---
title: name property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecolumn/name/
is_root: false
weight: 50
---

## name property


Gets or sets the name of this column used to access the column's data in a template document passed to
[`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler).

### Remarks 


If the column's name is read from a document (see [`DocumentTableOptions.first_row_contains_column_names`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions#first_row_contains_column_names)),
the name is automatically corrected so that it to be valid. However, if the column's name is set manually through
this property and the name is invalid, an exception is thrown.




The column's name is considered to be valid, if the following conditions are met:


|
|
 |
 |
 |
 |
### Definition:
```python
@property
def name(self):
    ...
@name.setter
def name(self, value):
    ...
```

### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
* class [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn)
