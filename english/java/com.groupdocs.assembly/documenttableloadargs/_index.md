---
title: DocumentTableLoadArgs
second_title: GroupDocs.Assembly for Java API Reference
description: Provides data for the com.groupdocs.assembly.IDocumentTableLoadHandlerhandlecom.groupdocs.assembly.DocumentTableLoadArgs method.
type: docs
weight: 20
url: /java/com.groupdocs.assembly/documenttableloadargs/
---
**Inheritance:**
java.lang.Object
```
public class DocumentTableLoadArgs
```

Provides data for the com.groupdocs.assembly.IDocumentTableLoadHandler\#handle(com.groupdocs.assembly.DocumentTableLoadArgs) method.
## Methods

| Method | Description |
| --- | --- |
| [getTableIndex()](#getTableIndex--) | Gets the zero-based index of the corresponding document table to be loaded. |
| [isLoaded()](#isLoaded--) | Gets a value indicating whether the corresponding document table is to be loaded or not. |
| [isLoaded(boolean value)](#isLoaded-boolean-) | Sets a value indicating whether the corresponding document table is to be loaded or not. |
| [getOptions()](#getOptions--) | Gets com.groupdocs.assembly.DocumentTableOptions to be used while loading the corresponding document table. |
| [setOptions(DocumentTableOptions value)](#setOptions-com.groupdocs.assembly.DocumentTableOptions-) | Sets com.groupdocs.assembly.DocumentTableOptions to be used while loading the corresponding document table. |
### getTableIndex() {#getTableIndex--}
```
public int getTableIndex()
```


Gets the zero-based index of the corresponding document table to be loaded.

**Returns:**
int - The zero-based index of the corresponding document table to be loaded.
### isLoaded() {#isLoaded--}
```
public boolean isLoaded()
```


Gets a value indicating whether the corresponding document table is to be loaded or not. The default value is true.

**Returns:**
boolean - A value indicating whether the corresponding document table is to be loaded or not.
### isLoaded(boolean value) {#isLoaded-boolean-}
```
public void isLoaded(boolean value)
```


Sets a value indicating whether the corresponding document table is to be loaded or not. The default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | A value indicating whether the corresponding document table is to be loaded or not. |

### getOptions() {#getOptions--}
```
public DocumentTableOptions getOptions()
```


Gets com.groupdocs.assembly.DocumentTableOptions to be used while loading the corresponding document table. The default value is null, which means that default com.groupdocs.assembly.DocumentTableOptions are to be applied.

**Returns:**
[DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions) - com.groupdocs.assembly.DocumentTableOptions to be used while loading the corresponding document table.
### setOptions(DocumentTableOptions value) {#setOptions-com.groupdocs.assembly.DocumentTableOptions-}
```
public void setOptions(DocumentTableOptions value)
```


Sets com.groupdocs.assembly.DocumentTableOptions to be used while loading the corresponding document table. The default value is null, which means that default com.groupdocs.assembly.DocumentTableOptions are to be applied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions) | com.groupdocs.assembly.DocumentTableOptions to be used while loading the corresponding document table. |

