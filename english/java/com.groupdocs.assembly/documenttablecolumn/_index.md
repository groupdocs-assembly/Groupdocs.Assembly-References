---
title: DocumentTableColumn
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a single column of a particular  object.
type: docs
weight: 18
url: /java/com.groupdocs.assembly/documenttablecolumn/
---
**Inheritance:**
java.lang.Object
```
public class DocumentTableColumn
```

Represents a single column of a particular [DocumentTable](../../com.groupdocs.assembly/documenttable) object.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the name of this column used to access the column's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). |
| [setName(String value)](#setName-java.lang.String-) | Sets the name of this column used to access the column's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). |
| [getIndexInDocument()](#getIndexInDocument--) | Gets the original zero-based index of the corresponding table column as per the source document. |
| [getType()](#getType--) | Gets the type of cell values in this column. |
| [setType(Class value)](#setType-java.lang.Class-) | Sets the type of cell values in this column. |
| [getAllowsNull()](#getAllowsNull--) | Gets a value indicating whether cells in this column contain null values or not. |
### getName() {#getName--}
```
public String getName()
```


Gets the name of this column used to access the column's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler).

If the column's name is read from a document (see [DocumentTableOptions.getFirstRowContainsColumnNames()](../../com.groupdocs.assembly/documenttableoptions\#getFirstRowContainsColumnNames--) / [DocumentTableOptions.setFirstRowContainsColumnNames(boolean)](../../com.groupdocs.assembly/documenttableoptions\#setFirstRowContainsColumnNames-boolean-)), the name is automatically corrected so that it to be valid. However, if the column's name is set manually through this property and the name is invalid, an exception is thrown.

The column's name is considered to be valid, if the following conditions are met:

 *  The name is not empty.
 *  The name's first character is a letter or underscore.
 *  The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '\#', '$'.
 *  The corresponding [DocumentTable](../../com.groupdocs.assembly/documenttable) object does not contain a [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) instance with the same name.

**Returns:**
java.lang.String - The name of this column used to access the column's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler).
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets the name of this column used to access the column's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler).

If the column's name is read from a document (see [DocumentTableOptions.getFirstRowContainsColumnNames()](../../com.groupdocs.assembly/documenttableoptions\#getFirstRowContainsColumnNames--) / [DocumentTableOptions.setFirstRowContainsColumnNames(boolean)](../../com.groupdocs.assembly/documenttableoptions\#setFirstRowContainsColumnNames-boolean-)), the name is automatically corrected so that it to be valid. However, if the column's name is set manually through this property and the name is invalid, an exception is thrown.

The column's name is considered to be valid, if the following conditions are met:

 *  The name is not empty.
 *  The name's first character is a letter or underscore.
 *  The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '\#', '$'.
 *  The corresponding [DocumentTable](../../com.groupdocs.assembly/documenttable) object does not contain a [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) instance with the same name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of this column used to access the column's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). |

### getIndexInDocument() {#getIndexInDocument--}
```
public int getIndexInDocument()
```


Gets the original zero-based index of the corresponding table column as per the source document. Depending on [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions) specified, this index may differ from the index of this [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) instance within the column collection of the corresponding [DocumentTable](../../com.groupdocs.assembly/documenttable) instance.

**Returns:**
int - The original zero-based index of the corresponding table column as per the source document.
### getType() {#getType--}
```
public Class getType()
```


Gets the type of cell values in this column.

For documents of non-Spreadsheet file formats, the initial type is always automatically determined as string. For documents of Spreadsheet file formats, the initial type is automatically determined depending on corresponding cell values.

If cells of a particular Spreadsheet column contain values of different types, then the column's initial type is also automatically determined as string.

**Returns:**
java.lang.Class - The type of cell values in this column.
### setType(Class value) {#setType-java.lang.Class-}
```
public void setType(Class value)
```


Sets the type of cell values in this column.

For documents of non-Spreadsheet file formats, the initial type is always automatically determined as string. For documents of Spreadsheet file formats, the initial type is automatically determined depending on corresponding cell values.

If cells of a particular Spreadsheet column contain values of different types, then the column's initial type is also automatically determined as string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Class | The type of cell values in this column. |

### getAllowsNull() {#getAllowsNull--}
```
public boolean getAllowsNull()
```


Gets a value indicating whether cells in this column contain null values or not. Undefined and error values in cells of Spreadsheet documents are also considered to be null.

**Returns:**
boolean - A value indicating whether cells in this column contain null values or not.
