---
title: index_of method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Returns the index of a table with the specified name within this collection."
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecollection/index_of/
is_root: false
weight: 1040
---


## index_of {#name}

Returns the index of a table with the specified name within this collection.

```python
def index_of(self, name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | The case-insensitive name of a table to find. |

**Returns:** int: The zero-based index of a table with the specified name, or -1 if the table does not exist in this collection.

## index_of {#table}

Returns the index of the specified table within this collection.

```python
def index_of(self, table):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| table | `DocumentTable` | A table to find. |

**Returns:** int: The zero-based index of the specified table, or -1 if the table does not exist in this collection.

### Aliases

These names call `index_of` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `index_of_file` | `index_of_file(name)` |
| `index_of_string` | `index_of_string(name)` |
| `index_of_document_table` | `index_of_document_table(table)` |

### See Also
* class [`DocumentTableCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablecollection/)
