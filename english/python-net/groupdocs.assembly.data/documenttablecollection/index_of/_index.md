---
title: index_of method
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecollection/index_of/
is_root: false
weight: 30
---

## index_of {#str}

Returns the index of a table with the specified name within this collection.


### Returns 


The zero-based index of a table with the specified name, or -1 if the table does not exist in this collection.


```python
def index_of(self, name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| name | str | The case-insensitive name of a table to find. |


## index_of {#groupdocs.assembly.data.DocumentTable}

Returns the index of the specified table within this collection.


### Returns 


The zero-based index of the specified table, or -1 if the table does not exist in this collection.


```python
def index_of(self, table):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| table | [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) | A table to find. |



### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`DocumentTableCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablecollection)
