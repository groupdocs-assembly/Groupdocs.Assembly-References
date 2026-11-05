---
title: XmlDataLoadOptions class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Represents options for XML data loading."
type: docs
url: /python-net/groupdocs.assembly.data/xmldataloadoptions/
is_root: false
weight: 160
---


## XmlDataLoadOptions class

Represents options for XML data loading.

An instance of this class can be passed into constructors of [`XmlDataSource`](/assembly/python-net/groupdocs.assembly.data/xmldatasource/).

The XmlDataLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions/__init__/) | Initializes a new instance of this class with default options. |

### Properties
| Property | Description |
| :- | :- |
| [always_generate_root_object](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions/always_generate_root_object/) | The flag indicating whether a generated data source will always contain an object for an XML root element; if the root has no attributes and all child elements share the same name, the object is omitted by default. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler
from groupdocs.assembly.data import XmlDataLoadOptions, XmlDataSource

options = XmlDataLoadOptions()
options.always_generate_root_object = True  # Always create root object

xml_data_source = XmlDataSource("staff-roster.xml", options)

assembler = DocumentAssembler()
assembler.assemble_document(
    "staff-roster-root.docx",
    "staff-roster-root-report.docx",
    DataSourceInfo(xml_data_source, "data")
)
```

### Guides
Task guides that use `XmlDataLoadOptions`:

* [GroupDocs.Assembly Engine APIs](/assembly/python-net/guides/groupdocs.assembly-engine-apis/)

### See Also
* module [`groupdocs.assembly.data`](/assembly/python-net/groupdocs.assembly.data/)
