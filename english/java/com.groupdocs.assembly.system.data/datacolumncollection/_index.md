---
title: DataColumnCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a collection of  objects for a .
type: docs
weight: 15
url: /java/com.groupdocs.assembly.system.data/datacolumncollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class DataColumnCollection implements Iterable<DataColumn>
```

Represents a collection of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects for a [DataTable](../../com.groupdocs.assembly.system.data/datatable). See also: https://referencesource.microsoft.com/#system.data/System/Data/DataColumnCollection.cs.

## Methods

| Method | Description |
| --- | --- |
| [add(DataColumn column)](#add-com.groupdocs.assembly.system.data.DataColumn-) | Adds the specified [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) to the columns collection.
 |
| [add(String columnName)](#add-java.lang.String-) | Creates and adds a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) with the specified name to the columns collection.
 |
| [add(String columnName, Class type)](#add-java.lang.String-java.lang.Class-) | Creates and adds a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) with the specified name and type to the columns collection.
 |
| [add(String columnName, Class type, int columnMapping, boolean allowAutoIncrement, boolean allowDBNull)](#add-java.lang.String-java.lang.Class-int-boolean-boolean-) | Creates and adds a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) with the specified name, type and specific values to the columns collection.
 |
| [indexOf(String columnName)](#indexOf-java.lang.String-) | Returns the index of a column specified by name.
 |
| [indexOf(DataColumn column)](#indexOf-com.groupdocs.assembly.system.data.DataColumn-) | Gets the index of a column specified by [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn).
 |
| [get(int index)](#get-int-) | Gets the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) from the collection at the specified index.
 |
| [get(String columnName)](#get-java.lang.String-) | Gets the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) from the collection with the specified name.
 |
| [contains(String name)](#contains-java.lang.String-) | Checks whether the collection contains a column with the specified name.
 |
| [remove(String name)](#remove-java.lang.String-) | Removes the DataColumn object that has the specified name from the collection.
 |
| [remove(DataColumn column)](#remove-com.groupdocs.assembly.system.data.DataColumn-) | Removes the DataColumn object that has the specified name from the collection.
 |
| [getCount()](#getCount--) |  |
| [iterator()](#iterator--) |  |
| [clear()](#clear--) | Clears the collection of any columns.
 |
### add(DataColumn column) {#add-com.groupdocs.assembly.system.data.DataColumn-}
```
public void add(DataColumn column)
```


Adds the specified [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) to the columns collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | new column to add
 |

### add(String columnName) {#add-java.lang.String-}
```
public void add(String columnName)
```


Creates and adds a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) with the specified name to the columns collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | new column
 |

### add(String columnName, Class type) {#add-java.lang.String-java.lang.Class-}
```
public DataColumn add(String columnName, Class type)
```


Creates and adds a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) with the specified name and type to the columns collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | name
 |
| type | java.lang.Class | data type
 |

**Returns:**
[DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) - created a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) instance.

### add(String columnName, Class type, int columnMapping, boolean allowAutoIncrement, boolean allowDBNull) {#add-java.lang.String-java.lang.Class-int-boolean-boolean-}
```
public DataColumn add(String columnName, Class type, int columnMapping, boolean allowAutoIncrement, boolean allowDBNull)
```


Creates and adds a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) with the specified name, type and specific values to the columns collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | name
 |
| type | java.lang.Class | data type
 |
| columnMapping | int | column mapping type
 |
| allowAutoIncrement | boolean | is auto increment allowed
 |
| allowDBNull | boolean | is DBNull value allowed
 |

**Returns:**
[DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) - created a [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) instance.

### indexOf(String columnName) {#indexOf-java.lang.String-}
```
public int indexOf(String columnName)
```


Returns the index of a column specified by name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | the name of column
 |

**Returns:**
int - the index of a column specified by name

### indexOf(DataColumn column) {#indexOf-com.groupdocs.assembly.system.data.DataColumn-}
```
public int indexOf(DataColumn column)
```


Gets the index of a column specified by [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) to find position for
 |

**Returns:**
int - the index of a specified [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn).

### get(int index) {#get-int-}
```
public DataColumn get(int index)
```


Gets the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) from the collection at the specified index.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | index of this column at this collection
 |

**Returns:**
[DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) - column with the specified name

### get(String columnName) {#get-java.lang.String-}
```
public DataColumn get(String columnName)
```


Gets the [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) from the collection with the specified name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | name of the column
 |

**Returns:**
[DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) - column with the specified name

### contains(String name) {#contains-java.lang.String-}
```
public boolean contains(String name)
```


Checks whether the collection contains a column with the specified name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | column name
 |

**Returns:**
boolean - true if column with the specified name exists

### remove(String name) {#remove-java.lang.String-}
```
public void remove(String name)
```


Removes the DataColumn object that has the specified name from the collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | name of the column
 |

### remove(DataColumn column) {#remove-com.groupdocs.assembly.system.data.DataColumn-}
```
public void remove(DataColumn column)
```


Removes the DataColumn object that has the specified name from the collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | name of the column
 |

### getCount() {#getCount--}
```
public int getCount()
```




**Returns:**
int - the total number of elements in a collection.

### iterator() {#iterator--}
```
public Iterator<DataColumn> iterator()
```




**Returns:**
java.util.Iterator<com.groupdocs.assembly.system.data.DataColumn>
### clear() {#clear--}
```
public void clear()
```


Clears the collection of any columns.


