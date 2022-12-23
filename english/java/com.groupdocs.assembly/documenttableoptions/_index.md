---
title: DocumentTableOptions
second_title: GroupDocs.Assembly for Java API Reference
description: Provides a set of options to control extraction of data from a document table.
type: docs
weight: 21
url: /java/com.groupdocs.assembly/documenttableoptions/
---
**Inheritance:**
java.lang.Object
```
public class DocumentTableOptions
```

Provides a set of options to control extraction of data from a document table.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentTableOptions()](#DocumentTableOptions--) | Creates a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [getMinRowIndex()](#getMinRowIndex--) | Gets the smallest zero-based index of a row to be extracted from a document table. |
| [setMinRowIndex(int value)](#setMinRowIndex-int-) | Sets the smallest zero-based index of a row to be extracted from a document table. |
| [getMaxRowIndex()](#getMaxRowIndex--) | Gets the largest zero-based index of a row to be extracted from a document table. |
| [setMaxRowIndex(int value)](#setMaxRowIndex-int-) | Sets the largest zero-based index of a row to be extracted from a document table. |
| [getMinColumnIndex()](#getMinColumnIndex--) | Gets the smallest zero-based index of a column to be extracted from a document table. |
| [setMinColumnIndex(int value)](#setMinColumnIndex-int-) | Sets the smallest zero-based index of a column to be extracted from a document table. |
| [getMaxColumnIndex()](#getMaxColumnIndex--) | Gets the largest zero-based index of a column to be extracted from a document table. |
| [setMaxColumnIndex(int value)](#setMaxColumnIndex-int-) | Sets the largest zero-based index of a column to be extracted from a document table. |
| [getFirstRowContainsColumnNames()](#getFirstRowContainsColumnNames--) | Gets a value indicating whether column names are to be obtained from the first extracted row of a document table. |
| [setFirstRowContainsColumnNames(boolean value)](#setFirstRowContainsColumnNames-boolean-) | Sets a value indicating whether column names are to be obtained from the first extracted row of a document table. |
### DocumentTableOptions() {#DocumentTableOptions--}
```
public DocumentTableOptions()
```


Creates a new instance of this class.

### getMinRowIndex() {#getMinRowIndex--}
```
public int getMinRowIndex()
```


Gets the smallest zero-based index of a row to be extracted from a document table. The default value is negative which means that the smallest row index is not limited.

**Returns:**
int - The smallest zero-based index of a row to be extracted from a document table.
### setMinRowIndex(int value) {#setMinRowIndex-int-}
```
public void setMinRowIndex(int value)
```


Sets the smallest zero-based index of a row to be extracted from a document table. The default value is negative which means that the smallest row index is not limited.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The smallest zero-based index of a row to be extracted from a document table. |

### getMaxRowIndex() {#getMaxRowIndex--}
```
public int getMaxRowIndex()
```


Gets the largest zero-based index of a row to be extracted from a document table. The default value is negative which means that the largest row index is not limited.

**Returns:**
int - The largest zero-based index of a row to be extracted from a document table.
### setMaxRowIndex(int value) {#setMaxRowIndex-int-}
```
public void setMaxRowIndex(int value)
```


Sets the largest zero-based index of a row to be extracted from a document table. The default value is negative which means that the largest row index is not limited.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The largest zero-based index of a row to be extracted from a document table. |

### getMinColumnIndex() {#getMinColumnIndex--}
```
public int getMinColumnIndex()
```


Gets the smallest zero-based index of a column to be extracted from a document table. The default value is negative which means that the smallest column index is not limited.

**Returns:**
int - The smallest zero-based index of a column to be extracted from a document table.
### setMinColumnIndex(int value) {#setMinColumnIndex-int-}
```
public void setMinColumnIndex(int value)
```


Sets the smallest zero-based index of a column to be extracted from a document table. The default value is negative which means that the smallest column index is not limited.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The smallest zero-based index of a column to be extracted from a document table. |

### getMaxColumnIndex() {#getMaxColumnIndex--}
```
public int getMaxColumnIndex()
```


Gets the largest zero-based index of a column to be extracted from a document table. The default value is negative which means that the largest column index is not limited.

**Returns:**
int - The largest zero-based index of a column to be extracted from a document table.
### setMaxColumnIndex(int value) {#setMaxColumnIndex-int-}
```
public void setMaxColumnIndex(int value)
```


Sets the largest zero-based index of a column to be extracted from a document table. The default value is negative which means that the largest column index is not limited.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The largest zero-based index of a column to be extracted from a document table. |

### getFirstRowContainsColumnNames() {#getFirstRowContainsColumnNames--}
```
public boolean getFirstRowContainsColumnNames()
```


Gets a value indicating whether column names are to be obtained from the first extracted row of a document table. The default value is false. If column names are not set to be obtained from the first extracted row of a document table, default column names are used instead. For documents of Spreadsheet file formats, default column names are defined as A, B, C, ... Z, AA, AB, and so on. For documents of other file formats, default column names are defined as Column1, Column2, Column3, and so on.

**Returns:**
boolean - A value indicating whether column names are to be obtained from the first extracted row of a document table.
### setFirstRowContainsColumnNames(boolean value) {#setFirstRowContainsColumnNames-boolean-}
```
public void setFirstRowContainsColumnNames(boolean value)
```


Sets a value indicating whether column names are to be obtained from the first extracted row of a document table. The default value is false. If column names are not set to be obtained from the first extracted row of a document table, default column names are used instead. For documents of Spreadsheet file formats, default column names are defined as A, B, C, ... Z, AA, AB, and so on. For documents of other file formats, default column names are defined as Column1, Column2, Column3, and so on.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A value indicating whether column names are to be obtained from the first extracted row of a document table. |

