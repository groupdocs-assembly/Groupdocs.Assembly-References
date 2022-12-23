---
title: IDataReader
second_title: GroupDocs.Assembly for Java API Reference
description: Provides a means of reading one or more forward-only streams of result sets obtained by executing a command at a data source and is implemented by .NET Framework data providers that access relational databases.
type: docs
weight: 34
url: /java/com.groupdocs.assembly.system.data/idatareader/
---
**All Implemented Interfaces:**
[com.groupdocs.assembly.system.data.IDataRecord](../../com.groupdocs.assembly.system.data/idatarecord)
```
public interface IDataReader extends IDataRecord
```

Provides a means of reading one or more forward-only streams of result sets obtained by executing a command at a data source, and is implemented by .NET Framework data providers that access relational databases.
## Methods

| Method | Description |
| --- | --- |
| [read()](#read--) | Advances the [IDataReader](../../com.groupdocs.assembly.system.data/idatareader) to the next record. |
| [getDepth()](#getDepth--) | Gets a value indicating the depth of nesting for the current row. |
| [isClosed()](#isClosed--) | Gets a value indicating whether the data reader is closed. |
| [getRecordsAffected()](#getRecordsAffected--) | Gets the number of rows changed, inserted, or deleted by execution of the SQL statement. |
| [close()](#close--) | Closes the [IDataReader](../../com.groupdocs.assembly.system.data/idatareader) Object. |
| [getSchemaTable()](#getSchemaTable--) | Returns a [DataTable](../../com.groupdocs.assembly.system.data/datatable) that describes the column metadata of the [IDataReader](../../com.groupdocs.assembly.system.data/idatareader). |
| [nextResult()](#nextResult--) | Advances the data reader to the next result, when reading the results of batch SQL statements. |
### read() {#read--}
```
public abstract boolean read()
```


Advances the [IDataReader](../../com.groupdocs.assembly.system.data/idatareader) to the next record.

**Returns:**
boolean - true if there are more rows; otherwise, false.
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```


Gets a value indicating the depth of nesting for the current row.

**Returns:**
int - The level of nesting.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Gets a value indicating whether the data reader is closed.

**Returns:**
boolean - true if the data reader is closed; otherwise, false.
### getRecordsAffected() {#getRecordsAffected--}
```
public abstract int getRecordsAffected()
```


Gets the number of rows changed, inserted, or deleted by execution of the SQL statement.

**Returns:**
int - The number of rows changed, inserted, or deleted; 0 if no rows were affected or the statement failed; and -1 for SELECT statements.
### close() {#close--}
```
public abstract void close()
```


Closes the [IDataReader](../../com.groupdocs.assembly.system.data/idatareader) Object.

### getSchemaTable() {#getSchemaTable--}
```
public abstract DataTable getSchemaTable()
```


Returns a [DataTable](../../com.groupdocs.assembly.system.data/datatable) that describes the column metadata of the [IDataReader](../../com.groupdocs.assembly.system.data/idatareader).

**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable) - A [DataTable](../../com.groupdocs.assembly.system.data/datatable) that describes the column metadata.
### nextResult() {#nextResult--}
```
public abstract boolean nextResult()
```


Advances the data reader to the next result, when reading the results of batch SQL statements.

**Returns:**
boolean - true if there are more rows; otherwise, false.
