---
title: "Nome"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta il nome di questa colonna utilizzato per accedere ai dati delle colonne in un documento modello passato a DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 30
url: /it/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

Ottiene o imposta il nome di questa colonna utilizzato per accedere ai dati della colonna in un documento modello passato a [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### Osservazioni

Se il nome della colonna viene letto da un documento (vedi [`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames)), il nome viene corretto automaticamente affinché sia valido. Tuttavia, se il nome della colonna viene impostato manualmente tramite questa proprietà e il nome non è valido, viene sollevata un'eccezione.

Il nome della colonna è considerato valido se sono soddisfatte le seguenti condizioni:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTable`](../../documenttable) object does not contain a [`DocumentTableColumn`](../../documenttablecolumn) instance with the same name.

### Vedi anche

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
