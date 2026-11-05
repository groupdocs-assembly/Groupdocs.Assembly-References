---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new DocumentTable using the default DocumentTableOptions."
type: docs
url: /python-net/groupdocs.assembly.data/documenttable/__init__/
is_root: false
weight: 10
---


## __init__ {#document_path-index_in_document}

Initializes a new DocumentTable using the default DocumentTableOptions.

```python
def __init__(self, document_path, index_in_document):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_path | `str` | The path to a document containing the table to be accessed. |
| index_in_document | `int` | The zero‑based index of the table in the document. |

## __init__ {#document_path-index_in_document-options}

Initializes a new DocumentTable instance.

```python
def __init__(self, document_path, index_in_document, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_path | `str` | The path to a document containing the table to be accessed. |
| index_in_document | `int` | The zero-based index of the table in the document. |
| options | `DocumentTableOptions` | A set of options controlling extraction of data from the table. If None, default options are applied. |

### Example

```python
    from groupdocs.assembly import DataSourceInfo, DocumentAssembler
    from groupdocs.assembly.data import DocumentTable, DocumentTableOptions

    options = DocumentTableOptions()
    options.max_row_index = 3
    table = DocumentTable("managers.docx", 1, options)

    assembler = DocumentAssembler()
    assembler.assemble_document(
        "importing-word-processing-table-into-presentation.pptx",
        "importing-word-processing-table-into-presentation-report.pptx",
        DataSourceInfo(table, "table")
    )
    ```

## __init__ {#document_stream-index_in_document}

Initializes a new DocumentTable instance using default DocumentTableOptions.

```python
def __init__(self, document_stream, index_in_document):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_stream | `io.RawIOBase` | The stream containing a document with the table to be accessed. |
| index_in_document | `int` | The zero-based index of the table in the document. |

## __init__ {#document_stream-index_in_document-options}

Initializes a new DocumentTable instance.

```python
def __init__(self, document_stream, index_in_document, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_stream | `io.RawIOBase` | The stream containing a document with the table to be accessed. |
| index_in_document | `int` | The zero‑based index of the table in the document. |
| options | `DocumentTableOptions` | A set of options controlling extraction of data from the table. If None, default options are applied. |

### Example

```python
from groupdocs.assembly import DataSourceInfo, DocumentAssembler
from groupdocs.assembly.data import DocumentTable, DocumentTableOptions

options = DocumentTableOptions()
options.max_row_index = 3
table = DocumentTable("managers.docx", 1, options)

assembler = DocumentAssembler()
assembler.assemble_document(
    "importing-word-processing-table-into-presentation.pptx",
    "importing-word-processing-table-into-presentation-report.pptx",
    DataSourceInfo(table, "table")
)
```

### See Also
* class [`DocumentTable`](/assembly/python-net/groupdocs.assembly.data/documenttable/)
