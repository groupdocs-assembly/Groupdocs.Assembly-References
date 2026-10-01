---
title: "IndexInDocument"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Restituisce l'indice originale a base zero della tabella corrispondente secondo il documento di origine."
type: docs
weight: 30
url: /it/net/groupdocs.assembly.data/documenttable/indexindocument/
---
## DocumentTable.IndexInDocument property

Ottiene l'indice originale basato su zero della tabella corrispondente secondo il documento di origine.

```csharp
public int IndexInDocument { get; }
```

### Osservazioni

A seconda dell'implementazione di [`IDocumentTableLoadHandler`](../../idocumenttableloadhandler) fornita, questo indice può differire dall'indice di questa istanza [`DocumentTable`](../../documenttable) all'interno della raccolta di tabelle della corrispondente istanza [`DocumentTableSet`](../../documenttableset), se presente.

### Vedi anche

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
