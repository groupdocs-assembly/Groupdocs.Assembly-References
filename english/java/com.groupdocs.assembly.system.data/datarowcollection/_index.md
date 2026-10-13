---
title: DataRowCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a collection of rows for a
type: docs
weight: 21
url: /java/com.groupdocs.assembly.system.data/datarowcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class DataRowCollection implements Iterable<DataRow>
```

Represents a collection of rows for a [DataTable](../../com.groupdocs.assembly.system.data/datatable)

## Methods

| Method | Description |
| --- | --- |
| [add(DataRow row)](#add-com.groupdocs.assembly.system.data.DataRow-) | Creates a row using specified [DataRow](../../com.groupdocs.assembly.system.data/datarow).
 |
| [add(Object[] values)](#add-java.lang.Object...-) | Creates a row using specified values and adds it to the DataRowCollection.
 |
| [get(int index)](#get-int-) |  |
| [getCount()](#getCount--) |  |
| [iterator()](#iterator--) |  |
| [clear()](#clear--) | Clears the collection of all rows.
 |
| [insertAt(DataRow row, int idx)](#insertAt-com.groupdocs.assembly.system.data.DataRow-int-) | Inserts a new row into the collection at the specified location.
 |
| [removeAt(int idx)](#removeAt-int-) | Removes the row at the specified index from the collection.
 |
| [find(String primaryKeyValue)](#find-java.lang.String-) | Gets the row specified by the primary key value.
 |
| [find(Object[] keys)](#find-java.lang.Object---) | Gets the row that contains the specified primary key values.
 |
| [get(Object[] values)](#get-java.lang.Object---) | Gets the row that contains the specified values.
 |
### add(DataRow row) {#add-com.groupdocs.assembly.system.data.DataRow-}
```
public void add(DataRow row)
```


Creates a row using specified [DataRow](../../com.groupdocs.assembly.system.data/datarow).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | [DataRow](../../com.groupdocs.assembly.system.data/datarow) | The DataRow to add.
 |

### add(Object[] values) {#add-java.lang.Object...-}
```
public void add(Object[] values)
```


Creates a row using specified values and adds it to the DataRowCollection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | java.lang.Object[] | The array of values that are used to create the new row.
 |

### get(int index) {#get-int-}
```
public DataRow get(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the row to return.
 |

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - the row at the specified index.

### getCount() {#getCount--}
```
public int getCount()
```




**Returns:**
int - the total number of DataRow objects in this collection. (

### iterator() {#iterator--}
```
public Iterator<DataRow> iterator()
```




**Returns:**
java.util.Iterator<com.groupdocs.assembly.system.data.DataRow>
### clear() {#clear--}
```
public void clear()
```


Clears the collection of all rows.


### insertAt(DataRow row, int idx) {#insertAt-com.groupdocs.assembly.system.data.DataRow-int-}
```
public void insertAt(DataRow row, int idx)
```


Inserts a new row into the collection at the specified location.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | [DataRow](../../com.groupdocs.assembly.system.data/datarow) | The DataRow to add.
 |
| idx | int | The (zero-based) location in the collection where you want to add the DataRow.
 |

### removeAt(int idx) {#removeAt-int-}
```
public void removeAt(int idx)
```


Removes the row at the specified index from the collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| idx | int | The index of the row to remove.
 |

### find(String primaryKeyValue) {#find-java.lang.String-}
```
public DataRow find(String primaryKeyValue)
```


Gets the row specified by the primary key value.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| primaryKeyValue | java.lang.String | The primary key value of the DataRow to find.
 |

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
| keys | java.lang.Object[] | An array of primary key values to find. The type of the array is Object.
 |

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - A DataRow object that contains the primary key values specified; otherwise a null value if the primary key value does not exist in the DataRowCollection.

### get(Object[] values) {#get-java.lang.Object---}
```
public DataRow get(Object[] values)
```


Gets the row that contains the specified values. If there is primary key's column(s) present then the index will be used. If there is no index then simple linear scan is used. Be carefully with that because it could take a significant amount of time.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| values | java.lang.Object[] | row's data
 |

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - found row or `null`

