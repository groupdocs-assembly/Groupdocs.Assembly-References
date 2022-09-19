---
title: BarcodeSettings
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a set of settings controlling barcode generation while assembling a document.
type: docs
weight: 10
url: /java/com.groupdocs.assembly/barcodesettings/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeSettings
```

Represents a set of settings controlling barcode generation while assembling a document.
## Methods

| Method | Description |
| --- | --- |
| [getGraphicsUnit()](#getGraphicsUnit--) | Gets a graphics unit used to measure getBaseXDimension() / setBaseXDimension(float) and getBaseYDimension() / setBaseYDimension(float). |
| [setGraphicsUnit(int value)](#setGraphicsUnit-int-) | Sets a graphics unit used to measure getBaseXDimension() / setBaseXDimension(float) and getBaseYDimension() / setBaseYDimension(float). |
| [getBaseXDimension()](#getBaseXDimension--) | Gets a base x-dimension, that is, the smallest width of the unit of barcode bars and spaces. |
| [setBaseXDimension(float value)](#setBaseXDimension-float-) | Sets a base x-dimension, that is, the smallest width of the unit of barcode bars and spaces. |
| [getBaseYDimension()](#getBaseYDimension--) | Gets a base y-dimension, that is, the smallest height of the unit of 2D barcode modules. |
| [setBaseYDimension(float value)](#setBaseYDimension-float-) | Sets a base y-dimension, that is, the smallest height of the unit of 2D barcode modules. |
| [getResolution()](#getResolution--) | Gets the horizontal and vertical resolution of a barcode image being generated. |
| [getXResolution()](#getXResolution--) | Gets the horizontal resolution of a barcode image being generated. |
| [getYResolution()](#getYResolution--) | Gets the vertical resolution of a barcode image being generated. |
| [getUseAutoCorrection()](#getUseAutoCorrection--) | Gets a value indicating whether an invalid barcode value should be corrected automatically (if possible) to fit the barcode's specification or an exception should be thrown to indicate the error. |
| [setUseAutoCorrection(boolean value)](#setUseAutoCorrection-boolean-) | Sets a value indicating whether an invalid barcode value should be corrected automatically (if possible) to fit the barcode's specification or an exception should be thrown to indicate the error. |
### getGraphicsUnit() {#getGraphicsUnit--}
```
public int getGraphicsUnit()
```


Gets a graphics unit used to measure getBaseXDimension() / setBaseXDimension(float) and getBaseYDimension() / setBaseYDimension(float). The default value is MILLIMETER.

**Returns:**
int - A graphics unit used to measure getBaseXDimension() / setBaseXDimension(float) and getBaseYDimension() / setBaseYDimension(float). The returned value is one of [GraphicsUnit](../../com.groupdocs.assembly.system.drawing/graphicsunit) constants.
### setGraphicsUnit(int value) {#setGraphicsUnit-int-}
```
public void setGraphicsUnit(int value)
```


Sets a graphics unit used to measure getBaseXDimension() / setBaseXDimension(float) and getBaseYDimension() / setBaseYDimension(float). The default value is MILLIMETER.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | A graphics unit used to measure getBaseXDimension() / setBaseXDimension(float) and getBaseYDimension() / setBaseYDimension(float). The value must be one of [GraphicsUnit](../../com.groupdocs.assembly.system.drawing/graphicsunit) constants. |

### getBaseXDimension() {#getBaseXDimension--}
```
public float getBaseXDimension()
```


Gets a base x-dimension, that is, the smallest width of the unit of barcode bars and spaces. Measured in getGraphicsUnit() / setGraphicsUnit(int). When barcode scaling is applied through a template, an actual x-dimension is calculated upon the base x-dimension and a scaling factor.

**Returns:**
float - A base x-dimension, that is, the smallest width of the unit of barcode bars and spaces.
### setBaseXDimension(float value) {#setBaseXDimension-float-}
```
public void setBaseXDimension(float value)
```


Sets a base x-dimension, that is, the smallest width of the unit of barcode bars and spaces. Measured in getGraphicsUnit() / setGraphicsUnit(int). When barcode scaling is applied through a template, an actual x-dimension is calculated upon the base x-dimension and a scaling factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | A base x-dimension, that is, the smallest width of the unit of barcode bars and spaces. |

### getBaseYDimension() {#getBaseYDimension--}
```
public float getBaseYDimension()
```


Gets a base y-dimension, that is, the smallest height of the unit of 2D barcode modules. Measured in getGraphicsUnit() / setGraphicsUnit(int).

Barcodes of some types (such as data matrix) may ignore an y-dimension and use an x-dimension for both width and height units.

When barcode scaling is applied through a template, an actual y-dimension is calculated upon the base y-dimension and a scaling factor.

**Returns:**
float - A base y-dimension, that is, the smallest height of the unit of 2D barcode modules.
### setBaseYDimension(float value) {#setBaseYDimension-float-}
```
public void setBaseYDimension(float value)
```


Sets a base y-dimension, that is, the smallest height of the unit of 2D barcode modules. Measured in getGraphicsUnit() / setGraphicsUnit(int).

Barcodes of some types (such as data matrix) may ignore an y-dimension and use an x-dimension for both width and height units.

When barcode scaling is applied through a template, an actual y-dimension is calculated upon the base y-dimension and a scaling factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | A base y-dimension, that is, the smallest height of the unit of 2D barcode modules. |

### getResolution() {#getResolution--}
```
public float getResolution()
```


Gets the horizontal and vertical resolution of a barcode image being generated. Measured in dots per inch. The default value is 96.

**Returns:**
float - The horizontal and vertical resolution of a barcode image being generated.
### getXResolution() {#getXResolution--}
```
public float getXResolution()
```


Gets the horizontal resolution of a barcode image being generated. Measured in dots per inch. The default value is 96.

**Returns:**
float - The horizontal resolution of a barcode image being generated.
### getYResolution() {#getYResolution--}
```
public float getYResolution()
```


Gets the vertical resolution of a barcode image being generated. Measured in dots per inch. The default value is 96.

**Returns:**
float - The vertical resolution of a barcode image being generated.
### getUseAutoCorrection() {#getUseAutoCorrection--}
```
public boolean getUseAutoCorrection()
```


Gets a value indicating whether an invalid barcode value should be corrected automatically (if possible) to fit the barcode's specification or an exception should be thrown to indicate the error. The default value is true. The auto-correction is not possible for Databar barcodes.

**Returns:**
boolean - A value indicating whether an invalid barcode value should be corrected automatically (if possible) to fit the barcode's specification or an exception should be thrown to indicate the error.
### setUseAutoCorrection(boolean value) {#setUseAutoCorrection-boolean-}
```
public void setUseAutoCorrection(boolean value)
```


Sets a value indicating whether an invalid barcode value should be corrected automatically (if possible) to fit the barcode's specification or an exception should be thrown to indicate the error. The default value is true. The auto-correction is not possible for Databar barcodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A value indicating whether an invalid barcode value should be corrected automatically (if possible) to fit the barcode's specification or an exception should be thrown to indicate the error. |

