---
title: "Nome"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta il nome di questa tabella usato per accedere ai dati della tabella in un documento modello passato a DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 40
url: /it/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

Ottiene o imposta il nome di questa tabella usato per accedere ai dati della tabella in un documento modello passato a [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### Osservazioni

Se il nome della tabella viene letto da un documento, il nome viene corretto automaticamente in modo che sia valido. Tuttavia, se il nome della tabella viene impostato manualmente tramite questa proprietà e il nome non è valido, viene generata un\'eccezione.

Il nome della tabella è considerato valido se sono soddisfatte le seguenti condizioni:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTableSet`](../../documenttableset) object does not contain a [`DocumentTable`](../../documenttable) instance with the same name.

### Vedi anche

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
