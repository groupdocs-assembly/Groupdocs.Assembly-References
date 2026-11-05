---
title: LoadSaveOptions class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Specifies additional options for loading and saving of a document to be assembled."
type: docs
url: /python-net/groupdocs.assembly/loadsaveoptions/
is_root: false
weight: 130
---


## LoadSaveOptions class

Specifies additional options for loading and saving of a document to be assembled.

The LoadSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/assembly/python-net/groupdocs.assembly/loadsaveoptions/__init__/) | Initializes a new instance of LoadSaveOptions without any properties specified. |
| [__init__](/assembly/python-net/groupdocs.assembly/loadsaveoptions/__init__/#save_format) | Initializes a new instance with the specified file format to save an assembled document to. |

### Properties
| Property | Description |
| :- | :- |
| [ooxml_compliance](/assembly/python-net/groupdocs.assembly/loadsaveoptions/ooxml_compliance/) | The OOXML compliance level to use when saving Word documents to OOXML formats (DOCX, DOCM, DOTX, DOTM, etc.). The default value is None, which means the compliance level will be determined automatically: if the original document was in Transitional format it is preserved; otherwise Strict compliance is used. |
| [resource_load_base_uri](/assembly/python-net/groupdocs.assembly/loadsaveoptions/resource_load_base_uri/) | The base URI used to resolve external resource files' relative URIs to absolute ones when loading an HTML template document to be assembled and saved to a non‑HTML format. The default value is an empty string. |
| [resource_save_folder](/assembly/python-net/groupdocs.assembly/loadsaveoptions/resource_save_folder/) | The path to a folder where external resource files are stored when an assembled document loaded from a non‑HTML format is saved to HTML. The default value is an empty string. |
| [save_format](/assembly/python-net/groupdocs.assembly/loadsaveoptions/save_format/) | The file format to save an assembled document to. `FileFormat.unspecified` is the default. |

### Example

```python
import io
from datetime import datetime
from decimal import Decimal

from groupdocs.assembly import DataSourceInfo, DocumentAssembler, FileFormat, LoadSaveOptions

invoice = {
    "CustomerName": "Lantern Street Café",
    "Amount": Decimal("522.00"),
    "Date": datetime(2015, 2, 3),
}

with open("customer-invoice.docx", "rb") as template, io.BytesIO() as out:
    assembler = DocumentAssembler()
    options = LoadSaveOptions(FileFormat.PDF)
    assembler.assemble_document(template, out, options,
                                DataSourceInfo(invoice, "invoice"))
    with open("customer-invoice-from-stream.pdf", "wb") as f:
        f.write(out.getvalue())
```

```python
from groupdocs.assembly import DocumentAssembler, FileFormat, LoadSaveOptions, OoxmlCompliance, DataSourceInfo

assembler = DocumentAssembler()
options = LoadSaveOptions(FileFormat.DOCX)
options.ooxml_compliance = OoxmlCompliance.TRANSITIONAL

data = {"CustomerName": "Quayside Bistro", "OrderNumber": "HLP-10001"}
assembler.assemble_document("order-acknowledgement.docx", "order-acknowledgement-report.docx",
                            options, DataSourceInfo(data, "order"))
```

### See Also
* module [`groupdocs.assembly`](/assembly/python-net/groupdocs.assembly/)
