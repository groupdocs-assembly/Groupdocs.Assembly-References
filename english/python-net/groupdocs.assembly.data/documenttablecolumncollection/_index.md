---
title: DocumentTableColumnCollection class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecolumncollection/
is_root: false
weight: 60
---

## DocumentTableColumnCollection class

Represents a read-only collection of [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn) objects of a particular 
[`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) instance.



The DocumentTableColumnCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [count](/assembly/python-net/groupdocs.assembly.data/documenttablecolumncollection/count) | Gets the total number of [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn) objects in the collection. |



Gets a [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn) instance from the collection at the specified index.
### Indexer
| Name | Description |
| :- | :- |
| [index] | The zero-based index of the column to return. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/assembly/python-net/groupdocs.assembly.data/documenttablecolumncollection/contains/#str) | Returns a value indicating whether this collection contains a column with the specified name. |
| [contains](/assembly/python-net/groupdocs.assembly.data/documenttablecolumncollection/contains/#groupdocs.assembly.data.DocumentTableColumn) | Returns a value indicating whether this collection contains the specified column. |
| [index_of](/assembly/python-net/groupdocs.assembly.data/documenttablecolumncollection/index_of/#str) | Returns the index of a column with the specified name within this collection. |
| [index_of](/assembly/python-net/groupdocs.assembly.data/documenttablecolumncollection/index_of/#groupdocs.assembly.data.DocumentTableColumn) | Returns the index of the specified column within this collection. |



### Remarks 


The collection is filled automatically while loading the corresponding table from a document and can not be modified.
However, properties of [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn) objects contained within the collection can be modified.

### See Also
* module [`groupdocs.assembly.data`](..)
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable)
* class [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn)
