---
title: BarcodeSettings class
second_title: GroupDocs.Assembly for Python via .NET API References
description: 
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
| [graphics_unit](/assembly/python-net/groupdocs.assembly/barcodesettings/graphics_unit) | Gets or sets a graphics unit used to measure [`BarcodeSettings.base_x_dimension`](/assembly/python-net/groupdocs.assembly/barcodesettings#base_x_dimension) and [`BarcodeSettings.base_y_dimension`](/assembly/python-net/groupdocs.assembly/barcodesettings#base_y_dimension).<br/>The default value is [`GraphicsUnit.MILLIMETER`](/assembly/python-net/groupdocs.assembly/graphicsunit#MILLIMETER). |
| [base_x_dimension](/assembly/python-net/groupdocs.assembly/barcodesettings/base_x_dimension) | Gets or sets a base x-dimension, that is, the smallest width of the unit of barcode bars and spaces.<br/>Measured in [`BarcodeSettings.graphics_unit`](/assembly/python-net/groupdocs.assembly/barcodesettings#graphics_unit). |
| [base_y_dimension](/assembly/python-net/groupdocs.assembly/barcodesettings/base_y_dimension) | Gets or sets a base y-dimension, that is, the smallest height of the unit of 2D barcode modules.<br/>Measured in [`BarcodeSettings.graphics_unit`](/assembly/python-net/groupdocs.assembly/barcodesettings#graphics_unit). |
| [resolution](/assembly/python-net/groupdocs.assembly/barcodesettings/resolution) | Gets or sets the horizontal and vertical resolution of a barcode image being generated. Measured in dots<br/>per inch. The default value is 96. |
| [x_resolution](/assembly/python-net/groupdocs.assembly/barcodesettings/x_resolution) | Gets or sets the horizontal resolution of a barcode image being generated. Measured in dots per inch.<br/>The default value is 96. |
| [y_resolution](/assembly/python-net/groupdocs.assembly/barcodesettings/y_resolution) | Gets or sets the vertical resolution of a barcode image being generated. Measured in dots per inch.<br/>The default value is 96. |
| [use_auto_correction](/assembly/python-net/groupdocs.assembly/barcodesettings/use_auto_correction) | Gets or sets a value indicating whether an invalid barcode value should be corrected automatically <br/>(if possible) to fit the barcode's specification or an exception should be thrown to indicate the error. <br/>The default value is true. |



### See Also
* module [`groupdocs.assembly`](..)
