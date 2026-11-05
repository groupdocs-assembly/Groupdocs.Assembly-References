---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new DocumentTableSet loading all tables from a document using default DocumentTableOptions."
type: docs
url: /python-net/groupdocs.assembly.data/documenttableset/__init__/
is_root: false
weight: 10
---


## __init__ {#document_path}

Initializes a new DocumentTableSet loading all tables from a document using default DocumentTableOptions.

```python
def __init__(self, document_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_path | `str` | The path to a document containing tables to be accessed. |

## __init__ {#document_path-load_handler}

Initializes a new DocumentTableSet.

```python
def __init__(self, document_path, load_handler):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_path | `str` | The path to a document containing tables to be accessed. |
| load_handler | `IDocumentTableLoadHandler` | An implementation controlling how document tables are loaded. |

### Example

```python
from groupdocs.assembly.data import DocumentTableSet, DocumentTableOptions

def load_table(args):
    options = DocumentTableOptions()
    options.first_row_contains_column_names = True
    args.options = options

tables = DocumentTableSet("multiple-tables.docx", load_table)
```

## __init__ {#document_stream}

Initializes a new DocumentTableSet loading all tables from a document using default DocumentTableOptions.

```python
def __init__(self, document_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_stream | `io.RawIOBase` | The stream containing a document with tables to be accessed. |

## __init__ {#document_stream-load_handler}

Initializes a new DocumentTableSet instance.

```python
def __init__(self, document_stream, load_handler):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| document_stream | `io.RawIOBase` | The stream containing a document with tables to be accessed. |
| load_handler | `IDocumentTableLoadHandler` | An implementation controlling how document tables are loaded. |

### See Also
* class [`DocumentTableSet`](/assembly/python-net/groupdocs.assembly.data/documenttableset/)
