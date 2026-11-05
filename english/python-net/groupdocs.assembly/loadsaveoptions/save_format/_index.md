---
title: save_format property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The file format to save an assembled document to."
type: docs
url: /python-net/groupdocs.assembly/loadsaveoptions/save_format/
is_root: false
weight: 2040
---


## save_format property

The file format to save an assembled document to. `FileFormat.unspecified` is the default.

When the value of this property is not specified, [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler/) behaves as follows:

- When you specify a file path to save an assembled document, the save file format is determined from the file extension of the path.
- When you specify a stream to save an assembled document, the save file format remains the same as the file format of the loaded template document.

Beware that it is not always possible to save an assembled document to any file format using GroupDocs.Assembly. For example, a document loaded from a Word Processing format (such as DOCX) cannot be saved to a Spreadsheet format (such as XLSX). See the GroupDocs.Assembly online documentation for supported load‑save format combinations.

### Definition:
```python
@property
def save_format(self):
    ...
@save_format.setter
def save_format(self, value):
    ...
```

### See Also
* class [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions/)
