---
title: DataRelationCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents the collection of relations  each of which allows navigation between related parent/child tables.
type: docs
weight: 19
url: /java/com.groupdocs.assembly.system.data/datarelationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class DataRelationCollection implements Iterable<DataRelation>
```

Represents the collection of relations, each of which allows navigation between related parent/child tables.

## Methods

| Method | Description |
| --- | --- |
| [add(DataRelation relation)](#add-com.groupdocs.assembly.system.data.DataRelation-) | Adds a relation to the collection.
 |
| [add(DataTable parentTable, DataTable childTable, String parentColumnName, String childColumnName)](#add-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String-java.lang.String-) | Adds a relation to the collection.
 |
| [add(DataTable parentTable, DataTable childTable, String[] parentColumnNames, String[] childColumnNames)](#add-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String---java.lang.String---) | Adds a relation to the collection.
 |
| [add(String name, DataColumn parentColumn, DataColumn childColumn, boolean createConstraints)](#add-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-boolean-) |  |
| [add(DataColumn parentColumn, DataColumn childColumn)](#add-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-) |  |
| [add(String name, DataColumn parentColumn, DataColumn childColumn)](#add-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-) |  |
| [iterator()](#iterator--) |  |
| [getCount()](#getCount--) |  |
| [contains(DataRelation relation)](#contains-com.groupdocs.assembly.system.data.DataRelation-) | Verifies whether a DataRelation with the specific name (case insensitive) exists in the collection.
 |
| [indexOf(DataRelation relation)](#indexOf-com.groupdocs.assembly.system.data.DataRelation-) | Returns the index of the specified relation within this collection.
 |
| [get(String name)](#get-java.lang.String-) | Gets the relationship by its name.
 |
| [get(int index)](#get-int-) | Gets a DataRelation instance from the collection at the specified index.
 |
| [removeAt(int index)](#removeAt-int-) | Removes the relation at the specified index from the collection.
 |
| [clear()](#clear--) | Clears the collection of any relations.
 |
### add(DataRelation relation) {#add-com.groupdocs.assembly.system.data.DataRelation-}
```
public void add(DataRelation relation)
```


Adds a relation to the collection. Performs no checks on the duplication etc.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | the DataRelation to add to the collection.
 |

### add(DataTable parentTable, DataTable childTable, String parentColumnName, String childColumnName) {#add-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String-java.lang.String-}
```
public void add(DataTable parentTable, DataTable childTable, String parentColumnName, String childColumnName)
```


Adds a relation to the collection. Performs no checks on the duplication etc.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The parent table of the relation.
 |
| childTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The child table of the relation.
 |
| parentColumnName | java.lang.String | The parent column's name of the relation.
 |
| childColumnName | java.lang.String | The child column's name of the relation.
 |

### add(DataTable parentTable, DataTable childTable, String[] parentColumnNames, String[] childColumnNames) {#add-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String---java.lang.String---}
```
public void add(DataTable parentTable, DataTable childTable, String[] parentColumnNames, String[] childColumnNames)
```


Adds a relation to the collection. Performs no checks on the duplication etc.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The parent table of the relation.
 |
| childTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The child table of the relation.
 |
| parentColumnNames | java.lang.String[] | The array of parent column's name of the relation.
 |
| childColumnNames | java.lang.String[] | The array of child column's name of the relation.
 |

### add(String name, DataColumn parentColumn, DataColumn childColumn, boolean createConstraints) {#add-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-boolean-}
```
public void add(String name, DataColumn parentColumn, DataColumn childColumn, boolean createConstraints)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) |  |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) |  |
| createConstraints | boolean |  |

### add(DataColumn parentColumn, DataColumn childColumn) {#add-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-}
```
public void add(DataColumn parentColumn, DataColumn childColumn)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) |  |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) |  |

### add(String name, DataColumn parentColumn, DataColumn childColumn) {#add-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-}
```
public void add(String name, DataColumn parentColumn, DataColumn childColumn)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) |  |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) |  |

### iterator() {#iterator--}
```
public Iterator<DataRelation> iterator()
```




**Returns:**
java.util.Iterator<com.groupdocs.assembly.system.data.DataRelation>
### getCount() {#getCount--}
```
public int getCount()
```




**Returns:**
int - the total number of elements in a collection

### contains(DataRelation relation) {#contains-com.groupdocs.assembly.system.data.DataRelation-}
```
public boolean contains(DataRelation relation)
```


Verifies whether a DataRelation with the specific name (case insensitive) exists in the collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | The name of the relation to find.
 |

**Returns:**
boolean - true, if a relation with the specified name exists; otherwise false.

### indexOf(DataRelation relation) {#indexOf-com.groupdocs.assembly.system.data.DataRelation-}
```
public int indexOf(DataRelation relation)
```


Returns the index of the specified relation within this collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | A relation to find.
 |

**Returns:**
int - The zero-based index of the specified relation, or -1 if the relation does not exist in this collection.

### get(String name) {#get-java.lang.String-}
```
public DataRelation get(String name)
```


Gets the relationship by its name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | the name of relationship
 |

**Returns:**
[DataRelation](../../com.groupdocs.assembly.system.data/datarelation) - DataRelationship or `null`

### get(int index) {#get-int-}
```
public DataRelation get(int index)
```


Gets a DataRelation instance from the collection at the specified index.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the relation to return.
 |

**Returns:**
[DataRelation](../../com.groupdocs.assembly.system.data/datarelation) - A DataRelation instance from the collection at the specified index.

### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


Removes the relation at the specified index from the collection.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the relation to remove.
 |

### clear() {#clear--}
```
public void clear()
```


Clears the collection of any relations.


