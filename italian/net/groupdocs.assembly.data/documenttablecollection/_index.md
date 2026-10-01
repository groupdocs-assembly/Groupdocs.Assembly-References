---
title: "DocumentTableCollection"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Rappresenta una collezione di sola lettura di oggetti DocumentTable./documenttable di una particolare istanza di DocumentTableSet./documenttableset."
type: docs
weight: 130
url: /it/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

Rappresenta una collezione di sola lettura di oggetti [`DocumentTable`](../documenttable) di una particolare istanza di [`DocumentTableSet`](../documenttableset).

```csharp
public class DocumentTableCollection : IEnumerable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | Ottiene il numero totale di oggetti [`DocumentTable`](../documenttable) nella collezione. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | Ottiene un'istanza di [`DocumentTable`](../documenttable) dalla collezione all'indice specificato. (2 indicizzatori) |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | Restituisce un valore che indica se questa collezione contiene la tabella specificata. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | Restituisce un valore che indica se questa collezione contiene una tabella con il nome specificato. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | Restituisce un enumeratore per iterare gli oggetti [`DocumentTable`](../documenttable) di questa collezione. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | Restituisce l'indice della tabella specificata all'interno di questa collezione. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | Restituisce l'indice di una tabella con il nome specificato all'interno di questa collezione. |

### Osservazioni

La collezione viene riempita automaticamente durante il caricamento delle tabelle corrispondenti da un documento e non può essere modificata. Tuttavia, le proprietà degli oggetti [`DocumentTable`](../documenttable) contenuti nella collezione possono essere modificate.

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
