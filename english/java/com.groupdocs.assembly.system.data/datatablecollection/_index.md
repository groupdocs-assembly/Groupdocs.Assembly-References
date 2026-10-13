---
title: DataTableCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents the collection of tables for the .
type: docs
weight: 26
url: /java/com.groupdocs.assembly.system.data/datatablecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class DataTableCollection implements Iterable<DataTable>
```

Represents the collection of tables for the [DataSet](../../com.groupdocs.assembly.system.data/dataset).

## Methods

| Method | Description |
| --- | --- |
| [iterator()](#iterator--) |  |
| [get(String name)](#get-java.lang.String-) | Case-insensitive search is performed, if [DataTable](../../com.groupdocs.assembly.system.data/datatable) is not found by the original name.
 |
| [get(String name, String namespace)](#get-java.lang.String-java.lang.String-) |  |
| [add(DataTable dataTable)](#add-com.groupdocs.assembly.system.data.DataTable-) | Adds a table to the collection.
 |
| [add(String dataTableName)](#add-java.lang.String-) | Adds and return table to the collection.
 |
| [get(int index)](#get-int-) |  |
| [getCount()](#getCount--) |  |
| [contains(String name)](#contains-java.lang.String-) |  |
### iterator() {#iterator--}
```
public Iterator<DataTable> iterator()
```




**Returns:**
java.util.Iterator<com.groupdocs.assembly.system.data.DataTable>
### get(String name) {#get-java.lang.String-}
```
public DataTable get(String name)
```


Case-insensitive search is performed, if [DataTable](../../com.groupdocs.assembly.system.data/datatable) is not found by the original name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | table name
 |

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - a DataTable by its name. Returns null if not found.

### get(String name, String namespace) {#get-java.lang.String-java.lang.String-}
```
public DataTable get(String name, String namespace)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| namespace | java.lang.String |  |

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable)
### add(DataTable dataTable) {#add-com.groupdocs.assembly.system.data.DataTable-}
```
public void add(DataTable dataTable)
```


Adds a table to the collection. The table name must be unique within the collection, otherwise will throw an exception.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | table will be added into this collection
 |

### add(String dataTableName) {#add-java.lang.String-}
```
public DataTable add(String dataTableName)
```


Adds and return table to the collection. The table name must be unique within the collection, otherwise will throw an exception.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataTableName | java.lang.String | name of the table that will be added into this collection
 |

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable)
### get(int index) {#get-int-}
```
public DataTable get(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | position of the table in this collection
 |

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - a [DataTable](../../com.groupdocs.assembly.system.data/datatable) instance by its index.

### getCount() {#getCount--}
```
public int getCount()
```




**Returns:**
int - total number of items in this collection.

### contains(String name) {#contains-java.lang.String-}
```
public boolean contains(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | table name
 |

**Returns:**
boolean - true if this collection contains [DataTable](../../com.groupdocs.assembly.system.data/datatable) with the given name.

