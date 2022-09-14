---
title: UniqueConstraint
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a restriction on a set of columns in which all values must be unique.
type: docs
weight: 32
url: /java/com.groupdocs.assembly.system.data/uniqueconstraint/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.assembly.system.data.Constraint](../../com.groupdocs.assembly.system.data/constraint)
```
public class UniqueConstraint extends Constraint
```

Represents a restriction on a set of columns in which all values must be unique.
## Constructors

| Constructor | Description |
| --- | --- |
| [UniqueConstraint(String name, DataColumn[] columns, boolean isPrimaryKey)](#UniqueConstraint-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---boolean-) | Initializes a new instance of the com.groupdocs.assembly.system.data.UniqueConstraint class with the specified name, an array of com.groupdocs.assembly.system.data.DataColumn objects to constrain, and a value specifying whether the constraint is a primary key. |
| [UniqueConstraint(DataColumn[] columns, boolean isPrimaryKey)](#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn---boolean-) | Initializes a new instance of the com.groupdocs.assembly.system.data.UniqueConstraint class with an array of com.groupdocs.assembly.system.data.DataColumn objects to constrain, and a value specifying whether the constraint is a primary key. |
| [UniqueConstraint(DataColumn[] columns)](#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn---) | Initializes a new instance of the com.groupdocs.assembly.system.data.UniqueConstraint class with the given array of com.groupdocs.assembly.system.data.DataColumn objects. |
| [UniqueConstraint(DataColumn column)](#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn-) | Initializes a new instance of the com.groupdocs.assembly.system.data.UniqueConstraint class with the specified com.groupdocs.assembly.system.data.DataColumn. |
## Methods

| Method | Description |
| --- | --- |
| [hashCode()](#hashCode--) |  |
| [equals(Object key2)](#equals-java.lang.Object-) | Compares this constraint to a second to determine if both are identical. |
| [getColumns()](#getColumns--) | Gets the array of columns that this constraint affects. |
| [isPrimaryKey()](#isPrimaryKey--) | Gets a value indicating whether or not the constraint is on a primary key. |
| [getTable()](#getTable--) | Gets the table to which this constraint belongs. |
### UniqueConstraint(String name, DataColumn[] columns, boolean isPrimaryKey) {#UniqueConstraint-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---boolean-}
```
public UniqueConstraint(String name, DataColumn[] columns, boolean isPrimaryKey)
```


Initializes a new instance of the com.groupdocs.assembly.system.data.UniqueConstraint class with the specified name, an array of com.groupdocs.assembly.system.data.DataColumn objects to constrain, and a value specifying whether the constraint is a primary key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the constraint. |
| columns | com.groupdocs.assembly.system.data.DataColumn[] | An array of com.groupdocs.assembly.system.data.DataColumn objects to constrain. |
| isPrimaryKey | boolean | true to indicate that the constraint is a primary key; otherwise, false. |

### UniqueConstraint(DataColumn[] columns, boolean isPrimaryKey) {#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn---boolean-}
```
public UniqueConstraint(DataColumn[] columns, boolean isPrimaryKey)
```


Initializes a new instance of the com.groupdocs.assembly.system.data.UniqueConstraint class with an array of com.groupdocs.assembly.system.data.DataColumn objects to constrain, and a value specifying whether the constraint is a primary key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columns | com.groupdocs.assembly.system.data.DataColumn[] | An array of com.groupdocs.assembly.system.data.DataColumn objects to constrain. |
| isPrimaryKey | boolean | true to indicate that the constraint is a primary key; otherwise, false. |

### UniqueConstraint(DataColumn[] columns) {#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn---}
```
public UniqueConstraint(DataColumn[] columns)
```


Initializes a new instance of the com.groupdocs.assembly.system.data.UniqueConstraint class with the given array of com.groupdocs.assembly.system.data.DataColumn objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columns | com.groupdocs.assembly.system.data.DataColumn[] | The array of com.groupdocs.assembly.system.data.DataColumn objects to constrain. |

### UniqueConstraint(DataColumn column) {#UniqueConstraint-com.groupdocs.assembly.system.data.DataColumn-}
```
public UniqueConstraint(DataColumn column)
```


Initializes a new instance of the com.groupdocs.assembly.system.data.UniqueConstraint class with the specified com.groupdocs.assembly.system.data.DataColumn.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The com.groupdocs.assembly.system.data.DataColumn to constrain. |

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


Compares this constraint to a second to determine if both are identical.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key2 | java.lang.Object | The object to which this com.groupdocs.assembly.system.data.UniqueConstraint is compared. |

**Returns:**
boolean - true, if the contraints are equal; otherwise, false.
### getColumns() {#getColumns--}
```
public DataColumn[] getColumns()
```


Gets the array of columns that this constraint affects.

**Returns:**
com.groupdocs.assembly.system.data.DataColumn[] - An array of com.groupdocs.assembly.system.data.DataColumn objects.
### isPrimaryKey() {#isPrimaryKey--}
```
public boolean isPrimaryKey()
```


Gets a value indicating whether or not the constraint is on a primary key.

**Returns:**
boolean - true, if the constraint is on a primary key; otherwise, false.
### getTable() {#getTable--}
```
public DataTable getTable()
```


Gets the table to which this constraint belongs.

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - The com.groupdocs.assembly.system.data.DataTable to which the constraint belongs.
