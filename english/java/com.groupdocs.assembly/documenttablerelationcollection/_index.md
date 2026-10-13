---
title: DocumentTableRelationCollection
second_title: GroupDocs.Assembly for Java API Reference
description: 
type: docs
weight: 23
url: /java/com.groupdocs.assembly/documenttablerelationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class DocumentTableRelationCollection implements Iterable
```
## Methods

| Method | Description |
| --- | --- |
| [add(DocumentTableColumn parentColumn, DocumentTableColumn childColumn)](#add-com.groupdocs.assembly.DocumentTableColumn-com.groupdocs.assembly.DocumentTableColumn-) |  |
| [remove(DocumentTableRelation relation)](#remove-com.groupdocs.assembly.DocumentTableRelation-) |  |
| [removeAt(int index)](#removeAt-int-) |  |
| [clear()](#clear--) |  |
| [iterator()](#iterator--) |  |
| [contains(DocumentTableRelation relation)](#contains-com.groupdocs.assembly.DocumentTableRelation-) |  |
| [indexOf(DocumentTableRelation relation)](#indexOf-com.groupdocs.assembly.DocumentTableRelation-) |  |
| [get(int index)](#get-int-) |  |
| [getCount()](#getCount--) |  |
### add(DocumentTableColumn parentColumn, DocumentTableColumn childColumn) {#add-com.groupdocs.assembly.DocumentTableColumn-com.groupdocs.assembly.DocumentTableColumn-}
```
public DocumentTableRelation add(DocumentTableColumn parentColumn, DocumentTableColumn childColumn)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentColumn | [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) |  |
| childColumn | [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) |  |

**Returns:**
[DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation)
### remove(DocumentTableRelation relation) {#remove-com.groupdocs.assembly.DocumentTableRelation-}
```
public void remove(DocumentTableRelation relation)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) |  |

### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

### clear() {#clear--}
```
public void clear()
```




### iterator() {#iterator--}
```
public Iterator iterator()
```




**Returns:**
java.util.Iterator
### contains(DocumentTableRelation relation) {#contains-com.groupdocs.assembly.DocumentTableRelation-}
```
public boolean contains(DocumentTableRelation relation)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) |  |

**Returns:**
boolean
### indexOf(DocumentTableRelation relation) {#indexOf-com.groupdocs.assembly.DocumentTableRelation-}
```
public int indexOf(DocumentTableRelation relation)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) |  |

**Returns:**
int
### get(int index) {#get-int-}
```
public DocumentTableRelation get(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation)
### getCount() {#getCount--}
```
public int getCount()
```




**Returns:**
int
