---
title: add method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Creates a DocumentTableRelation object for the specified parent and child columns and adds it to the collection."
type: docs
url: /python-net/groupdocs.assembly.data/documenttablerelationcollection/add/
is_root: false
weight: 1010
---


## add {#parent_column-child_column}

Creates a [`DocumentTableRelation`](/assembly/python-net/groupdocs.assembly.data/documenttablerelation/) object for the specified parent and child columns and adds it to the collection.

```python
def add(self, parent_column, child_column):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| parent_column | `DocumentTableColumn` | The parent column of the relation. |
| child_column | `DocumentTableColumn` | The child column of the relation. |

**Returns:** The created `DocumentTableRelation`.

### Aliases

These names call `add` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `add_document_table_column` | `add_document_table_column(parent_column, child_column)` |

### See Also
* class [`DocumentTableRelationCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablerelationcollection/)
