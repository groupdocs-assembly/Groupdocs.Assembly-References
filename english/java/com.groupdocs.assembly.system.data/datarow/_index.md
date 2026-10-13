---
title: DataRow
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a row of data in a .
type: docs
weight: 20
url: /java/com.groupdocs.assembly.system.data/datarow/
---
**Inheritance:**
java.lang.Object
```
public class DataRow
```

Represents a row of data in a [DataTable](../../com.groupdocs.assembly.system.data/datatable).

## Methods

| Method | Description |
| --- | --- |
| [readFrom(ResultSet resultSet)](#readFrom-java.sql.ResultSet-) | Reads values from the ResultSet
 |
| [get(int index)](#get-int-) | Gets the data stored in the column specified by index.
 |
| [get(String columnName)](#get-java.lang.String-) | Gets the data stored in the column specified by name.
 |
| [get(DataColumn column)](#get-com.groupdocs.assembly.system.data.DataColumn-) | Gets the specified DataColumn.
 |
| [getTable()](#getTable--) | Gets the DataTable for which this row has a schema
 |
| [getChildRows(DataRelation relation)](#getChildRows-com.groupdocs.assembly.system.data.DataRelation-) | Gets the child rows of a DataRow using the specified DataRelation
 |
| [getParentRow(DataRelation relation)](#getParentRow-com.groupdocs.assembly.system.data.DataRelation-) | Gets the parent row of a DataRow using the specified DataRelation
 |
| [getParentRows(DataRelation relation)](#getParentRows-com.groupdocs.assembly.system.data.DataRelation-) | Gets the parent rows using the specified DataRelation
 |
| [set(int columnIndex, Object value)](#set-int-java.lang.Object-) | Sets the data stored in the column specified by index.
 |
| [set(String columnName, Object value)](#set-java.lang.String-java.lang.Object-) | Sets the data stored in the column specified by index.
 |
| [set(DataColumn column, Object value)](#set-com.groupdocs.assembly.system.data.DataColumn-java.lang.Object-) | Sets the data stored in the column specified by index.
 |
| [getRowState()](#getRowState--) | Gets the current state of the row with regard to its relationship to the DataRowCollection.
 |
| [setRowState(int state)](#setRowState-int-) |  |
| [delete()](#delete--) | Deletes the DataRow.
 |
| [setOriginalValue(String columnName, Object data)](#setOriginalValue-java.lang.String-java.lang.Object-) |  |
| [getOriginalValue(String columnName)](#getOriginalValue-java.lang.String-) |  |
| [getItemArray()](#getItemArray--) | Gets all the values for this row through an array.
 |
| [setItemArray(Object[] array)](#setItemArray-java.lang.Object---) | Sets all the values for this row through an array.
 |
| [getKeyValues(DataKey childKey)](#getKeyValues-com.groupdocs.assembly.system.data.DataKey-) |  |
| [remove(int index)](#remove-int-) |  |
| [toString()](#toString--) |  |
### readFrom(ResultSet resultSet) {#readFrom-java.sql.ResultSet-}
```
public boolean readFrom(ResultSet resultSet)
```


Reads values from the ResultSet


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resultSet | java.sql.ResultSet | storage to read from
 |

**Returns:**
boolean - true if no read errors occurred

### get(int index) {#get-int-}
```
public Object get(int index)
```


Gets the data stored in the column specified by index.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the column.
 |

**Returns:**
java.lang.Object - An Object that contains the data.

### get(String columnName) {#get-java.lang.String-}
```
public Object get(String columnName)
```


Gets the data stored in the column specified by name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | The name of the column.
 |

**Returns:**
java.lang.Object - An Object that contains the data.

### get(DataColumn column) {#get-com.groupdocs.assembly.system.data.DataColumn-}
```
public Object get(DataColumn column)
```


Gets the specified DataColumn.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | A DataColumn that contains information about the column.
 |

**Returns:**
java.lang.Object - An Object that contains the data.

### getTable() {#getTable--}
```
public DataTable getTable()
```


Gets the DataTable for which this row has a schema


**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - he DataTable to which this row belongs.

### getChildRows(DataRelation relation) {#getChildRows-com.groupdocs.assembly.system.data.DataRelation-}
```
public DataRow[] getChildRows(DataRelation relation)
```


Gets the child rows of a DataRow using the specified DataRelation


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | The DataRelation to use.
 |

**Returns:**
com.groupdocs.assembly.system.data.DataRow[] - An array of DataRow objects.

### getParentRow(DataRelation relation) {#getParentRow-com.groupdocs.assembly.system.data.DataRelation-}
```
public DataRow getParentRow(DataRelation relation)
```


Gets the parent row of a DataRow using the specified DataRelation


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | The DataRelation to use.
 |

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - The parent DataRow of the current row.

### getParentRows(DataRelation relation) {#getParentRows-com.groupdocs.assembly.system.data.DataRelation-}
```
public DataRow[] getParentRows(DataRelation relation)
```


Gets the parent rows using the specified DataRelation


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) |  |

**Returns:**
com.groupdocs.assembly.system.data.DataRow[]
### set(int columnIndex, Object value) {#set-int-java.lang.Object-}
```
public void set(int columnIndex, Object value)
```


Sets the data stored in the column specified by index.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | The zero-based index of the column.
 |
| value | java.lang.Object | An Object that contains the data.
 |

### set(String columnName, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String columnName, Object value)
```


Sets the data stored in the column specified by index.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | The name of the column.
 |
| value | java.lang.Object | An Object that contains the data.
 |

### set(DataColumn column, Object value) {#set-com.groupdocs.assembly.system.data.DataColumn-java.lang.Object-}
```
public void set(DataColumn column, Object value)
```


Sets the data stored in the column specified by index.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | The name of the column.
 |
| value | java.lang.Object | An Object that contains the data.
 |

### getRowState() {#getRowState--}
```
public int getRowState()
```


Gets the current state of the row with regard to its relationship to the DataRowCollection.


**Returns:**
int - One of the DataRowState values.

### setRowState(int state) {#setRowState-int-}
```
public void setRowState(int state)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| state | int |  |

### delete() {#delete--}
```
public void delete()
```


Deletes the DataRow.


### setOriginalValue(String columnName, Object data) {#setOriginalValue-java.lang.String-java.lang.Object-}
```
public void setOriginalValue(String columnName, Object data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String |  |
| data | java.lang.Object |  |

### getOriginalValue(String columnName) {#getOriginalValue-java.lang.String-}
```
public Object getOriginalValue(String columnName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String |  |

**Returns:**
java.lang.Object
### getItemArray() {#getItemArray--}
```
public Object[] getItemArray()
```


Gets all the values for this row through an array.


**Returns:**
java.lang.Object[] - the values of this row.

### setItemArray(Object[] array) {#setItemArray-java.lang.Object---}
```
public void setItemArray(Object[] array)
```


Sets all the values for this row through an array. The array must have the same size and ordering as the column collection. Passing null in the `setItemArray` indicates that no value was specified.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | java.lang.Object[] | new values for this row.
 |

### getKeyValues(DataKey childKey) {#getKeyValues-com.groupdocs.assembly.system.data.DataKey-}
```
public Object[] getKeyValues(DataKey childKey)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| childKey | [DataKey](../../com.groupdocs.assembly.system.data/datakey) |  |

**Returns:**
java.lang.Object[]
### remove(int index) {#remove-int-}
```
public void remove(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
