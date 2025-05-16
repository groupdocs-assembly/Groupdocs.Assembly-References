---
title: XmlDataSource class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly.data/xmldatasource/
is_root: false
weight: 160
---

## XmlDataSource class

Provides access to data of an XML file or stream to be used while assembling a document.



The XmlDataSource type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#str) | Creates a new data source with data from an XML file using default options for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#io.RawIOBase) | Creates a new data source with data from an XML stream using default options for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#str-str) | Creates a new data source with data from an XML file using an XML Schema Definition file. Default options<br/>are used for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#io.RawIOBase-io.RawIOBase) | Creates a new data source with data from an XML stream using an XML Schema Definition stream. Default options<br/>are used for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#str-groupdocs.assembly.data.XmlDataLoadOptions) | Creates a new data source with data from an XML file using the specified options for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#io.RawIOBase-groupdocs.assembly.data.XmlDataLoadOptions) | Creates a new data source with data from an XML stream using the specified options for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#str-str-groupdocs.assembly.data.XmlDataLoadOptions) | Creates a new data source with data from an XML file using an XML Schema Definition file. The specified<br/>options are used for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#io.RawIOBase-io.RawIOBase-groupdocs.assembly.data.XmlDataLoadOptions) | Creates a new data source with data from an XML stream using an XML Schema Definition stream. The specified<br/>options are used for XML data loading. |



### Remarks 


To access data of the corresponding file or stream while assembling a document, pass an instance of this class as
a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler). 
overloads.




In template documents, if a top-level XML element contains only a list of elements of the same type, 
an [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource) instance should be treated in the same way as if it was 
a DataTable instance. Otherwise, an [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource) instance should be 
treated in the same way as if it was a DataRow instance. For more information, 
see template syntax reference 
.




When XML Schema Definition is passed to a constructor of this class, data types of values of simple XML elements 
and attributes are determined according to the schema. So in template documents, you can work with typed values 
rather than just strings.




When XML Schema Definition is not passed to a constructor of this class, data types of values of simple XML elements 
and attributes are determined automatically upon their string representations. So in template documents, you can work 
with typed values in this case as well. The engine is capable to automatically recognize values of the following types:




Note that for automatic recognition of data types to work, string representations of values of simple XML elements 
and attributes should be formed using invariant culture settings.




To override default behavior of XML data loading, initialize and pass a [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions)
instance to a constructor of this class.

### See Also
* module [`groupdocs.assembly.data`](..)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
* class [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions)
* class [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource)
