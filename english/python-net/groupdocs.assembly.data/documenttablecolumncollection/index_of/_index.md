---
title: index_of method
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecolumncollection/index_of/
is_root: false
weight: 30
---

## index_of {#str}

Returns the index of a column with the specified name within this collection.


### Returns 


The zero-based index of a column with the specified name, or -1 if the column does not exist in this collection.


```python
def index_of(self, name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| name | str | The case-insensitive name of a column to find. |


## index_of {#groupdocs.assembly.data.DocumentTableColumn}

Returns the index of the specified column within this collection.


### Returns 


The zero-based index of the specified column, or -1 if the column does not exist in this collection.


```python
def index_of(self, column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| column | [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn) | A column to find. |



### See Also
* module [`groupdocs.assembly.data`](../../)
* class [`DocumentTableColumnCollection`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumncollection)
