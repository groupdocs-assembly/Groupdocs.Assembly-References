---
title: CsvDataSource class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Provides access to data of a CSV file or stream to be used while assembling a document."
type: docs
url: /python-net/groupdocs.assembly.data/csvdatasource/
is_root: false
weight: 20
---


## CsvDataSource class

Provides access to data of a CSV file or stream to be used while assembling a document.

To access data of the corresponding file or stream while assembling a document, pass an instance of this class as a data source to one of [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/).AssembleDocument overloads.

In template documents, a [`CsvDataSource`](/assembly/python-net/groupdocs.assembly.data/csvdatasource/) instance should be treated in the same way as if it was a `System.Data.DataTable` instance. For more information, see the template syntax reference (https://docs.groupdocs.com/assembly/python-net/template-syntax-part-1-of-2/).

Data types of comma-separated values are determined automatically upon their string representations. So in template documents, you can work with typed values rather than just strings. The engine is capable to automatically recognize values of the following types:

- `long?`
- `double?`
- `bool?`
- `DateTime?`
- `string`

Note that for automatic recognition of data types to work, string representations of comma-separated values should be formed using invariant culture settings.

To override default behavior of CSV data loading, initialize and pass a [`CsvDataLoadOptions`](/assembly/python-net/groupdocs.assembly.data/csvdataloadoptions/) instance to a constructor of this class.

The CsvDataSource type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdatasource/__init__/#csv_path) | Initializes a new data source with data from a CSV file using default parsing options. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdatasource/__init__/#csv_path-options) | Initializes a new data source with data from a CSV file using the specified options for parsing CSV data. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdatasource/__init__/#csv_stream) | Initializes a new data source with data from a CSV stream using default parsing options. |
| [__init__](/assembly/python-net/groupdocs.assembly.data/csvdatasource/__init__/#csv_stream-options) | Initializes a new data source with data from a CSV stream using the specified options for parsing CSV data. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler
from groupdocs.assembly.data import CsvDataLoadOptions, CsvDataSource

persons = CsvDataSource("persons.csv", CsvDataLoadOptions(True))

assembler = DocumentAssembler()
assembler.assemble_document(
    "shop-staff-list.docx",
    "shop-staff-list-report.docx",
    DataSourceInfo(persons, "persons")
)
```

### Guides
Task guides that use `CsvDataSource`:

* [GroupDocs.Assembly Engine APIs](/assembly/python-net/guides/groupdocs.assembly-engine-apis/)

### See Also
* module [`groupdocs.assembly.data`](/assembly/python-net/groupdocs.assembly.data/)
