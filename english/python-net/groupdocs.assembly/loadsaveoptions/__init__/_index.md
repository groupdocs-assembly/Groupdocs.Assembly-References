---
title: __init__ constructor
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Initializes a new instance of LoadSaveOptions without any properties specified."
type: docs
url: /python-net/groupdocs.assembly/loadsaveoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of LoadSaveOptions without any properties specified.

```python
def __init__(self):
    ...
```

## __init__ {#save_format}

Initializes a new instance with the specified file format to save an assembled document to.

```python
def __init__(self, save_format):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| save_format | `FileFormat` | A file format to save an assembled document to. |

### Example

```python
from groupdocs.assembly import DocumentAssembler, LoadSaveOptions, FileFormat

options = LoadSaveOptions(FileFormat.PDF)
assembler = DocumentAssembler()
# Pass `options` to `assemble_document` to generate a PDF output
```

### See Also
* class [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions/)
