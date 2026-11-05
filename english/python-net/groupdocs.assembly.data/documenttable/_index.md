---
title: DocumentTable class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Provides access to data of a single table (or spreadsheet) located in an external document to be used while assembling a document."
type: docs
url: /python-net/groupdocs.assembly.data/documenttable/
is_root: false
weight: 30
---


## DocumentTable class

Provides access to data of a single table (or spreadsheet) located in an external document to be used while assembling a document.

For documents of Spreadsheet file formats, a [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/) instance represents a single sheet. For documents of other file formats, a [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/) instance represents a single table.

To access data of the corresponding table while assembling a document, pass an instance of this class as a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/).`AssembleDocument` overloads.

In template documents, a [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/) instance should be treated in the same way as if it was a `System.Data.DataTable` instance. See template syntax reference for more information.

The DocumentTable type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttable/__init__/#document_path-index_in_document) | Initializes a new DocumentTable using the default DocumentTableOptions. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttable/__init__/#document_path-index_in_document-options) | Initializes a new DocumentTable instance. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttable/__init__/#document_stream-index_in_document) | Initializes a new DocumentTable instance using default DocumentTableOptions. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttable/__init__/#document_stream-index_in_document-options) | Initializes a new DocumentTable instance. |

### Properties
| Property | Description |
| :- | :- |
| [columns](/assembly/python-net/groupdocs.assembly.data/documenttable/columns/) | The collection of [`DocumentTableColumn`](/assembly/python-net/groupdocs.assembly.data/documenttablecolumn/) objects representing columns of the corresponding table. |
| [index_in_document](/assembly/python-net/groupdocs.assembly.data/documenttable/index_in_document/) | The original zero-based index of the corresponding table in the source document. |
| [name](/assembly/python-net/groupdocs.assembly.data/documenttable/name/) | The name of this table used to access the table's data in a template document passed to [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/). |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler
from groupdocs.assembly.data import DocumentTable, DocumentTableOptions

options = DocumentTableOptions()
options.max_row_index = 3
table = DocumentTable("managers.pptx", 1, options)

assembler = DocumentAssembler()
assembler.assemble_document(
    "table-row.pptx",
    "table-row-report.pptx",
    DataSourceInfo(table, "table")
)
```

### See Also
* module [`groupdocs.assembly.data`](/assembly/python-net/groupdocs.assembly.data/)
