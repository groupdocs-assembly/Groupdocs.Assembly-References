---
title: DataTableReader
second_title: GroupDocs.Assembly for Java API Reference
description: 
type: docs
weight: 27
url: /java/com.groupdocs.assembly.system.data/datatablereader/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.assembly.system.data.common.DbDataReader](../../com.groupdocs.assembly.system.data.common/dbdatareader)
```
public class DataTableReader extends DbDataReader
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DataTableReader(DataTable dataTable)](#DataTableReader-com.groupdocs.assembly.system.data.DataTable-) |  |
| [DataTableReader(DataTable[] dataTables)](#DataTableReader-com.groupdocs.assembly.system.data.DataTable---) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFieldCount()](#getFieldCount--) |  |
| [isClosed()](#isClosed--) |  |
| [get(int ordinal)](#get-int-) |  |
| [getName(int ordinal)](#getName-int-) |  |
| [getFieldType(int ordinal)](#getFieldType-int-) |  |
| [getValue(int ordinal)](#getValue-int-) |  |
| [read()](#read--) |  |
| [getDepth()](#getDepth--) |  |
| [getRecordsAffected()](#getRecordsAffected--) |  |
| [close()](#close--) |  |
| [getSchemaTable()](#getSchemaTable--) |  |
| [nextResult()](#nextResult--) |  |
| [hasRows()](#hasRows--) |  |
| [iterator()](#iterator--) |  |
| [get(String columnName)](#get-java.lang.String-) |  |
### DataTableReader(DataTable dataTable) {#DataTableReader-com.groupdocs.assembly.system.data.DataTable-}
```
public DataTableReader(DataTable dataTable)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataTable | [DataTable](../../com.groupdocs.assembly.system.data/datatable) |  |

### DataTableReader(DataTable[] dataTables) {#DataTableReader-com.groupdocs.assembly.system.data.DataTable---}
```
public DataTableReader(DataTable[] dataTables)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataTables | [DataTable\[\]](../../com.groupdocs.assembly.system.data/datatable) |  |

### getFieldCount() {#getFieldCount--}
```
public int getFieldCount()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public boolean isClosed()
```




**Returns:**
boolean
### get(int ordinal) {#get-int-}
```
public Object get(int ordinal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int |  |

**Returns:**
java.lang.Object
### getName(int ordinal) {#getName-int-}
```
public String getName(int ordinal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int |  |

**Returns:**
java.lang.String
### getFieldType(int ordinal) {#getFieldType-int-}
```
public Class getFieldType(int ordinal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int |  |

**Returns:**
java.lang.Class
### getValue(int ordinal) {#getValue-int-}
```
public Object getValue(int ordinal)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ordinal | int |  |

**Returns:**
java.lang.Object
### read() {#read--}
```
public boolean read()
```




**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```




**Returns:**
int
### getRecordsAffected() {#getRecordsAffected--}
```
public int getRecordsAffected()
```




**Returns:**
int
### close() {#close--}
```
public void close()
```




### getSchemaTable() {#getSchemaTable--}
```
public DataTable getSchemaTable()
```




**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable)
### nextResult() {#nextResult--}
```
public boolean nextResult()
```




**Returns:**
boolean
### hasRows() {#hasRows--}
```
public boolean hasRows()
```




**Returns:**
boolean
### iterator() {#iterator--}
```
public Iterator iterator()
```




**Returns:**
java.util.Iterator
### get(String columnName) {#get-java.lang.String-}
```
public Object get(String columnName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnName | java.lang.String |  |

**Returns:**
java.lang.Object
