---
title: DocumentTableCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a read-only collection of  objects of a particular  instance.
type: docs
weight: 17
url: /java/com.groupdocs.assembly/documenttablecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class DocumentTableCollection implements Iterable
```

Represents a read-only collection of [DocumentTable](../../com.groupdocs.assembly/documenttable) objects of a particular [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) instance. The collection is filled automatically while loading the corresponding tables from a document and can not be modified. However, properties of [DocumentTable](../../com.groupdocs.assembly/documenttable) objects contained within the collection can be modified.
## Methods

| Method | Description |
| --- | --- |
| [iterator()](#iterator--) | Returns an enumerator to iterate [DocumentTable](../../com.groupdocs.assembly/documenttable) objects of this collection. |
| [contains(String name)](#contains-java.lang.String-) | Returns a value indicating whether this collection contains a table with the specified name. |
| [contains(DocumentTable table)](#contains-com.groupdocs.assembly.DocumentTable-) | Returns a value indicating whether this collection contains the specified table. |
| [indexOf(String name)](#indexOf-java.lang.String-) | Returns the index of a table with the specified name within this collection. |
| [indexOf(DocumentTable table)](#indexOf-com.groupdocs.assembly.DocumentTable-) | Returns the index of the specified table within this collection. |
| [get(int index)](#get-int-) | Gets a [DocumentTable](../../com.groupdocs.assembly/documenttable) instance from the collection at the specified index. |
| [get(String name)](#get-java.lang.String-) | Gets a [DocumentTable](../../com.groupdocs.assembly/documenttable) instance with the specified name from the collection. |
| [getCount()](#getCount--) | Gets the total number of [DocumentTable](../../com.groupdocs.assembly/documenttable) objects in the collection. |
### iterator() {#iterator--}
```
public Iterator iterator()
```


Returns an enumerator to iterate [DocumentTable](../../com.groupdocs.assembly/documenttable) objects of this collection.

**Returns:**
java.util.Iterator - An enumerator to iterate [DocumentTable](../../com.groupdocs.assembly/documenttable) objects of this collection.
### contains(String name) {#contains-java.lang.String-}
```
public boolean contains(String name)
```


Returns a value indicating whether this collection contains a table with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The case-insensitive name of a table to look for. |

**Returns:**
boolean - A value indicating whether this collection contains a table with the specified name.
### contains(DocumentTable table) {#contains-com.groupdocs.assembly.DocumentTable-}
```
public boolean contains(DocumentTable table)
```


Returns a value indicating whether this collection contains the specified table.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| table | [DocumentTable](../../com.groupdocs.assembly/documenttable) | A table to look for. |

**Returns:**
boolean - A value indicating whether this collection contains the specified table.
### indexOf(String name) {#indexOf-java.lang.String-}
```
public int indexOf(String name)
```


Returns the index of a table with the specified name within this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The case-insensitive name of a table to find. |

**Returns:**
int - The zero-based index of a table with the specified name, or -1 if the table does not exist in this collection.
### indexOf(DocumentTable table) {#indexOf-com.groupdocs.assembly.DocumentTable-}
```
public int indexOf(DocumentTable table)
```


Returns the index of the specified table within this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| table | [DocumentTable](../../com.groupdocs.assembly/documenttable) | A table to find. |

**Returns:**
int - The zero-based index of the specified table, or -1 if the table does not exist in this collection.
### get(int index) {#get-int-}
```
public DocumentTable get(int index)
```


Gets a [DocumentTable](../../com.groupdocs.assembly/documenttable) instance from the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the table to return. |

**Returns:**
[DocumentTable](../../com.groupdocs.assembly/documenttable) - A [DocumentTable](../../com.groupdocs.assembly/documenttable) instance from the collection at the specified index.
### get(String name) {#get-java.lang.String-}
```
public DocumentTable get(String name)
```


Gets a [DocumentTable](../../com.groupdocs.assembly/documenttable) instance with the specified name from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The case-insensitive name of the table to return. |

**Returns:**
[DocumentTable](../../com.groupdocs.assembly/documenttable) - A [DocumentTable](../../com.groupdocs.assembly/documenttable) instance with the specified name from the collection or null if such an instance does not exist.
### getCount() {#getCount--}
```
public int getCount()
```


Gets the total number of [DocumentTable](../../com.groupdocs.assembly/documenttable) objects in the collection.

**Returns:**
int - The total number of [DocumentTable](../../com.groupdocs.assembly/documenttable) objects in the collection.
