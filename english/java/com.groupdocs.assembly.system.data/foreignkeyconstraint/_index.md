---
title: ForeignKeyConstraint
second_title: GroupDocs.Assembly for Java API Reference
description: Represents an action restriction enforced on a set of columns in a primary key/foreign key relationship when a value or row is either deleted or updated.
type: docs
weight: 29
url: /java/com.groupdocs.assembly.system.data/foreignkeyconstraint/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.assembly.system.data.Constraint](../../com.groupdocs.assembly.system.data/constraint)
```
public class ForeignKeyConstraint extends Constraint
```

Represents an action restriction enforced on a set of columns in a primary key/foreign key relationship when a value or row is either deleted or updated.

## Constructors

| Constructor | Description |
| --- | --- |
| [ForeignKeyConstraint(String constraintName, DataColumn[] parentColumns, DataColumn[] childColumns)](#ForeignKeyConstraint-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---com.groupdocs.assembly.system.data.DataColumn---) | Initializes a new instance of the [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) class with the specified name, and arrays of parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.
 |
| [ForeignKeyConstraint(DataColumn parentColumn, DataColumn childColumn)](#ForeignKeyConstraint-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-) | Initializes a new instance of the [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) class, and arrays of parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.
 |
| [ForeignKeyConstraint(String constraintName, DataColumn parentColumn, DataColumn childColumn)](#ForeignKeyConstraint-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-) | Initializes a new instance of the ForeignKeyConstraint class with the specified name, parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.
 |
## Methods

| Method | Description |
| --- | --- |
| [getDeleteRule()](#getDeleteRule--) |  |
| [getUpdateRule()](#getUpdateRule--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object key)](#equals-java.lang.Object-) |  |
| [getColumns()](#getColumns--) |  |
| [getRelatedColumns()](#getRelatedColumns--) | The parent columns of this constraint.
 |
| [getTable()](#getTable--) |  |
| [getRelatedTable()](#getRelatedTable--) |  |
| [getAcceptRejectRule()](#getAcceptRejectRule--) |  |
### ForeignKeyConstraint(String constraintName, DataColumn[] parentColumns, DataColumn[] childColumns) {#ForeignKeyConstraint-java.lang.String-com.groupdocs.assembly.system.data.DataColumn---com.groupdocs.assembly.system.data.DataColumn---}
```
public ForeignKeyConstraint(String constraintName, DataColumn[] parentColumns, DataColumn[] childColumns)
```


Initializes a new instance of the [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) class with the specified name, and arrays of parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constraintName | java.lang.String | the specified constraint name
 |
| parentColumns | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | an array of parent [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)
 |
| childColumns | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | an array of child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)
 |

### ForeignKeyConstraint(DataColumn parentColumn, DataColumn childColumn) {#ForeignKeyConstraint-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-}
```
public ForeignKeyConstraint(DataColumn parentColumn, DataColumn childColumn)
```


Initializes a new instance of the [ForeignKeyConstraint](../../com.groupdocs.assembly.system.data/foreignkeyconstraint) class, and arrays of parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | an array of parent [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)
 |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | an array of child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)
 |

### ForeignKeyConstraint(String constraintName, DataColumn parentColumn, DataColumn childColumn) {#ForeignKeyConstraint-java.lang.String-com.groupdocs.assembly.system.data.DataColumn-com.groupdocs.assembly.system.data.DataColumn-}
```
public ForeignKeyConstraint(String constraintName, DataColumn parentColumn, DataColumn childColumn)
```


Initializes a new instance of the ForeignKeyConstraint class with the specified name, parent and child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| constraintName | java.lang.String | the specified constraint name
 |
| parentColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | parent [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)
 |
| childColumn | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | child [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn)
 |

### getDeleteRule() {#getDeleteRule--}
```
public Rule getDeleteRule()
```




**Returns:**
[Rule](../../com.groupdocs.assembly.system.data/rule) - the action [Rule](../../com.groupdocs.assembly.system.data/rule) that occurs across this constraint when a row is deleted.

### getUpdateRule() {#getUpdateRule--}
```
public Rule getUpdateRule()
```




**Returns:**
[Rule](../../com.groupdocs.assembly.system.data/rule) - the action [Rule](../../com.groupdocs.assembly.system.data/rule) that occurs across this constraint on when a row is updated.

### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object key) {#equals-java.lang.Object-}
```
public boolean equals(Object key)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.Object |  |

**Returns:**
boolean
### getColumns() {#getColumns--}
```
public DataColumn[] getColumns()
```




**Returns:**
com.groupdocs.assembly.system.data.DataColumn[] - the child columns of this constraint.

### getRelatedColumns() {#getRelatedColumns--}
```
public DataColumn[] getRelatedColumns()
```


The parent columns of this constraint.


**Returns:**
com.groupdocs.assembly.system.data.DataColumn[] - parent columns of this constraint

### getTable() {#getTable--}
```
public DataTable getTable()
```




**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - the child table of this constraint

### getRelatedTable() {#getRelatedTable--}
```
public DataTable getRelatedTable()
```




**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - The parent columns of this constraint.

### getAcceptRejectRule() {#getAcceptRejectRule--}
```
public AcceptRejectRule getAcceptRejectRule()
```




**Returns:**
com.groupdocs.assembly.system.data.AcceptRejectRule - AcceptRejectRule but it is not implemented yet.

