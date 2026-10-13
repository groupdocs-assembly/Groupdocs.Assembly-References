---
title: DocumentTableSet
second_title: GroupDocs.Assembly for Java API Reference
description: 
type: docs
weight: 24
url: /java/com.groupdocs.assembly/documenttableset/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.assembly.IDataSourceFacade
```
public class DocumentTableSet implements IDataSourceFacade
```
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentTableSet(String documentPath)](#DocumentTableSet-java.lang.String-) |  |
| [DocumentTableSet(String documentPath, IDocumentTableLoadHandler loadHandler)](#DocumentTableSet-java.lang.String-com.groupdocs.assembly.IDocumentTableLoadHandler-) |  |
| [DocumentTableSet(InputStream documentStream)](#DocumentTableSet-java.io.InputStream-) |  |
| [DocumentTableSet(InputStream documentStream, IDocumentTableLoadHandler loadHandler)](#DocumentTableSet-java.io.InputStream-com.groupdocs.assembly.IDocumentTableLoadHandler-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTables()](#getTables--) |  |
| [getRelations()](#getRelations--) |  |
### DocumentTableSet(String documentPath) {#DocumentTableSet-java.lang.String-}
```
public DocumentTableSet(String documentPath)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentPath | java.lang.String |  |

### DocumentTableSet(String documentPath, IDocumentTableLoadHandler loadHandler) {#DocumentTableSet-java.lang.String-com.groupdocs.assembly.IDocumentTableLoadHandler-}
```
public DocumentTableSet(String documentPath, IDocumentTableLoadHandler loadHandler)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentPath | java.lang.String |  |
| loadHandler | [IDocumentTableLoadHandler](../../com.groupdocs.assembly/idocumenttableloadhandler) |  |

### DocumentTableSet(InputStream documentStream) {#DocumentTableSet-java.io.InputStream-}
```
public DocumentTableSet(InputStream documentStream)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStream | java.io.InputStream |  |

### DocumentTableSet(InputStream documentStream, IDocumentTableLoadHandler loadHandler) {#DocumentTableSet-java.io.InputStream-com.groupdocs.assembly.IDocumentTableLoadHandler-}
```
public DocumentTableSet(InputStream documentStream, IDocumentTableLoadHandler loadHandler)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStream | java.io.InputStream |  |
| loadHandler | [IDocumentTableLoadHandler](../../com.groupdocs.assembly/idocumenttableloadhandler) |  |

### getTables() {#getTables--}
```
public DocumentTableCollection getTables()
```




**Returns:**
[DocumentTableCollection](../../com.groupdocs.assembly/documenttablecollection)
### getRelations() {#getRelations--}
```
public DocumentTableRelationCollection getRelations()
```




**Returns:**
[DocumentTableRelationCollection](../../com.groupdocs.assembly/documenttablerelationcollection)
