---
title: IDocumentTableLoadHandler
second_title: GroupDocs.Assembly for Java API Reference
description: Overrides default loading of com.groupdocs.assembly.DocumentTable objects while creating a com.groupdocs.assembly.DocumentTableSet instance.
type: docs
weight: 35
url: /java/com.groupdocs.assembly/idocumenttableloadhandler/
---```
public interface IDocumentTableLoadHandler
```

Overrides default loading of com.groupdocs.assembly.DocumentTable objects while creating a com.groupdocs.assembly.DocumentTableSet instance. Implement this interface if you want to discard loading of specific com.groupdocs.assembly.DocumentTable objects or provide specific com.groupdocs.assembly.DocumentTableOptions for document tables being loaded.
## Methods

| Method | Description |
| --- | --- |
| [handle(DocumentTableLoadArgs args)](#handle-com.groupdocs.assembly.DocumentTableLoadArgs-) | Overrides default loading of a particular com.groupdocs.assembly.DocumentTable object while creating a com.groupdocs.assembly.DocumentTableSet instance. |
### handle(DocumentTableLoadArgs args) {#handle-com.groupdocs.assembly.DocumentTableLoadArgs-}
```
public abstract void handle(DocumentTableLoadArgs args)
```


Overrides default loading of a particular com.groupdocs.assembly.DocumentTable object while creating a com.groupdocs.assembly.DocumentTableSet instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [DocumentTableLoadArgs](../../com.groupdocs.assembly/documenttableloadargs) |  |

