---
title: DataSourceInfo class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Provides information on a single data source object to be used to assemble a document from a template."
type: docs
url: /python-net/groupdocs.assembly/datasourceinfo/
is_root: false
weight: 20
---


## DataSourceInfo class

Provides information on a single data source object to be used to assemble a document from a template.

The DataSourceInfo type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly/datasourceinfo/__init__/) | Initializes a new DataSourceInfo instance with no properties set. |
| [__init__](/assembly/python-net/groupdocs.assembly/datasourceinfo/__init__/#data_source) | Initializes a new instance of this class with the specified data source object. |
| [__init__](/assembly/python-net/groupdocs.assembly/datasourceinfo/__init__/#data_source-name) | Initializes a new instance of this class with the data source object and its name specified. |

### Properties
| Property | Description |
| :- | :- |
| [data_source](/assembly/python-net/groupdocs.assembly/datasourceinfo/data_source/) | The data source object. |
| [name](/assembly/python-net/groupdocs.assembly/datasourceinfo/name/) | The name of the data source object used to access it in a template document. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler

# A dict, under the name the template's tags use for it: <<[customer.Name]>>
customer = {"Name": "Quayside Bistro", "Product": "Harbor Blend whole bean coffee"}

assembler = DocumentAssembler()
assembler.assemble_document("hello-world.docx", "hello-world-report.docx", DataSourceInfo(customer, "customer"))
```

### Guides
Task guides that use `DataSourceInfo`:

* [GroupDocs.Assembly Engine APIs](/assembly/python-net/guides/groupdocs.assembly-engine-apis/)
* [Generate sample report for document with variable](/assembly/python-net/guides/barcode/)
* [Generate email report with common list.](/assembly/python-net/guides/email_reports/)

### See Also
* module [`groupdocs.assembly`](/assembly/python-net/groupdocs.assembly/)
