---
title: DocumentTableColumnCollection
second_title: GroupDocs.Assembly for Java API Reference
description: Represents a read-only collection of com.groupdocs.assembly.DocumentTableColumn objects of a particular com.groupdocs.assembly.DocumentTable instance.
type: docs
weight: 19
url: /java/com.groupdocs.assembly/documenttablecolumncollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class DocumentTableColumnCollection implements Iterable
```

Represents a read-only collection of com.groupdocs.assembly.DocumentTableColumn objects of a particular com.groupdocs.assembly.DocumentTable instance. The collection is filled automatically while loading the corresponding table from a document and can not be modified. However, properties of com.groupdocs.assembly.DocumentTableColumn objects contained within the collection can be modified.
## Methods

| Method | Description |
| --- | --- |
| [iterator()](#iterator--) | Returns an enumerator to iterate com.groupdocs.assembly.DocumentTableColumn objects of this collection. |
| [contains(String name)](#contains-java.lang.String-) | Returns a value indicating whether this collection contains a column with the specified name. |
| [contains(DocumentTableColumn column)](#contains-com.groupdocs.assembly.DocumentTableColumn-) | Returns a value indicating whether this collection contains the specified column. |
| [indexOf(String name)](#indexOf-java.lang.String-) | Returns the index of a column with the specified name within this collection. |
| [indexOf(DocumentTableColumn column)](#indexOf-com.groupdocs.assembly.DocumentTableColumn-) | Returns the index of the specified column within this collection. |
| [get(int index)](#get-int-) | Gets a com.groupdocs.assembly.DocumentTableColumn instance from the collection at the specified index. |
| [get(String name)](#get-java.lang.String-) | Gets a com.groupdocs.assembly.DocumentTableColumn instance with the specified name from the collection. |
| [getCount()](#getCount--) | Gets the total number of com.groupdocs.assembly.DocumentTableColumn objects in the collection. |
### iterator() {#iterator--}
```
public Iterator iterator()
```


Returns an enumerator to iterate com.groupdocs.assembly.DocumentTableColumn objects of this collection.

**Returns:**
java.util.Iterator - An enumerator to iterate com.groupdocs.assembly.DocumentTableColumn objects of this collection.
### contains(String name) {#contains-java.lang.String-}
```
public boolean contains(String name)
```


Returns a value indicating whether this collection contains a column with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The case-insensitive name of a column to look for. |

**Returns:**
boolean - A value indicating whether this collection contains a column with the specified name.
### contains(DocumentTableColumn column) {#contains-com.groupdocs.assembly.DocumentTableColumn-}
```
public boolean contains(DocumentTableColumn column)
```


Returns a value indicating whether this collection contains the specified column.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) | A column to look for. |

**Returns:**
boolean - A value indicating whether this collection contains the specified column.
### indexOf(String name) {#indexOf-java.lang.String-}
```
public int indexOf(String name)
```


Returns the index of a column with the specified name within this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The case-insensitive name of a column to find. |

**Returns:**
int - The zero-based index of a column with the specified name, or -1 if the column does not exist in this collection.
### indexOf(DocumentTableColumn column) {#indexOf-com.groupdocs.assembly.DocumentTableColumn-}
```
public int indexOf(DocumentTableColumn column)
```


Returns the index of the specified column within this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| column | [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) | A column to find. |

**Returns:**
int - The zero-based index of the specified column, or -1 if the column does not exist in this collection.
### get(int index) {#get-int-}
```
public DocumentTableColumn get(int index)
```


Gets a com.groupdocs.assembly.DocumentTableColumn instance from the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the column to return. |

**Returns:**
[DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) - A com.groupdocs.assembly.DocumentTableColumn instance from the collection at the specified index.
### get(String name) {#get-java.lang.String-}
```
public DocumentTableColumn get(String name)
```


Gets a com.groupdocs.assembly.DocumentTableColumn instance with the specified name from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The case-insensitive name of the column to return. |

**Returns:**
[DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) - A com.groupdocs.assembly.DocumentTableColumn instance with the specified name from the collection or null if such an instance does not exist.
### getCount() {#getCount--}
```
public int getCount()
```


Gets the total number of com.groupdocs.assembly.DocumentTableColumn objects in the collection.

**Returns:**
int - The total number of com.groupdocs.assembly.DocumentTableColumn objects in the collection.
