---
title: IDataReader
second_title: GroupDocs.Assembly for Java API Reference
description: 
type: docs
weight: 34
url: /java/com.groupdocs.assembly.system.data/idatareader/
---
**All Implemented Interfaces:**
[com.groupdocs.assembly.system.data.IDataRecord](../../com.groupdocs.assembly.system.data/idatarecord)
```
public interface IDataReader extends IDataRecord
```
## Methods

| Method | Description |
| --- | --- |
| [read()](#read--) |  |
| [getDepth()](#getDepth--) |  |
| [isClosed()](#isClosed--) |  |
| [getRecordsAffected()](#getRecordsAffected--) |  |
| [close()](#close--) |  |
| [getSchemaTable()](#getSchemaTable--) |  |
| [nextResult()](#nextResult--) |  |
### read() {#read--}
```
public abstract boolean read()
```




**Returns:**
boolean
### getDepth() {#getDepth--}
```
public abstract int getDepth()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```




**Returns:**
boolean
### getRecordsAffected() {#getRecordsAffected--}
```
public abstract int getRecordsAffected()
```




**Returns:**
int
### close() {#close--}
```
public abstract void close()
```




### getSchemaTable() {#getSchemaTable--}
```
public abstract DataTable getSchemaTable()
```




**Returns:**
[DataTable](../../com.groupdocs.assembly.system.data/datatable)
### nextResult() {#nextResult--}
```
public abstract boolean nextResult()
```




**Returns:**
boolean
