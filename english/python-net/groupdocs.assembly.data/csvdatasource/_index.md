---
title: CsvDataSource class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/csvdatasource/
is_root: false
weight: 20
---

## CsvDataSource class

Provides access to data of a CSV file or stream to be used while assembling a document.



The CsvDataSource type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdatasource/__init__/#str) | Creates a new data source with data from a CSV file using default options for parsing CSV data. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdatasource/__init__/#str-groupdocs.assembly.data.CsvDataLoadOptions) | Creates a new data source with data from a CSV file using the specified options for parsing CSV data. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdatasource/__init__/#io.RawIOBase) | Creates a new data source with data from a CSV stream using default options for parsing CSV data. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdatasource/__init__/#io.RawIOBase-groupdocs.assembly.data.CsvDataLoadOptions) | Creates a new data source with data from a CSV stream using the specified options for parsing CSV data. |



### Remarks 


To access data of the corresponding file or stream while assembling a document, pass an instance of this class as
a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler). 
overloads.




In template documents, a [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource) instance should be treated in the same way as if it was
a DataTable instance. For more information, see template syntax reference 
.




Data types of comma-separated values are determined automatically upon their string representations. So in template
documents, you can work with typed values rather than just strings. The engine is capable to automatically recognize 
values of the following types:




Note that for automatic recognition of data types to work, string representations of comma-separated values should 
be formed using invariant culture settings.




To override default behavior of CSV data loading, initialize and pass a [`CsvDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions) instance
to a constructor of this class.

### See Also
* module [`groupdocs.assembly.data`](..)
* class [`CsvDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions)
* class [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
