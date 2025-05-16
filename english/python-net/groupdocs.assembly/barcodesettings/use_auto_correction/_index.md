---
title: use_auto_correction property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/barcodesettings/use_auto_correction/
is_root: false
weight: 70
---

## use_auto_correction property


Gets or sets a value indicating whether an invalid barcode value should be corrected automatically 
(if possible) to fit the barcode's specification or an exception should be thrown to indicate the error. 
The default value is true.

### Remarks 


The auto-correction is not possible for Databar barcodes.
### Definition:
```python
@property
def use_auto_correction(self):
    ...
@use_auto_correction.setter
def use_auto_correction(self, value):
    ...
```

### See Also
* module [`groupdocs.assembly`](../../)
* class [`BarcodeSettings`](/assembly/python-net/groupdocs.assembly/barcodesettings)
