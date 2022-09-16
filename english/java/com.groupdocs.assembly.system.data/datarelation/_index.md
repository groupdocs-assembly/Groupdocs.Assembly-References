---
title: DataRelation
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a parent/child relationship between two  objects.
type: docs
weight: 18
url: /java/com.groupdocs.assembly.system.data/datarelation/
---
**Inheritance:**
java.lang.Object
```
public final class DataRelation
```

Represents a parent/child relationship between two [DataTable](../../com.groupdocs.assembly.system.data/datatable) objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataRelation(String relationName, DataTable parentTable, DataTable childTable, String parentColumnNames, String childColumnNames)](#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String---java.lang.String---) | Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, parent and child tables, matched arrays of parent and child columns. |
| [DataRelation(String relationName, DataColumn parentColumns, DataColumn childColumns, boolean createConstraints)](#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---com.groupdocs.assembly.system.data.DataColumn---boolean-) | Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, matched arrays of parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects, and value that indicates whether to create constraints. |
| [DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn, boolean createConstraints)](#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-boolean-) | Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects, and a value that indicates whether to create constraints. |
| [DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn)](#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-) | Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) name, and parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects. |
## Methods

| Method | Description |
| --- | --- |
| [getRelationName()](#getRelationName--) | Gets the name used to retrieve a [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) from the [DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection). |
| [getParentTableName()](#getParentTableName--) |  |
| [getChildTableName()](#getChildTableName--) |  |
| [getParentTable()](#getParentTable--) | Gets the parent [DataTable](../../com.groupdocs.assembly.system.data/datatable) of this [DataRelation](../../com.groupdocs.assembly.system.data/datarelation). |
| [getChildTable()](#getChildTable--) | Gets the child table of this relation. |
| [getParentColumnNames()](#getParentColumnNames--) |  |
| [getChildColumnNames()](#getChildColumnNames--) |  |
| [getParentColumns()](#getParentColumns--) | Gets an array of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects that are the parent columns of this [DataRelation](../../com.groupdocs.assembly.system.data/datarelation). |
| [getChildColumns()](#getChildColumns--) | Gets the child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects of this relation. |
| [setNested(boolean value)](#setNested-boolean-) | Sets a value that indicates whether [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) objects are nested. |
| [getParentKeyConstraint()](#getParentKeyConstraint--) | Gets the [UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) that guarantees that values in the parent column of a [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) are unique. |
| [setParentKeyConstraint(UniqueConstraint parentKeyConstraint)](#setParentKeyConstraint-com.groupdocs.assembly.system.data.UniqueConstraint-) |  |
| [getChildKeyConstraint()](#getChildKeyConstraint--) | Gets the [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) for the relation. |
| [setChildKeyConstraint(ForeignKeyConstraint childKeyConstraint)](#setChildKeyConstraint-com.groupdocs.assembly.system.data.ForeignKeyConstraint-) |  |
| [getChildKey()](#getChildKey--) |  |
| [getParentKey()](#getParentKey--) |  |
| [getDataSet()](#getDataSet--) | Gets the [DataSet](../../com.groupdocs.assembly.system.data/dataset) to which the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) belongs. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### DataRelation(String relationName, DataTable parentTable, DataTable childTable, String parentColumnNames, String childColumnNames) {#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String---java.lang.String---}
```
public DataRelation(String relationName, DataTable parentTable, DataTable childTable, String parentColumnNames, String childColumnNames)
```


Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, parent and child tables, matched arrays of parent and child columns.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relationName | java.lang.String | The name of the DataRelation. If null or an empty string (""), a default name will be given when the created object is added to the DataRelationCollection. |
| parentTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The parent table in the relationship. |
| childTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The child table in the relationship. |
| parentColumnNames | java.lang.String | The parent DataColumn's name in the relationship. |
| childColumnNames | java.lang.String | The child DataColumn;s in the relationship. |

### DataRelation(String relationName, DataColumn parentColumns, DataColumn childColumns, boolean createConstraints) {#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---com.groupdocs.assembly.system.data.DataColumn---boolean-}
```
public DataRelation(String relationName, DataColumn parentColumns, DataColumn childColumns, boolean createConstraints)
```


Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, matched arrays of parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects, and value that indicates whether to create constraints.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relationName | java.lang.String | The name of the relation. If null or an empty string (""), a default name will be given when the created object is added to the [DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection). |
| parentColumns | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | An array of parent [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects. |
| childColumns | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | An array of child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects. |
| createConstraints | boolean | A value that indicates whether to create constraints. true, if constraints are created. Otherwise, false. |

### DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn, boolean createConstraints) {#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-boolean-}
```
public DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn, boolean createConstraints)
```


Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects, and a value that indicates whether to create constraints.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relationName | java.lang.String | The name of the relation. If null or an empty string (""), a default name will be given when the created object is added to the [DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection). |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The parent [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) in the relation. |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) in the relation. |
| createConstraints | boolean | A value that indicates whether constraints are created. true, if constraints are created. Otherwise, false. |

### DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn) {#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-}
```
public DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn)
```


Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) name, and parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relationName | java.lang.String | The name of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation). If null or an empty string (""), a default name will be given when the created object is added to the [DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection). |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The parent [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) in the relationship. |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) in the relationship. |

### getRelationName() {#getRelationName--}
```
public final String getRelationName()
```


Gets the name used to retrieve a [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) from the [DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection).

**Returns:**
java.lang.String - The name of the a [DataRelation](../../com.groupdocs.assembly.system.data/datarelation).
### getParentTableName() {#getParentTableName--}
```
public final String getParentTableName()
```




**Returns:**
java.lang.String - the parent DataTable's name of this DataRelation.
### getChildTableName() {#getChildTableName--}
```
public final String getChildTableName()
```




**Returns:**
java.lang.String - the child DataTable's name of this DataRelation.
### getParentTable() {#getParentTable--}
```
public final DataTable getParentTable()
```


Gets the parent [DataTable](../../com.groupdocs.assembly.system.data/datatable) of this [DataRelation](../../com.groupdocs.assembly.system.data/datarelation).

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - A [DataTable](../../com.groupdocs.assembly.system.data/datatable) that is the parent table of this relation.
### getChildTable() {#getChildTable--}
```
public final DataTable getChildTable()
```


Gets the child table of this relation.

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - A [DataTable](../../com.groupdocs.assembly.system.data/datatable) that is the child table of the relation.
### getParentColumnNames() {#getParentColumnNames--}
```
public final String[] getParentColumnNames()
```




**Returns:**
java.lang.String[] - the parent DataColumn names of this relation.
### getChildColumnNames() {#getChildColumnNames--}
```
public final String[] getChildColumnNames()
```




**Returns:**
java.lang.String[] - the child DataColumn names of this relation.
### getParentColumns() {#getParentColumns--}
```
public final DataColumn[] getParentColumns()
```


Gets an array of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects that are the parent columns of this [DataRelation](../../com.groupdocs.assembly.system.data/datarelation).

**Returns:**
com.groupdocs.assembly.system.data.DataColumn[] - An array of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects that are the parent columns of this [DataRelation](../../com.groupdocs.assembly.system.data/datarelation).
### getChildColumns() {#getChildColumns--}
```
public final DataColumn[] getChildColumns()
```


Gets the child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects of this relation.

**Returns:**
com.groupdocs.assembly.system.data.DataColumn[] - An array of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.
### setNested(boolean value) {#setNested-boolean-}
```
public final void setNested(boolean value)
```


Sets a value that indicates whether [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) objects are nested.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | true, if [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) objects are nested; otherwise, false. |

### getParentKeyConstraint() {#getParentKeyConstraint--}
```
public final UniqueConstraint getParentKeyConstraint()
```


Gets the [UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) that guarantees that values in the parent column of a [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) are unique.

**Returns:**
[UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) - A [UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) that makes sure that values in a parent column are unique.
### setParentKeyConstraint(UniqueConstraint parentKeyConstraint) {#setParentKeyConstraint-com.groupdocs.assembly.system.data.UniqueConstraint-}
```
public final void setParentKeyConstraint(UniqueConstraint parentKeyConstraint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentKeyConstraint | [UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) |  |

### getChildKeyConstraint() {#getChildKeyConstraint--}
```
public final ForeignKeyConstraint getChildKeyConstraint()
```


Gets the [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) for the relation.

**Returns:**
[ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) - A [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint).
### setChildKeyConstraint(ForeignKeyConstraint childKeyConstraint) {#setChildKeyConstraint-com.groupdocs.assembly.system.data.ForeignKeyConstraint-}
```
public final void setChildKeyConstraint(ForeignKeyConstraint childKeyConstraint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| childKeyConstraint | [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) |  |

### getChildKey() {#getChildKey--}
```
public final DataKey getChildKey()
```




**Returns:**
[DataKey](../../com.groupdocs.assembly.system.data/datakey)
### getParentKey() {#getParentKey--}
```
public final DataKey getParentKey()
```




**Returns:**
[DataKey](../../com.groupdocs.assembly.system.data/datakey)
### getDataSet() {#getDataSet--}
```
public final DataSet getDataSet()
```


Gets the [DataSet](../../com.groupdocs.assembly.system.data/dataset) to which the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) belongs.

**Returns:**
[DataSet](../../com.groupdocs.assembly.system.data/dataset) - A [DataSet](../../com.groupdocs.assembly.system.data/dataset) to which the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) belongs.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public final boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
