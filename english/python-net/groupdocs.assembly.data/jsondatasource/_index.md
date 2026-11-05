---
title: JsonDataSource class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Provides access to data of a JSON file or stream to be used while assembling a document."
type: docs
url: /python-net/groupdocs.assembly.data/jsondatasource/
is_root: false
weight: 140
---


## JsonDataSource class

Provides access to data of a JSON file or stream to be used while assembling a document.

To access data of the corresponding file or stream while assembling a document, pass an instance of this class as a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/) overloads.

In template documents, if a top-level JSON element is an array, a [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource/) instance should be treated in the same way as if it was a `System.Data.DataTable` instance. If a top-level JSON element is an object, a [`JsonDataSource`](/assembly/python-net/groupdocs.assembly.data/jsondatasource/) instance should be treated in the same way as if it was a `System.Data.DataRow` instance. For more information, see the template syntax reference (https://docs.groupdocs.com/assembly/python-net/template-syntax-part-1-of-2/).

In template documents, you can work with typed values of JSON elements. For convenience, the engine replaces the set of JSON simple types with the following one:
- `long?`
- `double?`
- `bool?`
- `DateTime?`
- `string`

The engine automatically recognizes values of the extra types upon their JSON representations.

To override default behavior of JSON data loading, initialize and pass a [`JsonDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/jsondataloadoptions/) instance to a constructor of this class.

The JsonDataSource type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondatasource/__init__/#json_path) | Initializes a new data source with data from a JSON file using default parsing options. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondatasource/__init__/#json_path-options) | Initializes a new data source with data from a JSON file using the specified options for parsing JSON data. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondatasource/__init__/#json_stream) | Initializes a new data source with data from a JSON stream using default parsing options. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/jsondatasource/__init__/#json_stream-options) | Initializes a new data source with data from a JSON stream using the specified options for parsing JSON data. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler
from groupdocs.assembly.data import JsonDataSource

json_data_source = JsonDataSource("staff-member.json")

assembler = DocumentAssembler()
assembler.assemble_document(
    "staff-member-card.docx",
    "staff-member-card-report.docx",
    DataSourceInfo(json_data_source, "data")
)
```

### Guides
Task guides that use `JsonDataSource`:

* [GroupDocs.Assembly Engine APIs](/assembly/python-net/guides/groupdocs.assembly-engine-apis/)

### See Also
* module [`groupdocs.assembly.data`](/assembly/python-net/groupdocs.assembly.data/)
