---
title: DocumentTableSet class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Provides access to data of multiple tables (or spreadsheets) located in an external document to be used while assembling a document."
type: docs
url: /python-net/groupdocs.assembly.data/documenttableset/
is_root: false
weight: 110
---


## DocumentTableSet class

Provides access to data of multiple tables (or spreadsheets) located in an external document to be used while assembling a document. Also enables defining parent‑child relations for the document tables, simplifying access to related data within template documents.

For documents of spreadsheet file formats, a [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset/) instance represents a set of sheets. For documents of other file formats, a [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset/) instance represents a set of tables.

To access data of the corresponding tables while assembling a document, pass an instance of this class as a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/) overloads.

In template documents, a [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset/) instance should be treated the same way as a `System.Data.DataSet` instance. See the template syntax reference for more information.

The DocumentTableSet type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttableset/__init__/#document_path) | Initializes a new DocumentTableSet loading all tables from a document using default DocumentTableOptions. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttableset/__init__/#document_path-load_handler) | Initializes a new DocumentTableSet. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttableset/__init__/#document_stream) | Initializes a new DocumentTableSet loading all tables from a document using default DocumentTableOptions. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/documenttableset/__init__/#document_stream-load_handler) | Initializes a new DocumentTableSet instance. |

### Properties
| Property | Description |
| :- | :- |
| [relations](/assembly/python-net/groupdocs.assembly.data/documenttableset/relations/) | The collection of parent‑child relations defined for document tables of this set. |
| [tables](/assembly/python-net/groupdocs.assembly.data/documenttableset/tables/) | The collection of [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/) objects representing tables of this set. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler
from groupdocs.assembly.data import DocumentTableOptions, DocumentTableSet

def load_table(args):
    # The first row of every table holds its column names
    options = DocumentTableOptions()
    options.first_row_contains_column_names = True
    args.options = options

# Load all tables from an Excel file
tables = DocumentTableSet("related-tables.xlsx", load_table)

# Define parent‑child relations between tables
tables.relations.add(
    tables.tables["CLIENT"].columns["ID"],
    tables.tables["CONTRACT"].columns["CLIENT_ID"]
)
tables.relations.add(
    tables.tables["MANAGER"].columns["ID"],
    tables.tables["CONTRACT"].columns["MANAGER_ID"]
)

# Use the tables as a data source for document assembly
assembler = DocumentAssembler()
assembler.assemble_document(
    "table-relations.docx",
    "table-relations-report.docx",
    DataSourceInfo(tables)
)
```

### Guides
Task guides that use `DocumentTableSet`:

* [Template Syntax - Part 2 of 2](/assembly/python-net/guides/template-syntax-part-2-of-2/)

### See Also
* module [`groupdocs.assembly.data`](/assembly/python-net/groupdocs.assembly.data/)
