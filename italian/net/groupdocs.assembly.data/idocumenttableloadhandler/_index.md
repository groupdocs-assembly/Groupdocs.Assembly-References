---
title: "IDocumentTableLoadHandler"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Sovrascrive il caricamento predefinito degli oggetti DocumentTable./documenttable durante la creazione di un'istanza DocumentTableSet./documenttableset."
type: docs
weight: 210
url: /it/net/groupdocs.assembly.data/idocumenttableloadhandler/
---
## IDocumentTableLoadHandler interface

Sovrascrive il caricamento predefinito degli oggetti [`DocumentTable`](../documenttable) durante la creazione di un'istanza [`DocumentTableSet`](../documenttableset).

```csharp
public interface IDocumentTableLoadHandler
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Handle](../../groupdocs.assembly.data/idocumenttableloadhandler/handle)(DocumentTableLoadArgs) | Sovrascrive il caricamento predefinito di un particolare oggetto [`DocumentTable`](../documenttable) durante la creazione di un'istanza [`DocumentTableSet`](../documenttableset). |

### Osservazioni

Implementa questa interfaccia se desideri scartare il caricamento di specifici oggetti [`DocumentTable`](../documenttable) o fornire specifici [`DocumentTableOptions`](../documenttableoptions) per le tabelle del documento da caricare.

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
