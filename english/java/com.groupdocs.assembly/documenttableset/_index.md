---
title: DocumentTableSet
second_title: GroupDocs.Assembly for Java API Reference
description: Provides access to data of multiple tables or spreadsheets located in an external document to be used while assembling a document.
type: docs
weight: 24
url: /java/com.groupdocs.assembly/documenttableset/
---
**Inheritance:**
java.lang.Object
```
public class DocumentTableSet
```

Provides access to data of multiple tables (or spreadsheets) located in an external document to be used while assembling a document. Also, enables to define parent-child relations for the document tables thus simplifying access to related data within template documents.

For documents of Spreadsheet file formats, a [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) instance represents a set of sheets. For documents of other file formats, a [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) instance represents a set of tables.

To access data of the corresponding tables while assembling a document, pass an instance of this class as a data source to one of [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). assembleDocument overloads.

In template documents, a [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) instance should be treated in the same way as if it was a [DataSet](../../com.groupdocs.assembly.system.data/dataset) instance. See template syntax reference for more information.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentTableSet(String documentPath)](#DocumentTableSet-java.lang.String-) | Creates a new instance of this class loading all tables from a document using default [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions). |
| [DocumentTableSet(String documentPath, IDocumentTableLoadHandler loadHandler)](#DocumentTableSet-java.lang.String-com.groupdocs.assembly.IDocumentTableLoadHandler-) | Creates a new instance of this class. |
| [DocumentTableSet(InputStream documentStream)](#DocumentTableSet-java.io.InputStream-) | Creates a new instance of this class loading all tables from a document using default [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions). |
| [DocumentTableSet(InputStream documentStream, IDocumentTableLoadHandler loadHandler)](#DocumentTableSet-java.io.InputStream-com.groupdocs.assembly.IDocumentTableLoadHandler-) | Creates a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [getTables()](#getTables--) | Gets the collection of [DocumentTable](../../com.groupdocs.assembly/documenttable) objects representing tables of this set. |
| [getRelations()](#getRelations--) | Gets the collection of parent-child relations defined for document tables of this set. |
### DocumentTableSet(String documentPath) {#DocumentTableSet-java.lang.String-}
```
public DocumentTableSet(String documentPath)
```


Creates a new instance of this class loading all tables from a document using default [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentPath | java.lang.String | The path to a document containing tables to be accessed. |

### DocumentTableSet(String documentPath, IDocumentTableLoadHandler loadHandler) {#DocumentTableSet-java.lang.String-com.groupdocs.assembly.IDocumentTableLoadHandler-}
```
public DocumentTableSet(String documentPath, IDocumentTableLoadHandler loadHandler)
```


Creates a new instance of this class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentPath | java.lang.String | The path to a document containing tables to be accessed. |
| loadHandler | [IDocumentTableLoadHandler](../../com.groupdocs.assembly/idocumenttableloadhandler) | An [IDocumentTableLoadHandler](../../com.groupdocs.assembly/idocumenttableloadhandler) implementation controlling how document tables are loaded. |

### DocumentTableSet(InputStream documentStream) {#DocumentTableSet-java.io.InputStream-}
```
public DocumentTableSet(InputStream documentStream)
```


Creates a new instance of this class loading all tables from a document using default [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStream | java.io.InputStream | The stream containing a document with tables to be accessed. |

### DocumentTableSet(InputStream documentStream, IDocumentTableLoadHandler loadHandler) {#DocumentTableSet-java.io.InputStream-com.groupdocs.assembly.IDocumentTableLoadHandler-}
```
public DocumentTableSet(InputStream documentStream, IDocumentTableLoadHandler loadHandler)
```


Creates a new instance of this class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStream | java.io.InputStream | The stream containing a document with tables to be accessed. |
| loadHandler | [IDocumentTableLoadHandler](../../com.groupdocs.assembly/idocumenttableloadhandler) | An [IDocumentTableLoadHandler](../../com.groupdocs.assembly/idocumenttableloadhandler) implementation controlling how document tables are loaded. |

### getTables() {#getTables--}
```
public DocumentTableCollection getTables()
```


Gets the collection of [DocumentTable](../../com.groupdocs.assembly/documenttable) objects representing tables of this set.

**Returns:**
[DocumentTableCollection](../../com.groupdocs.assembly/documenttablecollection) - The collection of [DocumentTable](../../com.groupdocs.assembly/documenttable) objects representing tables of this set.
### getRelations() {#getRelations--}
```
public DocumentTableRelationCollection getRelations()
```


Gets the collection of parent-child relations defined for document tables of this set.

**Returns:**
[DocumentTableRelationCollection](../../com.groupdocs.assembly/documenttablerelationcollection) - The collection of parent-child relations defined for document tables of this set.
