---
title: "DocumentTable"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt Zugriff auf die Daten einer einzelnen Tabelle oder eines Tabellenblatts in einem externen Dokument bereit, das beim Zusammenstellen eines Dokuments verwendet wird."
type: docs
weight: 120
url: /de/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

Stellt Zugriff auf Daten einer einzelnen Tabelle (oder Tabellenkalkulation) in einem externen Dokument bereit, die beim Zusammenstellen eines Dokuments verwendet werden.

```csharp
public class DocumentTable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | Erstellt eine neue Instanz dieser Klasse unter Verwendung der Standard-[`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTable](documenttable#constructor_2)(string, int) | Erstellt eine neue Instanz dieser Klasse unter Verwendung der Standard-[`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | Erstellt eine neue Instanz dieser Klasse. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | Erstellt eine neue Instanz dieser Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | Ruft die Sammlung von [`DocumentTableColumn`](../documenttablecolumn)-Objekten ab, die die Spalten der entsprechenden Tabelle darstellen. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | Ruft den ursprünglichen nullbasierten Index der entsprechenden Tabelle gemäß dem Quelldokument ab. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | Ruft den Namen dieser Tabelle ab oder legt ihn fest, der verwendet wird, um auf die Tabellendaten in einem Vorlagendokument zuzugreifen, das an [`DocumentAssembler`](../../groupdocs.assembly/documentassembler) übergeben wird. |

### Hinweise

Für Dokumente im Spreadsheet-Dateiformat stellt eine [`DocumentTable`](../documenttable)-Instanz ein einzelnes Blatt dar. Für Dokumente anderer Dateiformate stellt eine [`DocumentTable`](../documenttable)-Instanz eine einzelne Tabelle dar.

Um während des Zusammenstellens eines Dokuments auf die Daten der entsprechenden Tabelle zuzugreifen, übergeben Sie eine Instanz dieser Klasse als Datenquelle an eine der Überladungen von [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

In Vorlagendokumenten sollte eine [`DocumentTable`](../documenttable)-Instanz so behandelt werden, als wäre sie eine DataTable-Instanz. Weitere Informationen finden Sie in der Referenz zur Vorlagensyntax.

### Siehe auch

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
