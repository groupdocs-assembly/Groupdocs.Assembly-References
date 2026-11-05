---
title: use_auto_correction property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The property indicates whether an invalid barcode value should be corrected automatically (if possible) to fit the barcode's specification, or an exception should be thrown to indicate the error."
type: docs
url: /python-net/groupdocs.assembly/barcodesettings/use_auto_correction/
is_root: false
weight: 2050
---


## use_auto_correction property

The property indicates whether an invalid barcode value should be corrected automatically (if possible) to fit the barcode's specification, or an exception should be thrown to indicate the error. The default value is True.

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
* class [`BarcodeSettings`](/assembly/python-net/groupdocs.assembly/barcodesettings/)
