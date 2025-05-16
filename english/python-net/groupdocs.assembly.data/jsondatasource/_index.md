---
title: JsonDataSource class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/jsondatasource/
is_root: false
weight: 140
---

## JsonDataSource class

Provides access to data of a JSON file or stream to be used while assembling a document.



The JsonDataSource type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondatasource/__init__/#str) | Creates a new data source with data from a JSON file using default options for parsing JSON data. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondatasource/__init__/#str-groupdocs.assembly.data.JsonDataLoadOptions) | Creates a new data source with data from a JSON file using the specified options for parsing JSON data. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondatasource/__init__/#io.RawIOBase) | Creates a new data source with data from a JSON stream using default options for parsing JSON data. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondatasource/__init__/#io.RawIOBase-groupdocs.assembly.data.JsonDataLoadOptions) | Creates a new data source with data from a JSON stream using the specified options for parsing JSON data. |



### Remarks 


To access data of the corresponding file or stream while assembling a document, pass an instance of this class as
a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler). 
overloads.




In template documents, if a top-level JSON element is an array, a [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource) instance should be
treated in the same way as if it was a DataTable instance. If a top-level JSON element 
is an object, a [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource) instance should be treated in the same way as if it was 
a DataRow instance. For more information, see template syntax reference 
.




In template documents, you can work with typed values of JSON elements. For convenience, the engine replaces the set 
of JSON simple types with the following one:




The engine automatically recognizes values of the extra types upon their JSON representations.




To override default behavior of JSON data loading, initialize and pass a [`JsonDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions) instance
to a constructor of this class.

### See Also
* module [`groupdocs.assembly.data`](..)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
* class [`JsonDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions)
* class [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource)
