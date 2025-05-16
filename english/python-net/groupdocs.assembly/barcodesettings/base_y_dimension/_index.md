---
title: base_y_dimension property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/barcodesettings/base_y_dimension/
is_root: false
weight: 40
---

## base_y_dimension property


Gets or sets a base y-dimension, that is, the smallest height of the unit of 2D barcode modules.
Measured in [`BarcodeSettings.graphics_unit`](/assembly/python-net/groupdocs.assembly/barcodesettings#graphics_unit).

### Remarks 


Barcodes of some types (such as data matrix) may ignore an y-dimension and use an x-dimension for both 
width and height units.




When barcode scaling is applied through a template, an actual y-dimension is calculated upon the base 
y-dimension and a scaling factor.
### Definition:
```python
@property
def base_y_dimension(self):
    ...
@base_y_dimension.setter
def base_y_dimension(self, value):
    ...
```

### See Also
* module [`groupdocs.assembly`](../../)
* class [`BarcodeSettings`](/assembly/python-net/groupdocs.assembly/barcodesettings)
