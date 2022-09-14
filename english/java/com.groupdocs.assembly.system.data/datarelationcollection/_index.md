---
title: DataRelationCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents the collection of com.groupdocs.assembly.system.data.DataRelation objects for this com.groupdocs.assembly.system.data.DataSet.
type: docs
weight: 19
url: /java/com.groupdocs.assembly.system.data/datarelationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class DataRelationCollection implements Iterable
```

Represents the collection of com.groupdocs.assembly.system.data.DataRelation objects for this com.groupdocs.assembly.system.data.DataSet.
## Methods

| Method | Description |
| --- | --- |
| [add(DataRelation relation)](#add-com.groupdocs.assembly.system.data.DataRelation-) | Adds a com.groupdocs.assembly.system.data.DataRelation to the com.groupdocs.assembly.system.data.DataRelationCollection. |
| [add(DataTable parentTable, DataTable childTable, String parentColumnName, String childColumnName)](#add-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String-java.lang.String-) | Adds a relation to the collection. |
| [add(DataTable parentTable, DataTable childTable, String[] parentColumnNames, String[] childColumnNames)](#add-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String---java.lang.String---) | Adds a relation to the collection. |
| [add(String name, DataColumn parentColumn, DataColumn childColumn, boolean createConstraints)](#add-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-boolean-) | Creates a com.groupdocs.assembly.system.data.DataRelation with the specified name, parent and child columns, with optional constraints according to the value of the  createConstraints  parameter, and adds it to the collection. |
| [add(DataColumn parentColumn, DataColumn childColumn)](#add-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-) | Creates a com.groupdocs.assembly.system.data.DataRelation with a specified parent and child column, and adds it to the collection. |
| [add(String name, DataColumn parentColumn, DataColumn childColumn)](#add-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-) | Creates a com.groupdocs.assembly.system.data.DataRelation with the specified name, and parent and child columns, and adds it to the collection. |
| [iterator()](#iterator--) |  |
| [getCount()](#getCount--) |  |
| [contains(DataRelation relation)](#contains-com.groupdocs.assembly.system.data.DataRelation-) | Verifies whether a DataRelation with the specific name (case insensitive) exists in the collection. |
| [indexOf(DataRelation relation)](#indexOf-com.groupdocs.assembly.system.data.DataRelation-) | Gets the index of the specified com.groupdocs.assembly.system.data.DataRelation object. |
| [get(String name)](#get-java.lang.String-) | Gets the com.groupdocs.assembly.system.data.DataRelation object specified by name. |
| [get(int index)](#get-int-) | Gets the com.groupdocs.assembly.system.data.DataRelation object at the specified index. |
| [removeAt(int index)](#removeAt-int-) | Removes the relation at the specified index from the collection. |
| [clear()](#clear--) | Clears the collection of any relations. |
### add(DataRelation relation) {#add-com.groupdocs.assembly.system.data.DataRelation-}
```
public final void add(DataRelation relation)
```


Adds a com.groupdocs.assembly.system.data.DataRelation to the com.groupdocs.assembly.system.data.DataRelationCollection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | The DataRelation to add to the collection. |

### add(DataTable parentTable, DataTable childTable, String parentColumnName, String childColumnName) {#add-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String-java.lang.String-}
```
public final void add(DataTable parentTable, DataTable childTable, String parentColumnName, String childColumnName)
```


Adds a relation to the collection. Performs no checks on the duplication etc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The parent table of the relation. |
| childTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The child table of the relation. |
| parentColumnName | java.lang.String | The parent column's name of the relation. |
| childColumnName | java.lang.String | The child column's name of the relation. |

### add(DataTable parentTable, DataTable childTable, String[] parentColumnNames, String[] childColumnNames) {#add-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String---java.lang.String---}
```
public final void add(DataTable parentTable, DataTable childTable, String[] parentColumnNames, String[] childColumnNames)
```


Adds a relation to the collection. Performs no checks on the duplication etc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The parent table of the relation. |
| childTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The child table of the relation. |
| parentColumnNames | java.lang.String[] | The array of parent column's name of the relation. |
| childColumnNames | java.lang.String[] | The array of child column's name of the relation. |

### add(String name, DataColumn parentColumn, DataColumn childColumn, boolean createConstraints) {#add-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-boolean-}
```
public final void add(String name, DataColumn parentColumn, DataColumn childColumn, boolean createConstraints)
```


Creates a com.groupdocs.assembly.system.data.DataRelation with the specified name, parent and child columns, with optional constraints according to the value of the  createConstraints  parameter, and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the relation. |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The parent column of the relation. |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The child column of the relation. |
| createConstraints | boolean | true to create constraints; otherwise false. (The default is true). |

### add(DataColumn parentColumn, DataColumn childColumn) {#add-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-}
```
public final void add(DataColumn parentColumn, DataColumn childColumn)
```


Creates a com.groupdocs.assembly.system.data.DataRelation with a specified parent and child column, and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The parent column of the relation. |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The child column of the relation. |

### add(String name, DataColumn parentColumn, DataColumn childColumn) {#add-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-}
```
public final void add(String name, DataColumn parentColumn, DataColumn childColumn)
```


Creates a com.groupdocs.assembly.system.data.DataRelation with the specified name, and parent and child columns, and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the relation. |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The parent column of the relation. |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The child column of the relation. |

### iterator() {#iterator--}
```
public final Iterator iterator()
```




**Returns:**
java.util.Iterator
### getCount() {#getCount--}
```
public final int getCount()
```




**Returns:**
int - the total number of elements in a collection
### contains(DataRelation relation) {#contains-com.groupdocs.assembly.system.data.DataRelation-}
```
public final boolean contains(DataRelation relation)
```


Verifies whether a DataRelation with the specific name (case insensitive) exists in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | The name of the relation to find. |

**Returns:**
boolean - true, if a relation with the specified name exists; otherwise false.
### indexOf(DataRelation relation) {#indexOf-com.groupdocs.assembly.system.data.DataRelation-}
```
public final int indexOf(DataRelation relation)
```


Gets the index of the specified com.groupdocs.assembly.system.data.DataRelation object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | The relation to search for. |

**Returns:**
int - The 0-based index of the relation, or -1 if the relation is not found in the collection.
### get(String name) {#get-java.lang.String-}
```
public final DataRelation get(String name)
```


Gets the com.groupdocs.assembly.system.data.DataRelation object specified by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the relation to find. |

**Returns:**
[DataRelation](../../com.groupdocs.assembly.system.data/datarelation) - The named com.groupdocs.assembly.system.data.DataRelation, or a null value if the specified com.groupdocs.assembly.system.data.DataRelation does not exist.
### get(int index) {#get-int-}
```
public final DataRelation get(int index)
```


Gets the com.groupdocs.assembly.system.data.DataRelation object at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index to find. |

**Returns:**
[DataRelation](../../com.groupdocs.assembly.system.data/datarelation) - The com.groupdocs.assembly.system.data.DataRelation, or a null value if the specified com.groupdocs.assembly.system.data.DataRelation does not exist.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the relation at the specified index from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the relation to remove. |

### clear() {#clear--}
```
public final void clear()
```


Clears the collection of any relations.

