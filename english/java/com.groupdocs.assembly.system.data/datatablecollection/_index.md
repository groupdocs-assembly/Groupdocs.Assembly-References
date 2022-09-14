---
title: DataTableCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents the collection of tables for the com.groupdocs.assembly.system.data.DataSet.
type: docs
weight: 26
url: /java/com.groupdocs.assembly.system.data/datatablecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class DataTableCollection implements Iterable
```

Represents the collection of tables for the com.groupdocs.assembly.system.data.DataSet.
## Methods

| Method | Description |
| --- | --- |
| [iterator()](#iterator--) |  |
| [get(String name)](#get-java.lang.String-) | Gets the com.groupdocs.assembly.system.data.DataTable object with the specified name. |
| [get(String name, String tableNamespace)](#get-java.lang.String-java.lang.String-) | Gets the com.groupdocs.assembly.system.data.DataTable object with the specified name in the specified namespace. |
| [add(DataTable table)](#add-com.groupdocs.assembly.system.data.DataTable-) | Adds the specified DataTable to the collection. |
| [add(String name)](#add-java.lang.String-) | Creates a com.groupdocs.assembly.system.data.DataTable object by using the specified name and adds it to the collection. |
| [get(int index)](#get-int-) | Gets the com.groupdocs.assembly.system.data.DataTable object at the specified index. |
| [getCount()](#getCount--) |  |
| [contains(String name)](#contains-java.lang.String-) | Gets a value that indicates whether a com.groupdocs.assembly.system.data.DataTable object with the specified name exists in the collection. |
### iterator() {#iterator--}
```
public final Iterator iterator()
```




**Returns:**
java.util.Iterator
### get(String name) {#get-java.lang.String-}
```
public final DataTable get(String name)
```


Gets the com.groupdocs.assembly.system.data.DataTable object with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the DataTable to find. |

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - A com.groupdocs.assembly.system.data.DataTable with the specified name; otherwise null if the com.groupdocs.assembly.system.data.DataTable does not exist.
### get(String name, String tableNamespace) {#get-java.lang.String-java.lang.String-}
```
public final DataTable get(String name, String tableNamespace)
```


Gets the com.groupdocs.assembly.system.data.DataTable object with the specified name in the specified namespace.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the DataTable to find. |
| tableNamespace | java.lang.String | The name of the com.groupdocs.assembly.system.data.DataTable namespace to look in. |

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - A com.groupdocs.assembly.system.data.DataTable with the specified name; otherwise null if the com.groupdocs.assembly.system.data.DataTable does not exist.
### add(DataTable table) {#add-com.groupdocs.assembly.system.data.DataTable-}
```
public final void add(DataTable table)
```


Adds the specified DataTable to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| table | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The DataTable object to add. |

### add(String name) {#add-java.lang.String-}
```
public final DataTable add(String name)
```


Creates a com.groupdocs.assembly.system.data.DataTable object by using the specified name and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name to give the created com.groupdocs.assembly.system.data.DataTable. |

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - The newly created com.groupdocs.assembly.system.data.DataTable.
### get(int index) {#get-int-}
```
public final DataTable get(int index)
```


Gets the com.groupdocs.assembly.system.data.DataTable object at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the com.groupdocs.assembly.system.data.DataTable to find. |

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - A com.groupdocs.assembly.system.data.DataTable.
### getCount() {#getCount--}
```
public final int getCount()
```




**Returns:**
int - total number of items in this collection.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Gets a value that indicates whether a com.groupdocs.assembly.system.data.DataTable object with the specified name exists in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the com.groupdocs.assembly.system.data.DataTable to find. |

**Returns:**
boolean - true if the specified table exists; otherwise false.
