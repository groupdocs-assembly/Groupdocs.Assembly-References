---
title: index_in_document property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The original zero-based index of the corresponding table in the source document."
type: docs
url: /python-net/groupdocs.assembly.data/documenttable/index_in_document/
is_root: false
weight: 2020
---


## index_in_document property

The original zero-based index of the corresponding table in the source document.

Depending on a [`IDocumentTableLoadHandler`](/assembly/python-net/groupdocs.assembly.data/idocumenttableloadhandler/) implementation provided, this index may differ from the index of this [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/) instance within the table collection of the corresponding [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset/) instance, if any.

### Definition:
```python
@property
def index_in_document(self):
    ...
```

### See Also
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/)
