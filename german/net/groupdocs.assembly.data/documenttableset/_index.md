---
title: "DocumentTableSet"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt Zugriff auf Daten mehrerer Tabellen oder Tabellenkalkulationen bereit, die sich in einem externen Dokument befinden und beim Zusammenstellen eines Dokuments verwendet werden sollen. Ermöglicht außerdem die Definition von Eltern‑Kind‑Beziehungen für die Dokumenttabellen, wodurch der Zugriff auf verwandte Daten innerhalb von Vorlagendokumenten vereinfacht wird."
type: docs
weight: 200
url: /de/net/groupdocs.assembly.data/documenttableset/
---
## DocumentTableSet class

Stellt Zugriff auf Daten mehrerer Tabellen (oder Tabellenkalkulationen) in einem externen Dokument bereit, die beim Zusammenstellen eines Dokuments verwendet werden. Außerdem ermöglicht es, Eltern‑Kind-Beziehungen für die Dokumenttabellen zu definieren, wodurch der Zugriff auf verwandte Daten innerhalb von Vorlagendokumenten vereinfacht wird.

```csharp
public class DocumentTableSet
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DocumentTableSet](documenttableset#constructor)(Stream) | Erstellt eine neue Instanz dieser Klasse und lädt alle Tabellen aus einem Dokument mithilfe der Standard‑[`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTableSet](documenttableset#constructor_2)(string) | Erstellt eine neue Instanz dieser Klasse und lädt alle Tabellen aus einem Dokument mithilfe der Standard‑[`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTableSet](documenttableset#constructor_1)(Stream, IDocumentTableLoadHandler) | Erstellt eine neue Instanz dieser Klasse. |
| [DocumentTableSet](documenttableset#constructor_3)(string, IDocumentTableLoadHandler) | Erstellt eine neue Instanz dieser Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Relations](../../groupdocs.assembly.data/documenttableset/relations) { get; } | Ruft die Sammlung von Eltern‑Kind‑Beziehungen ab, die für die Dokumenttabellen dieses Satzes definiert sind. |
| [Tables](../../groupdocs.assembly.data/documenttableset/tables) { get; } | Ruft die Sammlung von [`DocumentTable`](../documenttable)-Objekten ab, die die Tabellen dieses Satzes darstellen. |

### Hinweise

Für Dokumente im Spreadsheet‑Dateiformat stellt eine [`DocumentTableSet`](../documenttableset)-Instanz eine Menge von Arbeitsblättern dar. Für Dokumente anderer Dateiformate stellt eine [`DocumentTableSet`](../documenttableset)-Instanz eine Menge von Tabellen dar.

Um während des Zusammenstellens eines Dokuments auf die Daten der entsprechenden Tabellen zuzugreifen, übergeben Sie eine Instanz dieser Klasse als Datenquelle an eine der Überladungen von [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

In Vorlagendokumenten sollte eine [`DocumentTableSet`](../documenttableset)-Instanz genauso behandelt werden, als wäre sie eine DataSet‑Instanz. Weitere Informationen finden Sie in der Referenz zur Vorlagensyntax.

### Siehe auch

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
