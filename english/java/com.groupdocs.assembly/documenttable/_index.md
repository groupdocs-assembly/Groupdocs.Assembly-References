---
title: DocumentTable
second_title: GroupDocs.Assembly for Java API Reference
description: Provides access to data of a single table or spreadsheet located in an external document to be used while assembling a document.
type: docs
weight: 16
url: /java/com.groupdocs.assembly/documenttable/
---
**Inheritance:**
java.lang.Object
```
public class DocumentTable
```

Provides access to data of a single table (or spreadsheet) located in an external document to be used while assembling a document.

For documents of Spreadsheet file formats, a [DocumentTable](../../com.groupdocs.assembly/documenttable) instance represents a single sheet. For documents of other file formats, a [DocumentTable](../../com.groupdocs.assembly/documenttable) instance represents a single table.

To access data of the corresponding table while assembling a document, pass an instance of this class as a data source to one of [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). assembleDocument overloads.

In template documents, a [DocumentTable](../../com.groupdocs.assembly/documenttable) instance should be treated in the same way as if it was a [DataTable](../../com.groupdocs.assembly.system.data/datatable) instance. See template syntax reference for more information.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentTable(String documentPath, int indexInDocument)](#DocumentTable-java.lang.String-int-) | Creates a new instance of this class using default [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions). |
| [DocumentTable(String documentPath, int indexInDocument, DocumentTableOptions options)](#DocumentTable-java.lang.String-int-com.groupdocs.assembly.DocumentTableOptions-) | Creates a new instance of this class. |
| [DocumentTable(InputStream documentStream, int indexInDocument)](#DocumentTable-java.io.InputStream-int-) | Creates a new instance of this class using default [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions). |
| [DocumentTable(InputStream documentStream, int indexInDocument, DocumentTableOptions options)](#DocumentTable-java.io.InputStream-int-com.groupdocs.assembly.DocumentTableOptions-) | Creates a new instance of this class. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the name of this table used to access the table's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). |
| [setName(String value)](#setName-java.lang.String-) | Sets the name of this table used to access the table's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). |
| [getIndexInDocument()](#getIndexInDocument--) | Gets the original zero-based index of the corresponding table as per the source document. |
| [getColumns()](#getColumns--) | Gets the collection of [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) objects representing columns of the corresponding table. |
### DocumentTable(String documentPath, int indexInDocument) {#DocumentTable-java.lang.String-int-}
```
public DocumentTable(String documentPath, int indexInDocument)
```


Creates a new instance of this class using default [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentPath | java.lang.String | The path to a document containing the table to be accessed. |
| indexInDocument | int | The zero-based index of the table in the document. |

### DocumentTable(String documentPath, int indexInDocument, DocumentTableOptions options) {#DocumentTable-java.lang.String-int-com.groupdocs.assembly.DocumentTableOptions-}
```
public DocumentTable(String documentPath, int indexInDocument, DocumentTableOptions options)
```


Creates a new instance of this class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentPath | java.lang.String | The path to a document containing the table to be accessed. |
| indexInDocument | int | The zero-based index of the table in the document. |
| options | [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions) | A set of options controlling extraction of data from the table. If null, default options are applied. |

### DocumentTable(InputStream documentStream, int indexInDocument) {#DocumentTable-java.io.InputStream-int-}
```
public DocumentTable(InputStream documentStream, int indexInDocument)
```


Creates a new instance of this class using default [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStream | java.io.InputStream | The stream containing a document with the table to be accessed. |
| indexInDocument | int | The zero-based index of the table in the document. |

### DocumentTable(InputStream documentStream, int indexInDocument, DocumentTableOptions options) {#DocumentTable-java.io.InputStream-int-com.groupdocs.assembly.DocumentTableOptions-}
```
public DocumentTable(InputStream documentStream, int indexInDocument, DocumentTableOptions options)
```


Creates a new instance of this class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStream | java.io.InputStream | The stream containing a document with the table to be accessed. |
| indexInDocument | int | The zero-based index of the table in the document. |
| options | [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions) | A set of options controlling extraction of data from the table. If null, default options are applied. |

### getName() {#getName--}
```
public String getName()
```


Gets the name of this table used to access the table's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler).

If the table's name is read from a document, the name is automatically corrected so that it to be valid. However, if the table's name is set manually through this property and the name is invalid, an exception is thrown.

The table's name is considered to be valid, if the following conditions are met:

 *  The name is not empty.
 *  The name's first character is a letter or underscore.
 *  The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '.', '$'.
 *  The corresponding [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) object does not contain a [DocumentTable](../../com.groupdocs.assembly/documenttable) instance with the same name.

**Returns:**
java.lang.String - The name of this table used to access the table's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler).
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets the name of this table used to access the table's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler).

If the table's name is read from a document, the name is automatically corrected so that it to be valid. However, if the table's name is set manually through this property and the name is invalid, an exception is thrown.

The table's name is considered to be valid, if the following conditions are met:

 *  The name is not empty.
 *  The name's first character is a letter or underscore.
 *  The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '.', '$'.
 *  The corresponding [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) object does not contain a [DocumentTable](../../com.groupdocs.assembly/documenttable) instance with the same name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of this table used to access the table's data in a template document passed to [DocumentAssembler](../../com.groupdocs.assembly/documentassembler). |

### getIndexInDocument() {#getIndexInDocument--}
```
public int getIndexInDocument()
```


Gets the original zero-based index of the corresponding table as per the source document. Depending on an [IDocumentTableLoadHandler](../../com.groupdocs.assembly/idocumenttableloadhandler) implementation provided, this index may differ from the index of this [DocumentTable](../../com.groupdocs.assembly/documenttable) instance within the table collection of the corresponding [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) instance, if any.

**Returns:**
int - The original zero-based index of the corresponding table as per the source document.
### getColumns() {#getColumns--}
```
public DocumentTableColumnCollection getColumns()
```


Gets the collection of [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) objects representing columns of the corresponding table.

**Returns:**
[DocumentTableColumnCollection](../../com.groupdocs.assembly/documenttablecolumncollection) - The collection of [DocumentTableColumn](../../com.groupdocs.assembly/documenttablecolumn) objects representing columns of the corresponding table.
