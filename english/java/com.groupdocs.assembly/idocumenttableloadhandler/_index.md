---
title: IDocumentTableLoadHandler
second_title: GroupDocs.Assembly for Java API Reference
description: Overrides default loading of  objects while creating a  instance.
type: docs
weight: 35
url: /java/com.groupdocs.assembly/idocumenttableloadhandler/
---```
public interface IDocumentTableLoadHandler
```

Overrides default loading of [DocumentTable](../../com.groupdocs.assembly/documenttable) objects while creating a [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) instance. Implement this interface if you want to discard loading of specific [DocumentTable](../../com.groupdocs.assembly/documenttable) objects or provide specific [DocumentTableOptions](../../com.groupdocs.assembly/documenttableoptions) for document tables being loaded.
## Methods

| Method | Description |
| --- | --- |
| [handle(DocumentTableLoadArgs args)](#handle-com.groupdocs.assembly.DocumentTableLoadArgs-) | Overrides default loading of a particular [DocumentTable](../../com.groupdocs.assembly/documenttable) object while creating a [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) instance. |
### handle(DocumentTableLoadArgs args) {#handle-com.groupdocs.assembly.DocumentTableLoadArgs-}
```
public abstract void handle(DocumentTableLoadArgs args)
```


Overrides default loading of a particular [DocumentTable](../../com.groupdocs.assembly/documenttable) object while creating a [DocumentTableSet](../../com.groupdocs.assembly/documenttableset) instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [DocumentTableLoadArgs](../../com.groupdocs.assembly/documenttableloadargs) |  |

