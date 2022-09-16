---
title: DataTableReader
second_title: GroupDocs.Assembly for Java API Reference
description: The  obtains the contents of one or more  objects in the form of one or more read-only forward-only result sets.
type: docs
weight: 27
url: /java/com.groupdocs.assembly.system.data/datatablereader/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.assembly.system.data.common.DbDataReader](../../com.groupdocs.assembly.system.data.common/dbdatareader)
```
public final class DataTableReader extends DbDataReader
```

The [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) obtains the contents of one or more [DataTable](../../com.groupdocs.assembly.system.data/datatable) objects in the form of one or more read-only, forward-only result sets.
## Constructors

| Constructor | Description |
| --- | --- |
| [DataTableReader(DataTable dataTable)](#DataTableReader-com.groupdocs.assembly.system.data.DataTable-) | Initializes a new instance of the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) class by using data from the supplied [DataTable](../../com.groupdocs.assembly.system.data/datatable). |
| [DataTableReader(DataTable dataTables)](#DataTableReader-com.groupdocs.assembly.system.data.DataTable---) | Initializes a new instance of the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) class using the supplied array of [DataTable](../../com.groupdocs.assembly.system.data/datatable) objects. |
## Methods

| Method | Description |
| --- | --- |
| [getFieldCount()](#getFieldCount--) | Returns the number of columns in the current row. |
| [isClosed()](#isClosed--) | Gets a value that indicates whether the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) is closed. |
| [get(int ordinal)](#get-int-) | Gets the value of the specified column in its native format given the column ordinal. |
| [getName(int ordinal)](#getName-int-) | Gets the value of the specified column as a java.lang.String. |
| [getFieldType(int ordinal)](#getFieldType-int-) | Gets the java.lang.Class that is the data type of the object. |
| [getValue(int ordinal)](#getValue-int-) | Gets the value of the specified column in its native format. |
| [read()](#read--) | Advances the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) to the next record. |
| [getDepth()](#getDepth--) | The depth of nesting for the current row of the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader). |
| [getRecordsAffected()](#getRecordsAffected--) | Gets the number of rows inserted, changed, or deleted by execution of the SQL statement. |
| [close()](#close--) | Closes the current [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader). |
| [getSchemaTable()](#getSchemaTable--) | Returns a [DataTable](../../com.groupdocs.assembly.system.data/datatable) that describes the column metadata of the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader). |
| [nextResult()](#nextResult--) | Advances the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) to the next result set, if any. |
| [hasRows()](#hasRows--) | Gets a value that indicates whether the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) contains one or more rows. |
| [iterator()](#iterator--) | Returns an enumerator that can be used to iterate through the item collection. |
| [get(String name)](#get-java.lang.String-) | Gets the value of the specified column in its native format given the column name. |
### DataTableReader(DataTable dataTable) {#DataTableReader-com.groupdocs.assembly.system.data.DataTable-}
```
public DataTableReader(DataTable dataTable)
```


Initializes a new instance of the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) class by using data from the supplied [DataTable](../../com.groupdocs.assembly.system.data/datatable).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) | The [DataTable](../../com.groupdocs.assembly.system.data/datatable) from which the new [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) obtains its result set. |

### DataTableReader(DataTable dataTables) {#DataTableReader-com.groupdocs.assembly.system.data.DataTable---}
```
public DataTableReader(DataTable dataTables)
```


Initializes a new instance of the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) class using the supplied array of [DataTable](../../com.groupdocs.assembly.system.data/datatable) objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataTables | [DataTable\[\]](../../com.groupdocs.assembly.system.data/datatable) | The array of [DataTable](../../com.groupdocs.assembly.system.data/datatable) objects that supplies the results for the new [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) object. |

### getFieldCount() {#getFieldCount--}
```
public final int getFieldCount()
```


Returns the number of columns in the current row.

**Returns:**
int - When not positioned in a valid result set, 0; otherwise the number of columns in the current row.
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Gets a value that indicates whether the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) is closed.

**Returns:**
boolean - Returns true if the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) is closed; otherwise, false.
### get(int ordinal) {#get-int-}
```
public final Object get(int ordinal)
```


Gets the value of the specified column in its native format given the column ordinal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int | The zero-based column ordinal. |

**Returns:**
java.lang.Object - The value of the specified column in its native format.
### getName(int ordinal) {#getName-int-}
```
public final String getName(int ordinal)
```


Gets the value of the specified column as a java.lang.String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int | The zero-based column ordinal |

**Returns:**
java.lang.String - The name of the specified column.
### getFieldType(int ordinal) {#getFieldType-int-}
```
public final Class getFieldType(int ordinal)
```


Gets the java.lang.Class that is the data type of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int | The zero-based column ordinal. |

**Returns:**
java.lang.Class - The java.lang.Class that is the data type of the object.
### getValue(int ordinal) {#getValue-int-}
```
public final Object getValue(int ordinal)
```


Gets the value of the specified column in its native format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int | The zero-based column ordinal |

**Returns:**
java.lang.Object - The value of the specified column. This method returns DBNull for null columns.
### read() {#read--}
```
public final boolean read()
```


Advances the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) to the next record.

**Returns:**
boolean - true if there was another row to read; otherwise false.
### getDepth() {#getDepth--}
```
public final int getDepth()
```


The depth of nesting for the current row of the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader).

**Returns:**
int - The depth of nesting for the current row; always zero.
### getRecordsAffected() {#getRecordsAffected--}
```
public final int getRecordsAffected()
```


Gets the number of rows inserted, changed, or deleted by execution of the SQL statement.

**Returns:**
int - The [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) does not support this property and always returns 0.
### close() {#close--}
```
public final void close()
```


Closes the current [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader).

### getSchemaTable() {#getSchemaTable--}
```
public final DataTable getSchemaTable()
```


Returns a [DataTable](../../com.groupdocs.assembly.system.data/datatable) that describes the column metadata of the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader).

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - A [DataTable](../../com.groupdocs.assembly.system.data/datatable) that describes the column metadata.
### nextResult() {#nextResult--}
```
public final boolean nextResult()
```


Advances the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) to the next result set, if any.

**Returns:**
boolean - true if there was another result set; otherwise false.
### hasRows() {#hasRows--}
```
public final boolean hasRows()
```


Gets a value that indicates whether the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) contains one or more rows.

**Returns:**
boolean - true if the [DataTableReader](../../com.groupdocs.assembly.system.data/datatablereader) contains one or more rows; otherwise false.
### iterator() {#iterator--}
```
public final Iterator iterator()
```


Returns an enumerator that can be used to iterate through the item collection.

**Returns:**
java.util.Iterator - An java.util.Iterator object that represents the item collection.
### get(String name) {#get-java.lang.String-}
```
public final Object get(String name)
```


Gets the value of the specified column in its native format given the column name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the column. |

**Returns:**
java.lang.Object - The value of the specified column in its native format.
