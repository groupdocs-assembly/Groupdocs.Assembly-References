---
title: "DocumentTableSet"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Fornisce l'accesso ai dati di più tabelle o fogli di calcolo situati in un documento esterno da utilizzare durante l'assemblaggio di un documento. Consente inoltre di definire relazioni padre‑figlio per le tabelle del documento, semplificando così l'accesso ai dati correlati nei documenti modello."
type: docs
weight: 200
url: /it/net/groupdocs.assembly.data/documenttableset/
---
## DocumentTableSet class

Fornisce l'accesso ai dati di più tabelle (o fogli di calcolo) situate in un documento esterno da utilizzare durante l'assemblaggio di un documento. Inoltre, consente di definire relazioni padre-figlio per le tabelle di documento semplificando così l'accesso ai dati correlati all'interno dei documenti modello.

```csharp
public class DocumentTableSet
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocumentTableSet](documenttableset#constructor)(Stream) | Crea una nuova istanza di questa classe caricando tutte le tabelle da un documento utilizzando le [`DocumentTableOptions`](../documenttableoptions) predefinite. |
| [DocumentTableSet](documenttableset#constructor_2)(string) | Crea una nuova istanza di questa classe caricando tutte le tabelle da un documento utilizzando le [`DocumentTableOptions`](../documenttableoptions) predefinite. |
| [DocumentTableSet](documenttableset#constructor_1)(Stream, IDocumentTableLoadHandler) | Crea una nuova istanza di questa classe. |
| [DocumentTableSet](documenttableset#constructor_3)(string, IDocumentTableLoadHandler) | Crea una nuova istanza di questa classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Relations](../../groupdocs.assembly.data/documenttableset/relations) { get; } | Restituisce la raccolta delle relazioni padre‑figlio definite per le tabelle del documento di questo set. |
| [Tables](../../groupdocs.assembly.data/documenttableset/tables) { get; } | Restituisce la raccolta di oggetti [`DocumentTable`](../documenttable) che rappresentano le tabelle di questo set. |

### Osservazioni

Per i documenti nei formati di file Spreadsheet, un'istanza di [`DocumentTableSet`](../documenttableset) rappresenta un insieme di fogli. Per i documenti di altri formati di file, un'istanza di [`DocumentTableSet`](../documenttableset) rappresenta un insieme di tabelle.

Per accedere ai dati delle tabelle corrispondenti durante l'assemblaggio di un documento, passa un'istanza di questa classe come origine dati a una delle overload di [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Nei documenti modello, un'istanza di [`DocumentTableSet`](../documenttableset) dovrebbe essere trattata allo stesso modo di un'istanza DataSet. Vedi il riferimento alla sintassi del modello per ulteriori informazioni.

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
