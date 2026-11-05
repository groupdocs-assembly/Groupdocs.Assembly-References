---
title: name property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The name of this column used to access the column's data in a template document passed to DocumentAssembler."
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecolumn/name/
is_root: false
weight: 2030
---


## name property

The name of this column used to access the column's data in a template document passed to [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/).

If the column's name is read from a document (see [`DocumentTableOptions.first_row_contains_column_names`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions/first_row_contains_column_names/)), the name is automatically corrected so that it is valid. However, if the column's name is set manually through this property and the name is invalid, an exception is thrown.

The column's name is considered to be valid if the following conditions are met:
- The name is not empty.
- The name's first character is a letter or underscore.
- The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
- The corresponding [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/) object does not contain a [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn/) instance with the same name.

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
* class [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn/)
