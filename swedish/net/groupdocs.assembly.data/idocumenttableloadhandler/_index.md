---
title: IDocumentTableLoadHandler
second_title: GroupDocs.Assembly för .NET API-referens
description: Åsidosätter standardladdning avDocumentTable./documenttable objekt medan du skapar enDocumentTableSet./documenttableset instans.
type: docs
weight: 130
url: /sv/net/groupdocs.assembly.data/idocumenttableloadhandler/
---
## IDocumentTableLoadHandler interface

Åsidosätter standardladdning av[`DocumentTable`](../documenttable) objekt medan du skapar en[`DocumentTableSet`](../documenttableset) instans.

```csharp
public interface IDocumentTableLoadHandler
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Handle](../../groupdocs.assembly.data/idocumenttableloadhandler/handle)(DocumentTableLoadArgs) | Åsidosätter standardladdning av en viss[`DocumentTable`](../documenttable) objekt medan du skapar a[`DocumentTableSet`](../documenttableset) instans. |

### Anmärkningar

Implementera detta gränssnitt om du vill ignorera laddning av specifika[`DocumentTable`](../documenttable) objekt eller ge specifika[`DocumentTableOptions`](../documenttableoptions) för dokumenttabeller som laddas.

### Se även

* namnutrymme [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* hopsättning [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
