---
title: DataRowCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a collection of rows for a com.groupdocs.assembly.system.data.DataTable.
type: docs
weight: 21
url: /java/com.groupdocs.assembly.system.data/datarowcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class DataRowCollection implements Iterable
```

Represents a collection of rows for a com.groupdocs.assembly.system.data.DataTable.
## Methods

| Method | Description |
| --- | --- |
| [add(DataRow row)](#add-com.groupdocs.assembly.system.data.DataRow-) | Adds the specified com.groupdocs.assembly.system.data.DataRow to the com.groupdocs.assembly.system.data.DataRowCollection object. |
| [add(Object[] values)](#add-java.lang.Object...-) | Creates a row using specified values and adds it to the com.groupdocs.assembly.system.data.DataRowCollection. |
| [get(int index)](#get-int-) | Gets the row at the specified index. |
| [getCount()](#getCount--) | Gets the total number of com.groupdocs.assembly.system.data.DataRow objects in this collection. |
| [iterator()](#iterator--) | Gets an java.util.Iterator for this collection. |
| [clear()](#clear--) | Clears the collection of all rows. |
| [insertAt(DataRow row, int pos)](#insertAt-com.groupdocs.assembly.system.data.DataRow-int-) | Inserts a new row into the collection at the specified location. |
| [removeAt(int index)](#removeAt-int-) | Removes the row at the specified index from the collection. |
| [find(String primaryKeyValue)](#find-java.lang.String-) | Gets the row specified by the primary key value. |
| [find(Object[] keys)](#find-java.lang.Object---) | Gets the row that contains the specified primary key values. |
| [get(Object[] values)](#get-java.lang.Object---) | Gets the row that contains the specified values. |
### add(DataRow row) {#add-com.groupdocs.assembly.system.data.DataRow-}
```
public void add(DataRow row)
```


Adds the specified com.groupdocs.assembly.system.data.DataRow to the com.groupdocs.assembly.system.data.DataRowCollection object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | [DataRow](../../com.groupdocs.assembly.system.data/datarow) | The com.groupdocs.assembly.system.data.DataRow to add. |

### add(Object[] values) {#add-java.lang.Object...-}
```
public void add(Object[] values)
```


Creates a row using specified values and adds it to the com.groupdocs.assembly.system.data.DataRowCollection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | java.lang.Object[] | The array of values that are used to create the new row. |

### get(int index) {#get-int-}
```
public DataRow get(int index)
```


Gets the row at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the row to return. |

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - The specified com.groupdocs.assembly.system.data.DataRow.
### getCount() {#getCount--}
```
public int getCount()
```


Gets the total number of com.groupdocs.assembly.system.data.DataRow objects in this collection.

**Returns:**
int - The total number of com.groupdocs.assembly.system.data.DataRow objects in this collection.
### iterator() {#iterator--}
```
public Iterator iterator()
```


Gets an java.util.Iterator for this collection.

**Returns:**
java.util.Iterator - An java.util.Iterator for this collection.
### clear() {#clear--}
```
public void clear()
```


Clears the collection of all rows.

### insertAt(DataRow row, int pos) {#insertAt-com.groupdocs.assembly.system.data.DataRow-int-}
```
public void insertAt(DataRow row, int pos)
```


Inserts a new row into the collection at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | [DataRow](../../com.groupdocs.assembly.system.data/datarow) | The com.groupdocs.assembly.system.data.DataRow to add. |
| pos | int | The (zero-based) location in the collection where you want to add the DataRow. |

### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


Removes the row at the specified index from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the row to remove. |

### find(String primaryKeyValue) {#find-java.lang.String-}
```
public DataRow find(String primaryKeyValue)
```


Gets the row specified by the primary key value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| primaryKeyValue | java.lang.String | The primary key value of the DataRow to find. |

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - A DataRow that contains the primary key value specified; otherwise a null value if the primary key value does not exist in the DataRowCollection.
### find(Object[] keys) {#find-java.lang.Object---}
```
public DataRow find(Object[] keys)
```


Gets the row that contains the specified primary key values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| keys | java.lang.Object[] | An array of primary key values to find. The type of the array is Object. |

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - A com.groupdocs.assembly.system.data.DataRow object that contains the primary key values specified; otherwise a null value if the primary key value does not exist in the com.groupdocs.assembly.system.data.DataRowCollection.
### get(Object[] values) {#get-java.lang.Object---}
```
public DataRow get(Object[] values)
```


Gets the row that contains the specified values. If there is primary key's column(s) present then the index will be used. If there is no index then simple linear scan is used. Be carefully with that because it could take a significant amount of time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | java.lang.Object[] | row's data |

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - found row or `null`
