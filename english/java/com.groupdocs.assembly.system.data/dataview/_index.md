---
title: DataView
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a databindable customized view of a com.groupdocs.assembly.system.data.DataTable for sorting filtering searching editing and navigation.
type: docs
weight: 28
url: /java/com.groupdocs.assembly.system.data/dataview/
---
**Inheritance:**
java.lang.Object
```
public class DataView
```

Represents a databindable, customized view of a com.groupdocs.assembly.system.data.DataTable for sorting, filtering, searching, editing, and navigation.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataView(DataTable table)](#DataView-com.groupdocs.assembly.system.data.DataTable-) | Initializes a new instance of the com.groupdocs.assembly.system.data.DataView class with the specified com.groupdocs.assembly.system.data.DataTable. |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of records in the com.groupdocs.assembly.system.data.DataView. |
| [getTable()](#getTable--) | Gets the source com.groupdocs.assembly.system.data.DataTable. |
| [get(int recordIndex)](#get-int-) | Gets a row of data from a specified table. |
| [close()](#close--) | Closes the com.groupdocs.assembly.system.data.DataView. |
### DataView(DataTable table) {#DataView-com.groupdocs.assembly.system.data.DataTable-}
```
public DataView(DataTable table)
```


Initializes a new instance of the com.groupdocs.assembly.system.data.DataView class with the specified com.groupdocs.assembly.system.data.DataTable.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| table | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | A com.groupdocs.assembly.system.data.DataTable to add to the com.groupdocs.assembly.system.data.DataView. |

### getCount() {#getCount--}
```
public int getCount()
```


Gets the number of records in the com.groupdocs.assembly.system.data.DataView.

**Returns:**
int - The number of records in the com.groupdocs.assembly.system.data.DataView.
### getTable() {#getTable--}
```
public DataTable getTable()
```


Gets the source com.groupdocs.assembly.system.data.DataTable.

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - A com.groupdocs.assembly.system.data.DataTable that provides the data for this view.
### get(int recordIndex) {#get-int-}
```
public DataRowView get(int recordIndex)
```


Gets a row of data from a specified table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recordIndex | int | The index of a record in the com.groupdocs.assembly.system.data.DataTable. |

**Returns:**
[DataRowView](../../com.groupdocs.assembly.system.data/datarowview) - A com.groupdocs.assembly.system.data.DataRowView of the row that you want.
### close() {#close--}
```
public void close()
```


Closes the com.groupdocs.assembly.system.data.DataView.

