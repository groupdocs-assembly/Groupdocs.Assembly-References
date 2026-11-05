---
title: ooxml_compliance property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The OOXML compliance level to use when saving Word documents to OOXML formats (DOCX, DOCM, DOTX, DOTM, etc.)."
type: docs
url: /python-net/groupdocs.assembly/loadsaveoptions/ooxml_compliance/
is_root: false
weight: 2010
---


## ooxml_compliance property

The OOXML compliance level to use when saving Word documents to OOXML formats (DOCX, DOCM, DOTX, DOTM, etc.). The default value is None, which means the compliance level will be determined automatically: if the original document was in Transitional format it is preserved; otherwise Strict compliance is used.

Allows explicit specification of the OOXML compliance level when saving Word documents. When set to None (default), the system automatically preserves the original document's compliance level if it was Transitional; otherwise it uses Strict compliance.

Applies only when saving to OOXML formats (DOCX, DOCM, DOTX, DOTM, FlatOpc, etc.) and is ignored for other file formats.

### Definition:
```python
@property
def ooxml_compliance(self):
    ...
@ooxml_compliance.setter
def ooxml_compliance(self, value):
    ...
```

### See Also
* class [`LoadSaveOptions`](/assembly/python-net/groupdocs.assembly/loadsaveoptions/)
