---
title: contains method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Returns a value indicating whether this collection contains a table with the specified name."
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecollection/contains/
is_root: false
weight: 1010
---


## contains {#name}

Returns a value indicating whether this collection contains a table with the specified name.

```python
def contains(self, name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | The case-insensitive name of a table to look for. |

**Returns:** bool: True if the collection contains a table with the specified name; otherwise False.

## contains {#table}

Returns a value indicating whether this collection contains the specified table.

```python
def contains(self, table):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| table | `DocumentTable` | A table to look for. |

**Returns:** bool: A value indicating whether this collection contains the specified table.

### Aliases

These names call `contains` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `contains_file` | `contains_file(name)` |
| `contains_string` | `contains_string(name)` |
| `contains_document_table` | `contains_document_table(table)` |

### See Also
* class [`DocumentTableCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablecollection/)
