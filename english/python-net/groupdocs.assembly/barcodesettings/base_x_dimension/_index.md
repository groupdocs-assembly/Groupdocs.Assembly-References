---
title: base_x_dimension property
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.assembly/barcodesettings/base_x_dimension/
is_root: false
weight: 30
---

## base_x_dimension property


Gets or sets a base x-dimension, that is, the smallest width of the unit of barcode bars and spaces.
Measured in [`BarcodeSettings.graphics_unit`](/assembly/python-net/groupdocs.assembly/barcodesettings#graphics_unit).

### Remarks 


When barcode scaling is applied through a template, an actual x-dimension is calculated upon the base 
x-dimension and a scaling factor.
### Definition:
```python
@property
def base_x_dimension(self):
    ...
@base_x_dimension.setter
def base_x_dimension(self, value):
    ...
```

### See Also
* module [`groupdocs.assembly`](../../)
* class [`BarcodeSettings`](/assembly/python-net/groupdocs.assembly/barcodesettings)
