---
title: XmlDataSource class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Provides access to data of an XML file or stream to be used while assembling a document."
type: docs
url: /python-net/groupdocs.assembly.data/xmldatasource/
is_root: false
weight: 170
---


## XmlDataSource class

Provides access to data of an XML file or stream to be used while assembling a document.

To access data of the corresponding file or stream while assembling a document, pass an instance of this class as a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/).assemble_document overloads.

In template documents, if a top‑level XML element contains only a list of elements of the same type, a [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource/) instance should be treated as a `System.Data.DataTable`. Otherwise, it should be treated as a `System.Data.DataRow`. For more information, see the template syntax reference.

When an XML Schema Definition is passed to a constructor of this class, data types of values of simple XML elements and attributes are determined according to the schema, allowing typed values in templates.

When no XML Schema Definition is provided, data types are inferred automatically from string representations. The engine can recognize the following types:

- `long?`
- `double?`
- `bool?`
- `DateTime?`
- `string`

Note that automatic type recognition requires string representations to use invariant culture settings.

To override the default XML data loading behavior, initialize and pass a [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions/) instance to a constructor of this class.

The XmlDataSource type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#xml_path) | Initializes a new data source with data from an XML file using default options for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#xml_stream) | Initializes a new data source with data from an XML stream using default options for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#xml_path-xml_schema_path) | Initializes a new data source with data from an XML file using an XML Schema Definition file. Default options are used for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#xml_stream-xml_schema_stream) | Initializes a new data source with data from an XML stream using an XML Schema Definition stream. Default options are used for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#xml_path-options) | Initializes a new data source with data from an XML file using the specified options for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#xml_stream-options) | Initializes a new data source with data from an XML stream using the specified options for XML data loading. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#xml_path-xml_schema_path-options) | Initializes a new data source with data from an XML file using an XML Schema Definition file. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldatasource/__init__/#xml_stream-xml_schema_stream-options) | Initializes a new data source with XML data from a stream and an optional XML Schema Definition stream, using the specified loading options. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler
from groupdocs.assembly.data import XmlDataSource

xml_data_source = XmlDataSource("staff-profile.xml")
assembler = DocumentAssembler()
assembler.assemble_document(
    "staff-profile.docx",
    "staff-profile-report.docx",
    DataSourceInfo(xml_data_source, "data")
)
```

### Guides
Task guides that use `XmlDataSource`:

* [GroupDocs.Assembly Engine APIs](/assembly/python-net/guides/groupdocs.assembly-engine-apis/)

### See Also
* module [`groupdocs.assembly.data`](/assembly/python-net/groupdocs.assembly.data/)
