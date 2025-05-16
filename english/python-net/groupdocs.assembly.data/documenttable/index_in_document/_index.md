---
title: index_in_document property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttable/index_in_document/
is_root: false
weight: 40
---

## index_in_document property


Gets the original zero-based index of the corresponding table as per the source document.

### Remarks 


Depending on an [`IDocumentTableLoadHandler`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler) implementation provided, this index may differ from 
the index of this [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) instance within the table collection of the corresponding 
[`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset) instance, if any.
### Definition:
```python
@property
def index_in_document(self):
    ...
```

### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable)
* class [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset)
* class [`IDocumentTableLoadHandler`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler)
