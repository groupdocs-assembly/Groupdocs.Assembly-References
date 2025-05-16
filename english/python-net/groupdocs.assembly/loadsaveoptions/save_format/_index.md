---
title: save_format property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/loadsaveoptions/save_format/
is_root: false
weight: 50
---

## save_format property


Gets or sets a file format to save an assembled document to. [`FileFormat.UNSPECIFIED`](/assembly/python-net/groupdocs.assembly/fileformat#UNSPECIFIED) is the default.

### Remarks 


When the value of this property is not specified, [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler) behaves as follows:




- When you specify a file path to save an assembled document, the save file format is determined upon file 
extension from the path.




- When you specify a stream to save an assembled document, the save file format remains the same as the file 
format of a loaded template document.




Beware that it is not always possible to save an assembled document to any file format using GroupDocs.Assembly. 
For example, it is impossible to save a document loaded from a Word Processing file format (such as DOCX) to 
a Spreadsheet file format (such as XLSX). For more information on possible combinations of load and save file 
formats supported by GroupDocs.Assembly, please check GroupDocs.Assembly online documentation.
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
* module [`groupdocs.assembly`](../../)
* class [`DocumentAssembler`](/assembly/python-net/groupdocs.assembly/documentassembler)
* class [`FileFormat`](/assembly/python-net/groupdocs.assembly/fileformat)
* class [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions)
