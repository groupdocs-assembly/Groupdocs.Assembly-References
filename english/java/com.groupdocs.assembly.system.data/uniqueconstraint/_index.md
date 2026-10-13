---
title: UniqueConstraint
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a restriction on a set of mDataColumns in which all values must be unique.
type: docs
weight: 32
url: /java/com.groupdocs.assembly.system.data/uniqueconstraint/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.assembly.system.data.Constraint](../../com.groupdocs.assembly.system.data/constraint)
```
public class UniqueConstraint extends Constraint
```

Represents a restriction on a set of mDataColumns in which all values must be unique.

## Constructors

| Constructor | Description |
| --- | --- |
| [UniqueConstraint(String constraintName, DataColumn[] columns, boolean isPK)](#UniqueConstraint-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---boolean-) | Initializes a new instance of the [UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) with the specified name, [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)s and the flag which indicates whether this constraint is the primary key.
 |
| [UniqueConstraint(DataColumn[] columns, boolean isPK)](#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn---boolean-) | Initializes a new instance of the UniqueConstraint class with an array of DataColumn objects to constrain, and a value specifying whether the constraint is a primary key.
 |
| [UniqueConstraint(DataColumn[] columns)](#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn---) | Initializes a new instance of the UniqueConstraint class with the given array of DataColumn objects.
 |
| [UniqueConstraint(DataColumn column)](#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn-) | Initializes a new instance of the UniqueConstraint class with the given array of DataColumn objects.
 |
## Methods

| Method | Description |
| --- | --- |
| [hashCode()](#hashCode--) |  |
| [equals(Object key2)](#equals-java.lang.Object-) |  |
| [getColumns()](#getColumns--) |  |
| [isPrimaryKey()](#isPrimaryKey--) | Gets a value indicating whether or not the constraint is on a primary key.
 |
| [getTable()](#getTable--) | Gets the table to which this constraint belongs.
 |
### UniqueConstraint(String constraintName, DataColumn[] columns, boolean isPK) {#UniqueConstraint-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---boolean-}
```
public UniqueConstraint(String constraintName, DataColumn[] columns, boolean isPK)
```


Initializes a new instance of the [UniqueConstraint](../../com.groupdocs.assembly.system.data/uniqueconstraint) with the specified name, [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)s and the flag which indicates whether this constraint is the primary key.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constraintName | java.lang.String | name
 |
| columns | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | an array of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) that this constraint affects.
 |
| isPK | boolean | flag which indicates whether this constraint is the primary key
 |

### UniqueConstraint(DataColumn[] columns, boolean isPK) {#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn---boolean-}
```
public UniqueConstraint(DataColumn[] columns, boolean isPK)
```


Initializes a new instance of the UniqueConstraint class with an array of DataColumn objects to constrain, and a value specifying whether the constraint is a primary key.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columns | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | an array of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) that this constraint affects.
 |
| isPK | boolean | flag which indicates whether this constraint is the primary key
 |

### UniqueConstraint(DataColumn[] columns) {#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn---}
```
public UniqueConstraint(DataColumn[] columns)
```


Initializes a new instance of the UniqueConstraint class with the given array of DataColumn objects.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columns | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | an array of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) that this constraint affects.
 |

### UniqueConstraint(DataColumn column) {#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn-}
```
public UniqueConstraint(DataColumn column)
```


Initializes a new instance of the UniqueConstraint class with the given array of DataColumn objects.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | one [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) that this constraint affects.
 |

### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object key2) {#equals-java.lang.Object-}
```
public boolean equals(Object key2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key2 | java.lang.Object |  |

**Returns:**
boolean
### getColumns() {#getColumns--}
```
public DataColumn[] getColumns()
```




**Returns:**
com.groupdocs.assembly.system.data.DataColumn[] - the array of mDataColumns that this constraint affects.

### isPrimaryKey() {#isPrimaryKey--}
```
public boolean isPrimaryKey()
```


Gets a value indicating whether or not the constraint is on a primary key.


**Returns:**
boolean - value indicating whether or not the constraint is on a primary key.

### getTable() {#getTable--}
```
public DataTable getTable()
```


Gets the table to which this constraint belongs.


**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - table to which this constraint belongs

