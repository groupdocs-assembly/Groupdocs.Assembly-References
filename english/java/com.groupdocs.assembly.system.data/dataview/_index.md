---
title: DataView
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a data bindable customized view of a DataTable for sorting filtering searching editing and navigation.
type: docs
weight: 28
url: /java/com.groupdocs.assembly.system.data/dataview/
---
**Inheritance:**
java.lang.Object
```
public class DataView
```

Represents a data bindable, customized view of a DataTable for sorting, filtering, searching, editing, and navigation. The DataView does not store data, but instead represents a connected view of its corresponding DataTable. Changes to the DataView\\u2019s data will affect the DataTable. Changes to the DataTable\\u2019s data will affect all DataViews associated with it.

## Constructors

| Constructor | Description |
| --- | --- |
| [DataView(DataTable table)](#DataView-com.groupdocs.assembly.system.data.DataTable-) | Initializes a new instance of the DataView class with the specified DataTable.
 |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) |  |
| [getTable()](#getTable--) |  |
| [get(int i)](#get-int-) |  |
| [close()](#close--) |  |
### DataView(DataTable table) {#DataView-com.groupdocs.assembly.system.data.DataTable-}
```
public DataView(DataTable table)
```


Initializes a new instance of the DataView class with the specified DataTable.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| table | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | table to be represented by this view.
 |

### getCount() {#getCount--}
```
public int getCount()
```




**Returns:**
int - the number of records in the DataView after RowFilter and RowStateFilter have been applied.

### getTable() {#getTable--}
```
public DataTable getTable()
```




**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - the source DataTable.

### get(int i) {#get-int-}
```
public DataRowView get(int i)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int | row position
 |

**Returns:**
[DataRowView](../../com.groupdocs.assembly.system.data/datarowview) - the element at the specified index.

### close() {#close--}
```
public void close()
```




