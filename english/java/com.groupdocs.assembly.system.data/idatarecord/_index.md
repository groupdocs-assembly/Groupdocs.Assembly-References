---
title: IDataRecord
second_title: GroupDocs.Assembly for Java API Reference
description: 
type: docs
weight: 35
url: /java/com.groupdocs.assembly.system.data/idatarecord/
---```
public interface IDataRecord
```
## Methods

| Method | Description |
| --- | --- |
| [getFieldCount()](#getFieldCount--) |  |
| [get(int i)](#get-int-) |  |
| [getName(int i)](#getName-int-) |  |
| [getFieldType(int i)](#getFieldType-int-) |  |
| [getValue(int i)](#getValue-int-) |  |
### getFieldCount() {#getFieldCount--}
```
public abstract int getFieldCount()
```




**Returns:**
int
### get(int i) {#get-int-}
```
public abstract Object get(int i)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int |  |

**Returns:**
java.lang.Object
### getName(int i) {#getName-int-}
```
public abstract String getName(int i)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int |  |

**Returns:**
java.lang.String
### getFieldType(int i) {#getFieldType-int-}
```
public abstract Class getFieldType(int i)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int |  |

**Returns:**
java.lang.Class
### getValue(int i) {#getValue-int-}
```
public abstract Object getValue(int i)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| i | int |  |

**Returns:**
java.lang.Object
