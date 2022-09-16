---
title: DocumentTableRelationCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents the collection of  objects of a single  instance.
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

Represents the collection of [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) objects of a single [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) instance.
## Methods

| Method | Description |
| --- | --- |
| [add(DocumentTableColumn parentColumn, DocumentTableColumn childColumn)](#add-com.groupdocs.assembly.DocumentTableColumn-com.groupdocs.assembly.DocumentTableColumn-) | Creates a [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) object for the specified parent and child columns, and adds it to the collection. |
| [remove(DocumentTableRelation relation)](#remove-com.groupdocs.assembly.DocumentTableRelation-) | Removes the specified relation from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the relation at the specified index from the collection. |
| [clear()](#clear--) | Clears the collection of any relations. |
| [iterator()](#iterator--) | Returns an enumerator to iterate [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) objects of this collection. |
| [contains(DocumentTableRelation relation)](#contains-com.groupdocs.assembly.DocumentTableRelation-) | Returns a value indicating whether this collection contains the specified relation. |
| [indexOf(DocumentTableRelation relation)](#indexOf-com.groupdocs.assembly.DocumentTableRelation-) | Returns the index of the specified relation within this collection. |
| [get(int index)](#get-int-) | Gets a [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) instance from the collection at the specified index. |
| [getCount()](#getCount--) | Gets the total number of [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) objects in the collection. |
### add(DocumentTableColumn parentColumn, DocumentTableColumn childColumn) {#add-com.groupdocs.assembly.DocumentTableColumn-com.groupdocs.assembly.DocumentTableColumn-}
```
public DocumentTableRelation add(DocumentTableColumn parentColumn, DocumentTableColumn childColumn)
```


Creates a [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) object for the specified parent and child columns, and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentColumn | [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) | The parent column of the relation. |
| childColumn | [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) | The child column of the relation. |

**Returns:**
[DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) - The created relation.
### remove(DocumentTableRelation relation) {#remove-com.groupdocs.assembly.DocumentTableRelation-}
```
public void remove(DocumentTableRelation relation)
```


Removes the specified relation from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) | The relation to remove. |

### removeAt(int index) {#removeAt-int-}
```
public void removeAt(int index)
```


Removes the relation at the specified index from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the relation to remove. |

### clear() {#clear--}
```
public void clear()
```


Clears the collection of any relations.

### iterator() {#iterator--}
```
public Iterator iterator()
```


Returns an enumerator to iterate [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) objects of this collection.

**Returns:**
java.util.Iterator - An enumerator to iterate [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) objects of this collection.
### contains(DocumentTableRelation relation) {#contains-com.groupdocs.assembly.DocumentTableRelation-}
```
public boolean contains(DocumentTableRelation relation)
```


Returns a value indicating whether this collection contains the specified relation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) | A relation to look for. |

**Returns:**
boolean - A value indicating whether this collection contains the specified relation.
### indexOf(DocumentTableRelation relation) {#indexOf-com.groupdocs.assembly.DocumentTableRelation-}
```
public int indexOf(DocumentTableRelation relation)
```


Returns the index of the specified relation within this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| relation | [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) | A relation to find. |

**Returns:**
int - The zero-based index of the specified relation, or -1 if the relation does not exist in this collection.
### get(int index) {#get-int-}
```
public DocumentTableRelation get(int index)
```


Gets a [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) instance from the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the relation to return. |

**Returns:**
[DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) - A [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) instance from the collection at the specified index.
### getCount() {#getCount--}
```
public int getCount()
```


Gets the total number of [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) objects in the collection.

**Returns:**
int - The total number of [DocumentTableRelation](../../com.groupdocs.assembly/documenttablerelation) objects in the collection.
