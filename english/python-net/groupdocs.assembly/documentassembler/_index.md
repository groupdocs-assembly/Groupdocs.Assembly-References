---
title: DocumentAssembler class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Provides routines to populate template documents with data and a set of settings to control these routines."
type: docs
url: /python-net/groupdocs.assembly/documentassembler/
is_root: false
weight: 30
---


## DocumentAssembler class

Provides routines to populate template documents with data and a set of settings to control these routines.

The DocumentAssembler type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly/documentassembler/__init__/) | Initializes a new instance of this class. |

### Methods
| Method | Description |
| :- | :- |
| [assemble_document](/assembly/python-net/groupdocs.assembly/documentassembler/assemble_document/#source_path-target_path-data_source_infos) | Loads a template document from the specified source path, populates the template document with data from the specified single or multiple sources, and stores the result document to the target path using default [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions/). |
| [assemble_document](/assembly/python-net/groupdocs.assembly/documentassembler/assemble_document/#source_path-target_path-load_save_options-data_source_infos) | Loads a template document from the specified source path, populates it with data from the given sources, and saves the result to the target path using the provided LoadSaveOptions. |
| [assemble_document](/assembly/python-net/groupdocs.assembly/documentassembler/assemble_document/#source_stream-target_stream-data_source_infos) | Loads a template document from the specified source stream, populates it with data from the given sources, and writes the result to the target stream using default [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions/). |
| [assemble_document](/assembly/python-net/groupdocs.assembly/documentassembler/assemble_document/#source_stream-target_stream-load_save_options-data_source_infos) | Loads a template document from the specified source stream, populates it with data from the given sources, and writes the result to the target stream using the provided LoadSaveOptions. |

### Properties
| Property | Description |
| :- | :- |
| [barcode_settings](/assembly/python-net/groupdocs.assembly/documentassembler/barcode_settings/) | The set of settings controlling barcode generation while assembling a document. |
| [known_types](/assembly/python-net/groupdocs.assembly/documentassembler/known_types/) | The unordered set of unique type names that can be referenced in document templates processed by this assembler instance to invoke static members, perform type casts, etc. |
| [options](/assembly/python-net/groupdocs.assembly/documentassembler/options/) | The options property defines a set of flags that control the behavior of this DocumentAssembler instance while assembling a document. |

### Fields
| Field | Description |
| :- | :- |
| [USE_REFLECTION_OPTIMIZATION](/assembly/python-net/groupdocs.assembly/documentassembler/use_reflection_optimization/) | Gets or sets a value indicating whether invocations of custom type members performed via reflection API are optimized using dynamic class generation or not. The default value is true. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler

orders = [
    {"Number": 10001, "Product": "Harbor Blend whole bean coffee", "Quantity": 30, "Price": 552.0},
    {"Number": 10004, "Product": "Aged harbour cheddar", "Quantity": 8, "Price": 132.0},
]

# Each data source goes under the name the template's tags use for it
assembler = DocumentAssembler()
assembler.assemble_document("order-table.docx", "order-table-report.docx", [
    DataSourceInfo("Quayside Bistro", "customer"),
    DataSourceInfo(orders, "orders"),
])
```

### Guides
Task guides that use `DocumentAssembler`:

* [GroupDocs.Assembly Engine APIs](/assembly/python-net/guides/groupdocs.assembly-engine-apis/)

### See Also
* module [`groupdocs.assembly`](/assembly/python-net/groupdocs.assembly/)
