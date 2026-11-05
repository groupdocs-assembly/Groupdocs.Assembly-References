---
title: index_of method
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Returns the zero-based index of a column with the specified name, or -1 if the column does not exist in this collection."
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecolumncollection/index_of/
is_root: false
weight: 1040
---


## index_of {#name}

Returns the zero-based index of a column with the specified name, or -1 if the column does not exist in this collection.

```python
def index_of(self, name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| name | `str` | The case-insensitive name of a column to find. |

**Returns:** int: The zero-based index of a column with the specified name, or -1 if the column does not exist in this collection.

## index_of {#column}

Returns the zero-based index of the specified column within this collection, or -1 if the column does not exist.

```python
def index_of(self, column):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| column | `DocumentTableColumn` | A column to find. |

**Returns:** int: The zero-based index of the specified column, or -1 if the column does not exist in this collection.

### Aliases

These names call `index_of` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `index_of_file` | `index_of_file(name)` |
| `index_of_string` | `index_of_string(name)` |
| `index_of_document_table_column` | `index_of_document_table_column(column)` |

### See Also
* class [`DocumentTableColumnCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumncollection/)
