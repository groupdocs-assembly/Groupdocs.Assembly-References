---
title: DataRelation
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a parent/child relationship between two tables.
type: docs
weight: 18
url: /java/com.groupdocs.assembly.system.data/datarelation/
---
**Inheritance:**
java.lang.Object
```
public class DataRelation
```

Represents a parent/child relationship between two tables.

## Constructors

| Constructor | Description |
| --- | --- |
| [DataRelation(String relationName, DataTable parentTable, DataTable childTable, String[] parentColumnNames, String[] childColumnNames)](#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String---java.lang.String---) | Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, parent and child tables, matched arrays of parent and child columns.
 |
| [DataRelation(String relationName, DataColumn[] parentColumns, DataColumn[] childColumns, boolean createConstraints)](#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---com.groupdocs.assembly.system.data.DataColumn---boolean-) | Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, matched arrays of parent and child columns, and value to create constraints.
 |
| [DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn, boolean createConstraint)](#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-boolean-) | Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, parent, and child columns, and value to create constraints.
 |
| [DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn)](#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-) | Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) name, and parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.
 |
## Methods

| Method | Description |
| --- | --- |
| [getRelationName()](#getRelationName--) |  |
| [getParentTableName()](#getParentTableName--) |  |
| [getChildTableName()](#getChildTableName--) |  |
| [getParentTable()](#getParentTable--) |  |
| [getChildTable()](#getChildTable--) |  |
| [getParentColumnNames()](#getParentColumnNames--) |  |
| [getChildColumnNames()](#getChildColumnNames--) |  |
| [getParentColumns()](#getParentColumns--) |  |
| [getChildColumns()](#getChildColumns--) |  |
| [setNested(boolean nested)](#setNested-boolean-) |  |
| [getParentKeyConstraint()](#getParentKeyConstraint--) |  |
| [setParentKeyConstraint(UniqueConstraint parentKeyConstraint)](#setParentKeyConstraint-com.groupdocs.assembly.system.data.UniqueConstraint-) |  |
| [getChildKeyConstraint()](#getChildKeyConstraint--) |  |
| [setChildKeyConstraint(ForeignKeyConstraint childKeyConstraint)](#setChildKeyConstraint-com.groupdocs.assembly.system.data.ForeignKeyConstraint-) |  |
| [getChildKey()](#getChildKey--) |  |
| [getParentKey()](#getParentKey--) |  |
| [getDataSet()](#getDataSet--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
### DataRelation(String relationName, DataTable parentTable, DataTable childTable, String[] parentColumnNames, String[] childColumnNames) {#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataTable-com.groupdocs.assembly.system.data.DataTable-java.lang.String---java.lang.String---}
```
public DataRelation(String relationName, DataTable parentTable, DataTable childTable, String[] parentColumnNames, String[] childColumnNames)
```


Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, parent and child tables, matched arrays of parent and child columns.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relationName | java.lang.String | The name of the DataRelation. If null or an empty string (""), a default name will be given when the created object is added to the DataRelationCollection.
 |
| parentTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The parent table in the relationship.
 |
| childTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The child table in the relationship.
 |
| parentColumnNames | java.lang.String[] | The parent DataColumn's name in the relationship.
 |
| childColumnNames | java.lang.String[] | The child DataColumn;s in the relationship.
 |

### DataRelation(String relationName, DataColumn[] parentColumns, DataColumn[] childColumns, boolean createConstraints) {#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---com.groupdocs.assembly.system.data.DataColumn---boolean-}
```
public DataRelation(String relationName, DataColumn[] parentColumns, DataColumn[] childColumns, boolean createConstraints)
```


Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, matched arrays of parent and child columns, and value to create constraints.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relationName | java.lang.String | he name of the DataRelation. If null or an empty string (""), a default name will be given when the created object is added to the DataRelationCollection.
 |
| parentColumns | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | An array of parent DataColumn objects.
 |
| childColumns | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | An array of child DataColumn objects.
 |
| createConstraints | boolean | value that indicates whether to create constraints. true, if constraints are created. Otherwise, false.
 |

### DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn, boolean createConstraint) {#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-boolean-}
```
public DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn, boolean createConstraint)
```


Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified name, parent, and child columns, and value to create constraints.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relationName | java.lang.String | The name of the DataRelation. If null or an empty string (""), a default name will be given when the created object is added to the DataRelationCollection.
 |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The parent DataColumn in the relationship.
 |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The child DataColumn in the relationship.
 |
| createConstraint | boolean | value that indicates whether to create constraints. true, if constraints are created. Otherwise, false.
 |

### DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn) {#DataRelation-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-}
```
public DataRelation(String relationName, DataColumn parentColumn, DataColumn childColumn)
```


Initializes a new instance of the [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) class using the specified [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) name, and parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relationName | java.lang.String | The name of the DataRelation. If null or an empty string (""), a default name will be given when the created object is added to the DataRelationCollection.
 |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The parent DataColumn in the relationship.
 |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The child DataColumn in the relationship.
 |

### getRelationName() {#getRelationName--}
```
public String getRelationName()
```




**Returns:**
java.lang.String - the name used to look up this relation in the parent data set's [DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection).

### getParentTableName() {#getParentTableName--}
```
public String getParentTableName()
```




**Returns:**
java.lang.String - the parent DataTable's name of this DataRelation.

### getChildTableName() {#getChildTableName--}
```
public String getChildTableName()
```




**Returns:**
java.lang.String - the child DataTable's name of this DataRelation.

### getParentTable() {#getParentTable--}
```
public DataTable getParentTable()
```




**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - the parent DataTable of this DataRelation.

### getChildTable() {#getChildTable--}
```
public DataTable getChildTable()
```




**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - the child DataTable of this DataRelation.

### getParentColumnNames() {#getParentColumnNames--}
```
public String[] getParentColumnNames()
```




**Returns:**
java.lang.String[] - the parent DataColumn names of this relation.

### getChildColumnNames() {#getChildColumnNames--}
```
public String[] getChildColumnNames()
```




**Returns:**
java.lang.String[] - the child DataColumn names of this relation.

### getParentColumns() {#getParentColumns--}
```
public DataColumn[] getParentColumns()
```




**Returns:**
com.groupdocs.assembly.system.data.DataColumn[] - an array of DataColumn objects that are the parent columns of this DataRelation.

### getChildColumns() {#getChildColumns--}
```
public DataColumn[] getChildColumns()
```




**Returns:**
com.groupdocs.assembly.system.data.DataColumn[] - the child DataColumn objects of this relation.

### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| nested | boolean | value that indicates whether DataRelation objects are nested.
 |

### getParentKeyConstraint() {#getParentKeyConstraint--}
```
public UniqueConstraint getParentKeyConstraint()
```




**Returns:**
[UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) - the UniqueConstraint that guarantees that values in the parent column of a DataRelation are unique.

### setParentKeyConstraint(UniqueConstraint parentKeyConstraint) {#setParentKeyConstraint-com.groupdocs.assembly.system.data.UniqueConstraint-}
```
public void setParentKeyConstraint(UniqueConstraint parentKeyConstraint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentKeyConstraint | [UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) |  |

### getChildKeyConstraint() {#getChildKeyConstraint--}
```
public ForeignKeyConstraint getChildKeyConstraint()
```




**Returns:**
[ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) - the ForeignKeyConstraint for the relation.

### setChildKeyConstraint(ForeignKeyConstraint childKeyConstraint) {#setChildKeyConstraint-com.groupdocs.assembly.system.data.ForeignKeyConstraint-}
```
public void setChildKeyConstraint(ForeignKeyConstraint childKeyConstraint)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| childKeyConstraint | [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) |  |

### getChildKey() {#getChildKey--}
```
public DataKey getChildKey()
```




**Returns:**
[DataKey](../../com.groupdocs.assembly.system.data/datakey)
### getParentKey() {#getParentKey--}
```
public DataKey getParentKey()
```




**Returns:**
[DataKey](../../com.groupdocs.assembly.system.data/datakey)
### getDataSet() {#getDataSet--}
```
public DataSet getDataSet()
```




**Returns:**
[DataSet](../../com.groupdocs.assembly.system.data/dataset)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
