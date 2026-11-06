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

* [Template Syntax - Part 1 of 2](/assembly/python-net/guides/template-syntax-part-1-of-2/)
* [Template Syntax - Part 2 of 2](/assembly/python-net/guides/template-syntax-part-2-of-2/)
* [GroupDocs.Assembly Engine APIs](/assembly/python-net/guides/groupdocs.assembly-engine-apis/)
* [Barcodes Syntax and Properties](/assembly/python-net/guides/barcodes-syntax-and-properties/)
* [Generate Email Messages from Data](/assembly/python-net/guides/generate-email-messages/)
* [Adding NEXT Field into Template Syntax](/assembly/python-net/guides/adding-next-field-into-template-syntax/)

### See Also
* module [`groupdocs.assembly`](/assembly/python-net/groupdocs.assembly/)
