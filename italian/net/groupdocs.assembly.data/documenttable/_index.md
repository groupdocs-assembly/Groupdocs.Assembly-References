---
title: "DocumentTable"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Fornisce l'accesso ai dati di una singola tabella o foglio di calcolo situato in un documento esterno da utilizzare durante l'assemblaggio di un documento."
type: docs
weight: 120
url: /it/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

Fornisce l'accesso ai dati di una singola tabella (o foglio di calcolo) situata in un documento esterno da utilizzare durante l'assemblaggio di un documento.

```csharp
public class DocumentTable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | Crea una nuova istanza di questa classe utilizzando le [`DocumentTableOptions`](../documenttableoptions) predefinite. |
| [DocumentTable](documenttable#constructor_2)(string, int) | Crea una nuova istanza di questa classe utilizzando le [`DocumentTableOptions`](../documenttableoptions) predefinite. |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | Crea una nuova istanza di questa classe. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | Crea una nuova istanza di questa classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | Ottiene la collezione di oggetti [`DocumentTableColumn`](../documenttablecolumn) che rappresentano le colonne della tabella corrispondente. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | Ottiene l'indice originale basato su zero della tabella corrispondente secondo il documento di origine. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | Ottiene o imposta il nome di questa tabella utilizzato per accedere ai dati della tabella in un documento modello passato a [`DocumentAssembler`](../../groupdocs.assembly/documentassembler). |

### Osservazioni

Per i documenti nei formati di file Spreadsheet, un'istanza di [`DocumentTable`](../documenttable) rappresenta un singolo foglio. Per i documenti di altri formati di file, un'istanza di [`DocumentTable`](../documenttable) rappresenta una singola tabella.

Per accedere ai dati della tabella corrispondente durante l'assemblaggio di un documento, passa un'istanza di questa classe come origine dati a una delle overload di [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Nei documenti modello, un'istanza di [`DocumentTable`](../documenttable) dovrebbe essere trattata allo stesso modo di un'istanza DataTable. Vedi il riferimento alla sintassi del modello per ulteriori informazioni.

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
