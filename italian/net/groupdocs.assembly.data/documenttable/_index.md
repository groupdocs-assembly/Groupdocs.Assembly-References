---
title: DocumentTable
second_title: Riferimento API GroupDocs.Assembly per .NET
description: Fornisce laccesso ai dati di una singola tabella o foglio di calcolo che si trova in un documento esterno da utilizzare durante assemblando un documento.
type: docs
weight: 40
url: /it/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

Fornisce l'accesso ai dati di una singola tabella (o foglio di calcolo) che si trova in un documento esterno da utilizzare durante assemblando un documento.

```csharp
public class DocumentTable
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | Crea una nuova istanza di questa classe utilizzando default[`DocumentTableOptions`](../documenttableoptions) . |
| [DocumentTable](documenttable#constructor_2)(string, int) | Crea una nuova istanza di questa classe utilizzando default[`DocumentTableOptions`](../documenttableoptions) . |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | Crea una nuova istanza di questa classe. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | Crea una nuova istanza di questa classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | Ottiene la raccolta di[`DocumentTableColumn`](../documenttablecolumn) oggetti che rappresentano colonne di la tabella corrispondente. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | Ottiene l'indice in base zero originale della tabella corrispondente come da documento di origine. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | Ottiene o imposta il nome di questa tabella utilizzata per accedere ai dati della tabella in un documento modello passato a [`DocumentAssembler`](../../groupdocs.assembly/documentassembler) . |

### Osservazioni

Per i documenti dei formati di file Spreadsheet, a[`DocumentTable`](../documenttable)l'istanza rappresenta un singolo foglio. Per documenti di altri formati di file, a[`DocumentTable`](../documenttable) l'istanza rappresenta una singola tabella.

Per accedere ai dati della tabella corrispondente durante l'assemblaggio di un documento, passa un'istanza di questa classe come un'origine dati a uno dei[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .AssembleDocument sovraccarichi.

Nei documenti modello, a[`DocumentTable`](../documenttable) instance dovrebbe essere trattato come se fosse aDataTable esempio. Per ulteriori informazioni, vedere il riferimento alla sintassi del modello.

### Guarda anche

* spazio dei nomi [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assemblea [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->