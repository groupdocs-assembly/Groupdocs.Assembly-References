---
title: BarcodeSettings class
second_title: GroupDocs.Assembly for Python via .NET API References
description: "Represents a set of settings controlling barcode generation while assembling a document."
type: docs
url: /python-net/groupdocs.assembly/barcodesettings/
is_root: false
weight: 10
---


## BarcodeSettings class

Represents a set of settings controlling barcode generation while assembling a document.

The BarcodeSettings type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [base_x_dimension](/assembly/python-net/groupdocs.assembly/barcodesettings/base_x_dimension/) | The base x-dimension, the smallest width of the unit of barcode bars and spaces, measured in [`BarcodeSettings.graphics_unit`](/assembly/python-net/groupdocs.assembly/barcodesettings/graphics_unit/). |
| [base_y_dimension](/assembly/python-net/groupdocs.assembly/barcodesettings/base_y_dimension/) | The base y-dimension, the smallest height of the unit of 2D barcode modules. Measured in [`BarcodeSettings.graphics_unit`](/assembly/python-net/groupdocs.assembly/barcodesettings/graphics_unit/). |
| [graphics_unit](/assembly/python-net/groupdocs.assembly/barcodesettings/graphics_unit/) | The graphics unit used to measure [`BarcodeSettings.BaseXDimension`](/assembly/python-net/groupdocs.assembly/barcodesettings/base_x_dimension/) and [`BarcodeSettings.BaseYDimension`](/assembly/python-net/groupdocs.assembly/barcodesettings/base_y_dimension/). The default value is `GraphicsUnit.MILLIMETER`. |
| [resolution](/assembly/python-net/groupdocs.assembly/barcodesettings/resolution/) | The horizontal and vertical resolution of a barcode image being generated, measured in dots per inch. The default value is 96. |
| [use_auto_correction](/assembly/python-net/groupdocs.assembly/barcodesettings/use_auto_correction/) | The property indicates whether an invalid barcode value should be corrected automatically (if possible) to fit the barcode's specification, or an exception should be thrown to indicate the error. The default value is True. |
| [xresolution](/assembly/python-net/groupdocs.assembly/barcodesettings/xresolution/) | The horizontal resolution of a generated barcode image, measured in dots per inch. |
| [yresolution](/assembly/python-net/groupdocs.assembly/barcodesettings/yresolution/) | The vertical resolution of a barcode image being generated, measured in dots per inch. The default value is 96. |

### See Also
* module [`groupdocs.assembly`](/assembly/python-net/groupdocs.assembly/)
