---
title: DataColumnCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a collection of com.groupdocs.assembly.system.data.DataColumn objects for a com.groupdocs.assembly.system.data.DataTable.
type: docs
weight: 15
url: /java/com.groupdocs.assembly.system.data/datacolumncollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class DataColumnCollection implements Iterable
```

Represents a collection of com.groupdocs.assembly.system.data.DataColumn objects for a com.groupdocs.assembly.system.data.DataTable.
## Methods

| Method | Description |
| --- | --- |
| [add(DataColumn column)](#add-com.groupdocs.assembly.system.data.DataColumn-) | Creates and adds the specified com.groupdocs.assembly.system.data.DataColumn object to the com.groupdocs.assembly.system.data.DataColumnCollection. |
| [add(String columnName)](#add-java.lang.String-) | Creates and adds a com.groupdocs.assembly.system.data.DataColumn object that has the specified name to the com.groupdocs.assembly.system.data.DataColumnCollection. |
| [add(String columnName, Class type)](#add-java.lang.String-java.lang.Class-) | Creates and adds a com.groupdocs.assembly.system.data.DataColumn object that has the specified name and type to the com.groupdocs.assembly.system.data.DataColumnCollection. |
| [add(String columnName, Class type, int columnMapping, boolean allowAutoIncrement, boolean allowDBNull)](#add-java.lang.String-java.lang.Class-int-boolean-boolean-) | Creates and adds a com.groupdocs.assembly.system.data.DataColumn with the specified name, type and specific values to the columns collection. |
| [indexOf(String columnName)](#indexOf-java.lang.String-) | Gets the index of the column with the specific name (the name is not case sensitive). |
| [indexOf(DataColumn column)](#indexOf-com.groupdocs.assembly.system.data.DataColumn-) | Gets the index of a column specified by name. |
| [get(int index)](#get-int-) | Gets the com.groupdocs.assembly.system.data.DataColumn from the collection at the specified index. |
| [get(String name)](#get-java.lang.String-) | Gets the com.groupdocs.assembly.system.data.DataColumn from the collection with the specified name. |
| [contains(String name)](#contains-java.lang.String-) | Checks whether the collection contains a column with the specified name. |
| [remove(String name)](#remove-java.lang.String-) | Removes the com.groupdocs.assembly.system.data.DataColumn object that has the specified name from the collection. |
| [remove(DataColumn column)](#remove-com.groupdocs.assembly.system.data.DataColumn-) | Removes the specified com.groupdocs.assembly.system.data.DataColumn object from the collection. |
| [getCount()](#getCount--) |  |
| [iterator()](#iterator--) |  |
| [clear()](#clear--) | Clears the collection of any columns. |
### add(DataColumn column) {#add-com.groupdocs.assembly.system.data.DataColumn-}
```
public final void add(DataColumn column)
```


Creates and adds the specified com.groupdocs.assembly.system.data.DataColumn object to the com.groupdocs.assembly.system.data.DataColumnCollection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The com.groupdocs.assembly.system.data.DataColumn to add. |

### add(String columnName) {#add-java.lang.String-}
```
public final void add(String columnName)
```


Creates and adds a com.groupdocs.assembly.system.data.DataColumn object that has the specified name to the com.groupdocs.assembly.system.data.DataColumnCollection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | The name of the column. |

### add(String columnName, Class type) {#add-java.lang.String-java.lang.Class-}
```
public final DataColumn add(String columnName, Class type)
```


Creates and adds a com.groupdocs.assembly.system.data.DataColumn object that has the specified name and type to the com.groupdocs.assembly.system.data.DataColumnCollection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | The com.groupdocs.assembly.system.data.DataColumn\#getColumnName() / com.groupdocs.assembly.system.data.DataColumn\#setColumnName(java.lang.String) to use when you create the column. |
| type | java.lang.Class | The com.groupdocs.assembly.system.data.DataColumn\#getDataType() / com.groupdocs.assembly.system.data.DataColumn\#setDataType(java.lang.Class) of the new column. |

**Returns:**
[DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) - The newly created com.groupdocs.assembly.system.data.DataColumn.
### add(String columnName, Class type, int columnMapping, boolean allowAutoIncrement, boolean allowDBNull) {#add-java.lang.String-java.lang.Class-int-boolean-boolean-}
```
public final DataColumn add(String columnName, Class type, int columnMapping, boolean allowAutoIncrement, boolean allowDBNull)
```


Creates and adds a com.groupdocs.assembly.system.data.DataColumn with the specified name, type and specific values to the columns collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | name |
| type | java.lang.Class | data type |
| columnMapping | int | column mapping type |
| allowAutoIncrement | boolean | is auto increment allowed |
| allowDBNull | boolean | is DBNull value allowed |

**Returns:**
[DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) - created a com.groupdocs.assembly.system.data.DataColumn instance.
### indexOf(String columnName) {#indexOf-java.lang.String-}
```
public final int indexOf(String columnName)
```


Gets the index of the column with the specific name (the name is not case sensitive).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | The name of the column to find. |

**Returns:**
int - The zero-based index of the column with the specified name, or -1 if the column does not exist in the collection.
### indexOf(DataColumn column) {#indexOf-com.groupdocs.assembly.system.data.DataColumn-}
```
public final int indexOf(DataColumn column)
```


Gets the index of a column specified by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The name of the column to return. |

**Returns:**
int - The index of the column specified by  column  if it is found; otherwise, -1.
### get(int index) {#get-int-}
```
public final DataColumn get(int index)
```


Gets the com.groupdocs.assembly.system.data.DataColumn from the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the column to return. |

**Returns:**
[DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) - The com.groupdocs.assembly.system.data.DataColumn at the specified index.
### get(String name) {#get-java.lang.String-}
```
public final DataColumn get(String name)
```


Gets the com.groupdocs.assembly.system.data.DataColumn from the collection with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The com.groupdocs.assembly.system.data.DataColumn\#getColumnName() / com.groupdocs.assembly.system.data.DataColumn\#setColumnName(java.lang.String) of the column to return. |

**Returns:**
[DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) - The com.groupdocs.assembly.system.data.DataColumn in the collection with the specified com.groupdocs.assembly.system.data.DataColumn\#getColumnName() / com.groupdocs.assembly.system.data.DataColumn\#setColumnName(java.lang.String); otherwise a null value if the com.groupdocs.assembly.system.data.DataColumn does not exist.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Checks whether the collection contains a column with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The com.groupdocs.assembly.system.data.DataColumn\#getColumnName() / com.groupdocs.assembly.system.data.DataColumn\#setColumnName(java.lang.String) of the column to look for. |

**Returns:**
boolean - true if a column exists with this name; otherwise, false.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Removes the com.groupdocs.assembly.system.data.DataColumn object that has the specified name from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the column to remove. |

### remove(DataColumn column) {#remove-com.groupdocs.assembly.system.data.DataColumn-}
```
public final void remove(DataColumn column)
```


Removes the specified com.groupdocs.assembly.system.data.DataColumn object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The com.groupdocs.assembly.system.data.DataColumn to remove. |

### getCount() {#getCount--}
```
public final int getCount()
```




**Returns:**
int - the total number of elements in a collection.
### iterator() {#iterator--}
```
public final Iterator iterator()
```




**Returns:**
java.util.Iterator
### clear() {#clear--}
```
public final void clear()
```


Clears the collection of any columns.

