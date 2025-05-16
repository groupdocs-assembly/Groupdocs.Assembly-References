---
title: DocumentTable class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttable/
is_root: false
weight: 30
---

## DocumentTable class

Provides access to data of a single table (or spreadsheet) located in an external document to be used while 
assembling a document.



The DocumentTable type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttable/__init__/#str-int) | Creates a new instance of this class using default [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions). |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttable/__init__/#str-int-groupdocs.assembly.data.DocumentTableOptions) | Creates a new instance of this class. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttable/__init__/#io.RawIOBase-int) | Creates a new instance of this class using default [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions). |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttable/__init__/#io.RawIOBase-int-groupdocs.assembly.data.DocumentTableOptions) | Creates a new instance of this class. |


### Properties
| Property | Description |
| :- | :- |
| [name](/assembly/python-net/groupdocs.assembly.data/documenttable/name) | Gets or sets the name of this table used to access the table's data in a template document passed to<br/>[`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler). |
| [index_in_document](/assembly/python-net/groupdocs.assembly.data/documenttable/index_in_document) | Gets the original zero-based index of the corresponding table as per the source document. |
| [columns](/assembly/python-net/groupdocs.assembly.data/documenttable/columns) | Gets the collection of [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn) objects representing columns of <br/>the corresponding table. |



### Remarks 


For documents of Spreadsheet file formats, a [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) instance represents a single sheet.
For documents of other file formats, a [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) instance represents a single table.




To access data of the corresponding table while assembling a document, pass an instance of this class as 
a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler).
overloads.




In template documents, a [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) instance should be treated in the same way as if it was
a DataTable instance. See template syntax reference for more information.

### See Also
* module [`groupdocs.assembly.data`](..)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable)
* class [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn)
* class [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions)
