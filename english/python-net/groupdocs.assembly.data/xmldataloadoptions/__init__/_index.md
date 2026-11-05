---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new instance of this class with default options."
type: docs
url: /python-net/groupdocs.assembly.data/xmldataloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of this class with default options.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.assembly.data import XmlDataLoadOptions, XmlDataSource
from groupdocs.assembly import DataSourceInfo, DocumentAssembler

options = XmlDataLoadOptions()
options.always_generate_root_object = True  # optional setting

xml_source = XmlDataSource("staff-roster.xml", options)

assembler = DocumentAssembler()
assembler.assemble_document(
    "staff-roster-root.docx",
    "staff-roster-root-report.docx",
    DataSourceInfo(xml_source, "data")
)
```

### See Also
* class [`XmlDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/xmldataloadoptions/)
