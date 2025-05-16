---
title: DocumentTableSet class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/documenttableset/
is_root: false
weight: 110
---

## DocumentTableSet class

Provides access to data of multiple tables (or spreadsheets) located in an external document to be used while 
assembling a document. Also, enables to define parent-child relations for the document tables thus simplifying
access to related data within template documents.



The DocumentTableSet type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttableset/__init__/#str) | Creates a new instance of this class loading all tables from a document using default <br/>[`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions). |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttableset/__init__/#str-groupdocs.assembly.data.IDocumentTableLoadHandler) | Creates a new instance of this class. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttableset/__init__/#io.RawIOBase) | Creates a new instance of this class loading all tables from a document using default <br/>[`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions). |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttableset/__init__/#io.RawIOBase-groupdocs.assembly.data.IDocumentTableLoadHandler) | Creates a new instance of this class. |


### Properties
| Property | Description |
| :- | :- |
| [tables](/assembly/python-net/groupdocs.assembly.data/documenttableset/tables) | Gets the collection of [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable) objects representing tables of this set. |
| [relations](/assembly/python-net/groupdocs.assembly.data/documenttableset/relations) | Gets the collection of parent-child relations defined for document tables of this set. |



### Remarks 


For documents of Spreadsheet file formats, a [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset) instance represents a set of sheets.
For documents of other file formats, a [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset) instance represents a set of tables.




To access data of the corresponding tables while assembling a document, pass an instance of this class as 
a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler).
overloads.




In template documents, a [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset) instance should be treated in the same way as if it was
a DataSet instance. See template syntax reference for more information.

### See Also
* module [`groupdocs.assembly.data`](..)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable)
* class [`DocumentTableOptions`](/assembly/python-net/groupdocs.assembly.data/documenttableoptions)
* class [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset)
