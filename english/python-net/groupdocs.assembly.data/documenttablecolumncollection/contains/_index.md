---
title: contains method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Returns a value indicating whether this collection contains a column with the specified name."
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecolumncollection/contains/
is_root: false
weight: 1010
---


## contains {#name}

Returns a value indicating whether this collection contains a column with the specified name.

```python
def contains(self, name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | The case-insensitive name of a column to look for. |

**Returns:** bool: True if the collection contains a column with the specified name; otherwise False.

## contains {#column}

Returns a value indicating whether this collection contains the specified column.

```python
def contains(self, column):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| column | `DocumentTableColumn` | A column to look for. |

**Returns:** bool: A value indicating whether this collection contains the specified column.

### Aliases

These names call `contains` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `contains_file` | `contains_file(name)` |
| `contains_string` | `contains_string(name)` |
| `contains_document_table_column` | `contains_document_table_column(column)` |

### See Also
* class [`DocumentTableColumnCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumncollection/)
