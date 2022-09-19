---
title: DataTable
second_title: GroupDocs.Assembly for Java API Reference
description: Represents one table of in-memory data.
type: docs
weight: 25
url: /java/com.groupdocs.assembly.system.data/datatable/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.assembly.system.data.DataTableEventListener](../../com.groupdocs.assembly.system.data/datatableeventlistener)
```
public class DataTable implements DataTableEventListener
```

Represents one table of in-memory data.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataTable()](#DataTable--) | Initializes a new instance of the [DataTable](../../com.groupdocs.assembly.system.data/datatable) class with no arguments. |
| [DataTable(String tableName)](#DataTable-java.lang.String-) | Initializes a new instance of the [DataTable](../../com.groupdocs.assembly.system.data/datatable) class with the specified table name. |
| [DataTable(ResultSet resultSet)](#DataTable-java.sql.ResultSet-) | Creates an object by wrapping the specified ResultSet. |
| [DataTable(ResultSet resultSet, String tableName)](#DataTable-java.sql.ResultSet-java.lang.String-) | Creates an object by wrapping the specified ResultSet. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [getTableName()](#getTableName--) | Gets the name of the [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [setTableName(String value)](#setTableName-java.lang.String-) | Sets the name of the [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [containsColumn(String columnName)](#containsColumn-java.lang.String-) | Check whether the given column exists or not |
| [getColumnsCount()](#getColumnsCount--) |  |
| [getColumnName(int index)](#getColumnName-int-) | Analog for .Net DataTable.Columns[i].ColumnName |
| [getResultSet()](#getResultSet--) | Returns the underlying Java ResultSet object. |
| [getDataSet()](#getDataSet--) | Gets the [DataSet](../../com.groupdocs.assembly.system.data/dataset) to which this table belongs. |
| [getChildRelations()](#getChildRelations--) | Gets the collection of child relations for this [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [getParentRelations()](#getParentRelations--) | Gets the collection of parent relations for this [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [getRows()](#getRows--) | Gets the collection of rows that belong to this table. |
| [getColumns()](#getColumns--) | Gets the collection of columns that belong to this table. |
| [newRow()](#newRow--) | Creates a new [DataRow](../../com.groupdocs.assembly.system.data/datarow) with the same schema as the table. |
| [getConstraints()](#getConstraints--) | Gets the collection of constraints maintained by this table. |
| [getPrimaryKey()](#getPrimaryKey--) | Gets an array of columns that function as primary keys for the data table. |
| [setPrimaryKey(DataColumn value)](#setPrimaryKey-com.groupdocs.assembly.system.data.DataColumn---) | Sets an array of columns that function as primary keys for the data table. |
| [getNamespace()](#getNamespace--) | Gets the namespace for the XML representation of the data stored in the [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [setNamespace(String value)](#setNamespace-java.lang.String-) | Sets the namespace for the XML representation of the data stored in the [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [getEnforceConstraints()](#getEnforceConstraints--) |  |
| [setEnforceConstraints(boolean enforceConstraints)](#setEnforceConstraints-boolean-) |  |
| [refresh()](#refresh--) | Reloads all the data from ResultSet if it is present. |
| [acceptChanges()](#acceptChanges--) | Commits all the changes made to this table since the last time acceptChanges() was called. |
| [addEventListener(DataTableEventListener listener)](#addEventListener-com.groupdocs.assembly.system.data.DataTableEventListener-) |  |
| [clearEventListneers()](#clearEventListneers--) |  |
| [onDataRowChanged(DataRow row)](#onDataRowChanged-com.groupdocs.assembly.system.data.DataRow-) |  |
| [onDataRowInserted(DataRow row)](#onDataRowInserted-com.groupdocs.assembly.system.data.DataRow-) |  |
| [onDataRowDeleted(DataRow row)](#onDataRowDeleted-com.groupdocs.assembly.system.data.DataRow-) |  |
| [onDataColumnInserted(DataColumn column)](#onDataColumnInserted-com.groupdocs.assembly.system.data.DataColumn-) |  |
| [onDataColumnDeleted(DataColumn column)](#onDataColumnDeleted-com.groupdocs.assembly.system.data.DataColumn-) |  |
### DataTable() {#DataTable--}
```
public DataTable()
```


Initializes a new instance of the [DataTable](../../com.groupdocs.assembly.system.data/datatable) class with no arguments.

### DataTable(String tableName) {#DataTable-java.lang.String-}
```
public DataTable(String tableName)
```


Initializes a new instance of the [DataTable](../../com.groupdocs.assembly.system.data/datatable) class with the specified table name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tableName | java.lang.String | The name to give the table. If  tableName  is null or an empty string, a default name is given when added to the [DataTableCollection](../../com.groupdocs.assembly.system.data/datatablecollection). |

### DataTable(ResultSet resultSet) {#DataTable-java.sql.ResultSet-}
```
public DataTable(ResultSet resultSet)
```


Creates an object by wrapping the specified ResultSet. Attempts to retrieve the table name from the metadata of the first column of the ResultSet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resultSet | java.sql.ResultSet | data set |

### DataTable(ResultSet resultSet, String tableName) {#DataTable-java.sql.ResultSet-java.lang.String-}
```
public DataTable(ResultSet resultSet, String tableName)
```


Creates an object by wrapping the specified ResultSet.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resultSet | java.sql.ResultSet | data set |
| tableName | java.lang.String | name of the table |

### close() {#close--}
```
public void close()
```




### getTableName() {#getTableName--}
```
public String getTableName()
```


Gets the name of the [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Returns:**
java.lang.String - The name of the [DataTable](../../com.groupdocs.assembly.system.data/datatable).
### setTableName(String value) {#setTableName-java.lang.String-}
```
public void setTableName(String value)
```


Sets the name of the [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the [DataTable](../../com.groupdocs.assembly.system.data/datatable). |

### containsColumn(String columnName) {#containsColumn-java.lang.String-}
```
public boolean containsColumn(String columnName)
```


Check whether the given column exists or not

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | name of the column |

**Returns:**
boolean - `true` is column can be found by the given `columnName`
### getColumnsCount() {#getColumnsCount--}
```
public int getColumnsCount()
```




**Returns:**
int - columns count
### getColumnName(int index) {#getColumnName-int-}
```
public String getColumnName(int index)
```


Analog for .Net DataTable.Columns[i].ColumnName

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | \- column's index |

**Returns:**
java.lang.String - column's name by its index.
### getResultSet() {#getResultSet--}
```
public ResultSet getResultSet()
```


Returns the underlying Java ResultSet object. Ideally we would like to work with DataTable in .Net manner. But some users and even some ours sample code are using this property.

**Returns:**
java.sql.ResultSet - the underlying java.sql.ResultSet
### getDataSet() {#getDataSet--}
```
public DataSet getDataSet()
```


Gets the [DataSet](../../com.groupdocs.assembly.system.data/dataset) to which this table belongs.

**Returns:**
[DataSet](../../com.groupdocs.assembly.system.data/dataset) - The [DataSet](../../com.groupdocs.assembly.system.data/dataset) to which this table belongs.
### getChildRelations() {#getChildRelations--}
```
public DataRelationCollection getChildRelations()
```


Gets the collection of child relations for this [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Returns:**
[DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection) - A [DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection) that contains the child relations for the table. An empty collection is returned if no [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) objects exist.
### getParentRelations() {#getParentRelations--}
```
public DataRelationCollection getParentRelations()
```


Gets the collection of parent relations for this [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Returns:**
[DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection) - A [DataRelationCollection](../../com.groupdocs.assembly.system.data/datarelationcollection) that contains the parent relations for the table. An empty collection is returned if no [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) objects exist.
### getRows() {#getRows--}
```
public DataRowCollection getRows()
```


Gets the collection of rows that belong to this table.

**Returns:**
[DataRowCollection](../../com.groupdocs.assembly.system.data/datarowcollection) - A [DataRowCollection](../../com.groupdocs.assembly.system.data/datarowcollection) that contains [DataRow](../../com.groupdocs.assembly.system.data/datarow) objects; otherwise a null value if no [DataRow](../../com.groupdocs.assembly.system.data/datarow) objects exist.
### getColumns() {#getColumns--}
```
public DataColumnCollection getColumns()
```


Gets the collection of columns that belong to this table.

**Returns:**
[DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection) - A [DataColumnCollection](../../com.groupdocs.assembly.system.data/datacolumncollection) that contains the collection of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects for the table. An empty collection is returned if no [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects exist.
### newRow() {#newRow--}
```
public DataRow newRow()
```


Creates a new [DataRow](../../com.groupdocs.assembly.system.data/datarow) with the same schema as the table.

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - A [DataRow](../../com.groupdocs.assembly.system.data/datarow) with the same schema as the [DataTable](../../com.groupdocs.assembly.system.data/datatable).
### getConstraints() {#getConstraints--}
```
public ConstraintCollection getConstraints()
```


Gets the collection of constraints maintained by this table.

**Returns:**
[ConstraintCollection](../../com.groupdocs.assembly.system.data/constraintcollection) - A [ConstraintCollection](../../com.groupdocs.assembly.system.data/constraintcollection) that contains the collection of [Constraint](../../com.groupdocs.assembly.system.data/constraint) objects for the table. An empty collection is returned if no [Constraint](../../com.groupdocs.assembly.system.data/constraint) objects exist.
### getPrimaryKey() {#getPrimaryKey--}
```
public DataColumn[] getPrimaryKey()
```


Gets an array of columns that function as primary keys for the data table.

**Returns:**
com.groupdocs.assembly.system.data.DataColumn[] - An array of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects.
### setPrimaryKey(DataColumn value) {#setPrimaryKey-com.groupdocs.assembly.system.data.DataColumn---}
```
public void setPrimaryKey(DataColumn value)
```


Sets an array of columns that function as primary keys for the data table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataColumn\[\]](../../com.groupdocs.assembly.system.data/datacolumn) | An array of [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) objects. |

### getNamespace() {#getNamespace--}
```
public String getNamespace()
```


Gets the namespace for the XML representation of the data stored in the [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Returns:**
java.lang.String - The namespace of the [DataTable](../../com.groupdocs.assembly.system.data/datatable).
### setNamespace(String value) {#setNamespace-java.lang.String-}
```
public void setNamespace(String value)
```


Sets the namespace for the XML representation of the data stored in the [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The namespace of the [DataTable](../../com.groupdocs.assembly.system.data/datatable). |

### getEnforceConstraints() {#getEnforceConstraints--}
```
public boolean getEnforceConstraints()
```




**Returns:**
boolean - flag which indicates whether check constraint violation or not
### setEnforceConstraints(boolean enforceConstraints) {#setEnforceConstraints-boolean-}
```
public void setEnforceConstraints(boolean enforceConstraints)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| enforceConstraints | boolean | is the flag which indicates whether check constraint violation or not |

### refresh() {#refresh--}
```
public void refresh()
```


Reloads all the data from ResultSet if it is present.

### acceptChanges() {#acceptChanges--}
```
public void acceptChanges()
```


Commits all the changes made to this table since the last time acceptChanges() was called.

### addEventListener(DataTableEventListener listener) {#addEventListener-com.groupdocs.assembly.system.data.DataTableEventListener-}
```
public synchronized void addEventListener(DataTableEventListener listener)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| listener | [DataTableEventListener](../../com.groupdocs.assembly.system.data/datatableeventlistener) |  |

### clearEventListneers() {#clearEventListneers--}
```
public synchronized void clearEventListneers()
```




### onDataRowChanged(DataRow row) {#onDataRowChanged-com.groupdocs.assembly.system.data.DataRow-}
```
public void onDataRowChanged(DataRow row)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | [DataRow](../../com.groupdocs.assembly.system.data/datarow) |  |

### onDataRowInserted(DataRow row) {#onDataRowInserted-com.groupdocs.assembly.system.data.DataRow-}
```
public void onDataRowInserted(DataRow row)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | [DataRow](../../com.groupdocs.assembly.system.data/datarow) |  |

### onDataRowDeleted(DataRow row) {#onDataRowDeleted-com.groupdocs.assembly.system.data.DataRow-}
```
public void onDataRowDeleted(DataRow row)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | [DataRow](../../com.groupdocs.assembly.system.data/datarow) |  |

### onDataColumnInserted(DataColumn column) {#onDataColumnInserted-com.groupdocs.assembly.system.data.DataColumn-}
```
public void onDataColumnInserted(DataColumn column)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) |  |

### onDataColumnDeleted(DataColumn column) {#onDataColumnDeleted-com.groupdocs.assembly.system.data.DataColumn-}
```
public void onDataColumnDeleted(DataColumn column)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) |  |

