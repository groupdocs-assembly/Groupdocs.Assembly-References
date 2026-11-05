---
title: base_y_dimension property
second_title: GroupDocs.Assembly for Python via .NET API References
description: "The base y-dimension, the smallest height of the unit of 2D barcode modules."
type: docs
url: /python-net/groupdocs.assembly/barcodesettings/base_y_dimension/
is_root: false
weight: 2020
---


## base_y_dimension property

The base y-dimension, the smallest height of the unit of 2D barcode modules. Measured in [`BarcodeSettings.graphics_unit`](/assembly/python-net/groupdocs.assembly/barcodesettings/graphics_unit/).

Barcodes of some types (such as data matrix) may ignore a y-dimension and use an x-dimension for both width and height units.

When barcode scaling is applied through a template, an actual y-dimension is calculated from the base y-dimension and a scaling factor.

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
* class [`BarcodeSettings`](/assembly/python-net/groupdocs.assembly/barcodesettings/)
