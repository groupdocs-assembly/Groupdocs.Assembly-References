---
title: DataView
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a databindable customized view of a  for sorting filtering searching editing and navigation.
type: docs
weight: 28
url: /java/com.groupdocs.assembly.system.data/dataview/
---
**Inheritance:**
java.lang.Object
```
public class DataView
```

Represents a databindable, customized view of a [DataTable](../../com.groupdocs.assembly.system.data/datatable) for sorting, filtering, searching, editing, and navigation.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataView(DataTable table)](#DataView-com.groupdocs.assembly.system.data.DataTable-) | Initializes a new instance of the [DataView](../../com.groupdocs.assembly.system.data/dataview) class with the specified [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of records in the [DataView](../../com.groupdocs.assembly.system.data/dataview). |
| [getTable()](#getTable--) | Gets the source [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [get(int recordIndex)](#get-int-) | Gets a row of data from a specified table. |
| [close()](#close--) | Closes the [DataView](../../com.groupdocs.assembly.system.data/dataview). |
### DataView(DataTable table) {#DataView-com.groupdocs.assembly.system.data.DataTable-}
```
public DataView(DataTable table)
```


Initializes a new instance of the [DataView](../../com.groupdocs.assembly.system.data/dataview) class with the specified [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| table | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | A [DataTable](../../com.groupdocs.assembly.system.data/datatable) to add to the [DataView](../../com.groupdocs.assembly.system.data/dataview). |

### getCount() {#getCount--}
```
public int getCount()
```


Gets the number of records in the [DataView](../../com.groupdocs.assembly.system.data/dataview).

**Returns:**
int - The number of records in the [DataView](../../com.groupdocs.assembly.system.data/dataview).
### getTable() {#getTable--}
```
public DataTable getTable()
```


Gets the source [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - A [DataTable](../../com.groupdocs.assembly.system.data/datatable) that provides the data for this view.
### get(int recordIndex) {#get-int-}
```
public DataRowView get(int recordIndex)
```


Gets a row of data from a specified table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordIndex | int | The index of a record in the [DataTable](../../com.groupdocs.assembly.system.data/datatable). |

**Returns:**
[DataRowView](../../com.groupdocs.assembly.system.data/datarowview) - A [DataRowView](../../com.groupdocs.assembly.system.data/datarowview) of the row that you want.
### close() {#close--}
```
public void close()
```


Closes the [DataView](../../com.groupdocs.assembly.system.data/dataview).

