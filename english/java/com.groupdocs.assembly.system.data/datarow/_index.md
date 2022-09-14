---
title: DataRow
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a row of data in a com.groupdocs.assembly.system.data.DataTable.
type: docs
weight: 20
url: /java/com.groupdocs.assembly.system.data/datarow/
---
**Inheritance:**
java.lang.Object
```
public class DataRow
```

Represents a row of data in a com.groupdocs.assembly.system.data.DataTable.
## Methods

| Method | Description |
| --- | --- |
| [readFrom(ResultSet resultSet)](#readFrom-java.sql.ResultSet-) | Reads values from the java.sql.ResultSet |
| [get(int columnIndex)](#get-int-) | Gets the data stored in the column specified by index. |
| [get(String columnName)](#get-java.lang.String-) | Gets the data stored in the column specified by name. |
| [get(DataColumn column)](#get-com.groupdocs.assembly.system.data.DataColumn-) | Gets the data stored in the specified com.groupdocs.assembly.system.data.DataColumn. |
| [getTable()](#getTable--) | Gets the com.groupdocs.assembly.system.data.DataTable for which this row has a schema. |
| [getChildRows(DataRelation relation)](#getChildRows-com.groupdocs.assembly.system.data.DataRelation-) | Gets the child rows of this com.groupdocs.assembly.system.data.DataRow using the specified com.groupdocs.assembly.system.data.DataRelation. |
| [getParentRow(DataRelation relation)](#getParentRow-com.groupdocs.assembly.system.data.DataRelation-) | Gets the parent row of a com.groupdocs.assembly.system.data.DataRow using the specified com.groupdocs.assembly.system.data.DataRelation. |
| [getParentRows(DataRelation relation)](#getParentRows-com.groupdocs.assembly.system.data.DataRelation-) | Gets the parent rows of a com.groupdocs.assembly.system.data.DataRow using the specified com.groupdocs.assembly.system.data.DataRelation. |
| [set(int value, Object columnIndex)](#set-int-java.lang.Object-) | Sets the data stored in the column specified by index. |
| [set(String value, Object columnName)](#set-java.lang.String-java.lang.Object-) | Sets the data stored in the column specified by name. |
| [set(DataColumn value, Object column)](#set-com.groupdocs.assembly.system.data.DataColumn-java.lang.Object-) | Sets the data stored in the specified com.groupdocs.assembly.system.data.DataColumn. |
| [getRowState()](#getRowState--) | Gets the current state of the row with regard to its relationship to the com.groupdocs.assembly.system.data.DataRowCollection. |
| [setRowState(int state)](#setRowState-int-) |  |
| [delete()](#delete--) | Deletes the com.groupdocs.assembly.system.data.DataRow. |
| [setOriginalValue(String columnName, Object data)](#setOriginalValue-java.lang.String-java.lang.Object-) |  |
| [getOriginalValue(String columnName)](#getOriginalValue-java.lang.String-) |  |
| [getItemArray()](#getItemArray--) | Gets all the values for this row through an array. |
| [setItemArray(Object[] value)](#setItemArray-java.lang.Object---) | Sets all the values for this row through an array. |
| [getKeyValues(DataKey childKey)](#getKeyValues-com.groupdocs.assembly.system.data.DataKey-) |  |
| [remove(int index)](#remove-int-) |  |
| [toString()](#toString--) |  |
### readFrom(ResultSet resultSet) {#readFrom-java.sql.ResultSet-}
```
public boolean readFrom(ResultSet resultSet)
```


Reads values from the java.sql.ResultSet

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resultSet | java.sql.ResultSet | storage to read from |

**Returns:**
boolean - true if no read errors occurred
### get(int columnIndex) {#get-int-}
```
public Object get(int columnIndex)
```


Gets the data stored in the column specified by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | The zero-based index of the column. |

**Returns:**
java.lang.Object - An java.lang.Object that contains the data.
### get(String columnName) {#get-java.lang.String-}
```
public Object get(String columnName)
```


Gets the data stored in the column specified by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String | The name of the column. |

**Returns:**
java.lang.Object - An java.lang.Object that contains the data.
### get(DataColumn column) {#get-com.groupdocs.assembly.system.data.DataColumn-}
```
public Object get(DataColumn column)
```


Gets the data stored in the specified com.groupdocs.assembly.system.data.DataColumn.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | A com.groupdocs.assembly.system.data.DataColumn that contains the data. |

**Returns:**
java.lang.Object - An java.lang.Object that contains the data.
### getTable() {#getTable--}
```
public DataTable getTable()
```


Gets the com.groupdocs.assembly.system.data.DataTable for which this row has a schema.

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - The com.groupdocs.assembly.system.data.DataTable to which this row belongs.
### getChildRows(DataRelation relation) {#getChildRows-com.groupdocs.assembly.system.data.DataRelation-}
```
public DataRow[] getChildRows(DataRelation relation)
```


Gets the child rows of this com.groupdocs.assembly.system.data.DataRow using the specified com.groupdocs.assembly.system.data.DataRelation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | The com.groupdocs.assembly.system.data.DataRelation to use. |

**Returns:**
com.groupdocs.assembly.system.data.DataRow[] - An array of com.groupdocs.assembly.system.data.DataRow objects or an array of length zero.
### getParentRow(DataRelation relation) {#getParentRow-com.groupdocs.assembly.system.data.DataRelation-}
```
public DataRow getParentRow(DataRelation relation)
```


Gets the parent row of a com.groupdocs.assembly.system.data.DataRow using the specified com.groupdocs.assembly.system.data.DataRelation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | The com.groupdocs.assembly.system.data.DataRelation to use. |

**Returns:**
[DataRow](../../com.groupdocs.assembly.system.data/datarow) - The parent com.groupdocs.assembly.system.data.DataRow of the current row.
### getParentRows(DataRelation relation) {#getParentRows-com.groupdocs.assembly.system.data.DataRelation-}
```
public DataRow[] getParentRows(DataRelation relation)
```


Gets the parent rows of a com.groupdocs.assembly.system.data.DataRow using the specified com.groupdocs.assembly.system.data.DataRelation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DataRelation](../../com.groupdocs.assembly.system.data/datarelation) | The com.groupdocs.assembly.system.data.DataRelation to use. |

**Returns:**
com.groupdocs.assembly.system.data.DataRow[] - An array of com.groupdocs.assembly.system.data.DataRow objects or an array of length zero.
### set(int value, Object columnIndex) {#set-int-java.lang.Object-}
```
public void set(int value, Object columnIndex)
```


Sets the data stored in the column specified by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | An java.lang.Object that contains the data. |
| columnIndex | java.lang.Object | The zero-based index of the column. |

### set(String value, Object columnName) {#set-java.lang.String-java.lang.Object-}
```
public void set(String value, Object columnName)
```


Sets the data stored in the column specified by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | An java.lang.Object that contains the data. |
| columnName | java.lang.Object | The name of the column. |

### set(DataColumn value, Object column) {#set-com.groupdocs.assembly.system.data.DataColumn-java.lang.Object-}
```
public void set(DataColumn value, Object column)
```


Sets the data stored in the specified com.groupdocs.assembly.system.data.DataColumn.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DataColumn](../../com.groupdocs.assembly.system.data/datacolumn) | An java.lang.Object that contains the data. |
| column | java.lang.Object | A com.groupdocs.assembly.system.data.DataColumn that contains the data. |

### getRowState() {#getRowState--}
```
public int getRowState()
```


Gets the current state of the row with regard to its relationship to the com.groupdocs.assembly.system.data.DataRowCollection.

**Returns:**
int - One of the com.groupdocs.assembly.system.data.DataRowState values. The returned value is a bitwise combination of com.groupdocs.assembly.system.data.DataRowState constants.
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


Deletes the com.groupdocs.assembly.system.data.DataRow.

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
java.lang.Object[] - An array of type java.lang.Object.
### setItemArray(Object[] value) {#setItemArray-java.lang.Object---}
```
public void setItemArray(Object[] value)
```


Sets all the values for this row through an array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object[] | An array of type java.lang.Object. |

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
