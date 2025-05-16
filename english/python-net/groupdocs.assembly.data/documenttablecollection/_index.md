---
title: DocumentTableCollection class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttablecollection/
is_root: false
weight: 40
---

## DocumentTableCollection class

Represents a read-only collection of [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) objects of a particular [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset) 
instance.



The DocumentTableCollection type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [count](/assembly/python-net/groupdocs.assembly.data/documenttablecollection/count) | Gets the total number of [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) objects in the collection. |



Gets a [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) instance from the collection at the specified index.
### Indexer
| Name | Description |
| :- | :- |
| [index] | The zero-based index of the table to return. |


### Methods
| Method | Description |
| :- | :- |
| [contains](/assembly/python-net/groupdocs.assembly.data/documenttablecollection/contains/#str) | Returns a value indicating whether this collection contains a table with the specified name. |
| [contains](/assembly/python-net/groupdocs.assembly.data/documenttablecollection/contains/#groupdocs.assembly.data.DocumentTable) | Returns a value indicating whether this collection contains the specified table. |
| [index_of](/assembly/python-net/groupdocs.assembly.data/documenttablecollection/index_of/#str) | Returns the index of a table with the specified name within this collection. |
| [index_of](/assembly/python-net/groupdocs.assembly.data/documenttablecollection/index_of/#groupdocs.assembly.data.DocumentTable) | Returns the index of the specified table within this collection. |



### Remarks 


The collection is filled automatically while loading the corresponding tables from a document and can not be modified.
However, properties of [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) objects contained within the collection can be modified.

### See Also
* module [`groupdocs.assembly.data`](..)
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable)
* class [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset)
