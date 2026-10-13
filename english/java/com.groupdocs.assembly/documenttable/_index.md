---
title: DocumentTable
second_title: GroupDocs.Assembly for Java API Reference
description: 
type: docs
weight: 16
url: /java/com.groupdocs.assembly/documenttable/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.assembly.IDocumentTableObject, com.groupdocs.assembly.IDataSourceFacade
```
public class DocumentTable implements IDocumentTableObject, IDataSourceFacade
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentTable(String documentPath, int indexInDocument)](#DocumentTable-java.lang.String-int-) |  |
| [DocumentTable(String documentPath, int indexInDocument, DocumentTableOptions options)](#DocumentTable-java.lang.String-int-com.groupdocs.assembly.DocumentTableOptions-) |  |
| [DocumentTable(InputStream documentStream, int indexInDocument)](#DocumentTable-java.io.InputStream-int-) |  |
| [DocumentTable(InputStream documentStream, int indexInDocument, DocumentTableOptions options)](#DocumentTable-java.io.InputStream-int-com.groupdocs.assembly.DocumentTableOptions-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) |  |
| [setName(String value)](#setName-java.lang.String-) |  |
| [getIndexInDocument()](#getIndexInDocument--) |  |
| [getColumns()](#getColumns--) |  |
### DocumentTable(String documentPath, int indexInDocument) {#DocumentTable-java.lang.String-int-}
```
public DocumentTable(String documentPath, int indexInDocument)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentPath | java.lang.String |  |
| indexInDocument | int |  |

### DocumentTable(String documentPath, int indexInDocument, DocumentTableOptions options) {#DocumentTable-java.lang.String-int-com.groupdocs.assembly.DocumentTableOptions-}
```
public DocumentTable(String documentPath, int indexInDocument, DocumentTableOptions options)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentPath | java.lang.String |  |
| indexInDocument | int |  |
| options | [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions) |  |

### DocumentTable(InputStream documentStream, int indexInDocument) {#DocumentTable-java.io.InputStream-int-}
```
public DocumentTable(InputStream documentStream, int indexInDocument)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStream | java.io.InputStream |  |
| indexInDocument | int |  |

### DocumentTable(InputStream documentStream, int indexInDocument, DocumentTableOptions options) {#DocumentTable-java.io.InputStream-int-com.groupdocs.assembly.DocumentTableOptions-}
```
public DocumentTable(InputStream documentStream, int indexInDocument, DocumentTableOptions options)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStream | java.io.InputStream |  |
| indexInDocument | int |  |
| options | [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions) |  |

### getName() {#getName--}
```
public String getName()
```




**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getIndexInDocument() {#getIndexInDocument--}
```
public int getIndexInDocument()
```




**Returns:**
int
### getColumns() {#getColumns--}
```
public DocumentTableColumnCollection getColumns()
```




**Returns:**
[DocumentTableColumnCollection](../../com.groupdocs.assembly/documenttablecolumncollection)
