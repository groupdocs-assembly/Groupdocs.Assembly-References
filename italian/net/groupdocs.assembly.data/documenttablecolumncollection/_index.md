---
title: "DocumentTableColumnCollection"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Rappresenta una collezione readonly di oggetti DocumentTableColumn./documenttablecolumn di una particolare istanza di DocumentTable./documenttable."
type: docs
weight: 150
url: /it/net/groupdocs.assembly.data/documenttablecolumncollection/
---
## DocumentTableColumnCollection class

Rappresenta una collezione read-only di oggetti [`DocumentTableColumn`](../documenttablecolumn) di una specifica istanza di [`DocumentTable`](../documenttable).

```csharp
public class DocumentTableColumnCollection : IEnumerable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecolumncollection/count) { get; } | Ottiene il numero totale di oggetti [`DocumentTableColumn`](../documenttablecolumn) nella collezione. |
| [Item](../../groupdocs.assembly.data/documenttablecolumncollection/item) { get; } | Ottiene un'istanza di [`DocumentTableColumn`](../documenttablecolumn) dalla collezione all'indice specificato. (2 indicizzatori) |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains)(DocumentTableColumn) | Restituisce un valore che indica se questa collezione contiene la colonna specificata. |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains_1)(string) | Restituisce un valore che indica se questa collezione contiene una colonna con il nome specificato. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecolumncollection/getenumerator)() | Restituisce un enumeratore per iterare gli oggetti [`DocumentTableColumn`](../documenttablecolumn) di questa collezione. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof)(DocumentTableColumn) | Restituisce l'indice della colonna specificata all'interno di questa collezione. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof_1)(string) | Restituisce l'indice di una colonna con il nome specificato all'interno di questa collezione. |

### Osservazioni

La collezione viene popolata automaticamente durante il caricamento della tabella corrispondente da un documento e non può essere modificata. Tuttavia, le proprietà degli oggetti [`DocumentTableColumn`](../documenttablecolumn) contenuti nella collezione possono essere modificate.

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
