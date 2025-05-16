---
title: index_in_document property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecolumn/index_in_document/
is_root: false
weight: 40
---

## index_in_document property


Gets the original zero-based index of the corresponding table column as per the source document.

### Remarks 


Depending on [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions) specified, this index may differ from the index of 
this [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn) instance within the column collection of the corresponding 
[`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) instance.
### Definition:
```python
@property
def index_in_document(self):
    ...
```

### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable)
* class [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn)
* class [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions)
