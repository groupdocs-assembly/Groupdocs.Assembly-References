---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt Zugriff auf Daten einer XML-Datei oder eines Streams bereit, die beim Zusammenstellen eines Dokuments verwendet werden."
type: docs
weight: 260
url: /de/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

Stellt Zugriff auf Daten einer XML-Datei oder eines Streams bereit, die beim Zusammenstellen eines Dokuments verwendet werden.

```csharp
public class XmlDataSource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | Erstellt eine neue Datenquelle mit Daten aus einem XML‑Stream unter Verwendung der Standardoptionen für das Laden von XML‑Daten. |
| [XmlDataSource](xmldatasource#constructor_4)(string) | Erstellt eine neue Datenquelle mit Daten aus einer XML‑Datei unter Verwendung der Standardoptionen für das Laden von XML‑Daten. |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | Erstellt eine neue Datenquelle mit Daten aus einem XML‑Stream unter Verwendung eines XML‑Schema‑Definitions‑Streams. Für das Laden von XML‑Daten werden die Standardoptionen verwendet. |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | Erstellt eine neue Datenquelle mit Daten aus einem XML‑Stream unter Verwendung der angegebenen Optionen für das Laden von XML‑Daten. |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | Erstellt eine neue Datenquelle mit Daten aus einer XML‑Datei unter Verwendung einer XML‑Schema‑Definitions‑Datei. Für das Laden von XML‑Daten werden die Standardoptionen verwendet. |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | Erstellt eine neue Datenquelle mit Daten aus einer XML‑Datei unter Verwendung der angegebenen Optionen für das Laden von XML‑Daten. |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | Erstellt eine neue Datenquelle mit Daten aus einem XML‑Stream unter Verwendung eines XML‑Schema‑Definitions‑Streams. Die angegebenen Optionen werden für das Laden von XML‑Daten verwendet. |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | Erstellt eine neue Datenquelle mit Daten aus einer XML‑Datei unter Verwendung einer XML‑Schema‑Definitions‑Datei. Die angegebenen Optionen werden für das Laden von XML‑Daten verwendet. |

### Hinweise

Um auf die Daten der entsprechenden Datei oder des Streams beim Zusammenstellen eines Dokuments zuzugreifen, übergeben Sie eine Instanz dieser Klasse als Datenquelle an eine der Überladungen von [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

In Vorlagendokumenten, wenn ein XML-Element auf oberster Ebene nur eine Liste von Elementen desselben Typs enthält, sollte eine [`XmlDataSource`](../xmldatasource)-Instanz so behandelt werden, als wäre sie eine DataTable-Instanz. Andernfalls sollte eine [`XmlDataSource`](../xmldatasource)-Instanz so behandelt werden, als wäre sie eine DataRow-Instanz. Weitere Informationen finden Sie in der Referenz zur Vorlagensyntax (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Wenn ein XML Schema Definition an einen Konstruktor dieser Klasse übergeben wird, werden die Datentypen der Werte einfacher XML-Elemente und Attribute gemäß dem Schema bestimmt. So können Sie in Vorlagendokumenten mit typisierten Werten statt nur Zeichenketten arbeiten.

Wenn ein XML Schema Definition nicht an einen Konstruktor dieser Klasse übergeben wird, werden die Datentypen der Werte einfacher XML-Elemente und Attribute automatisch anhand ihrer Zeichenkettenrepräsentationen bestimmt. So können Sie in Vorlagendokumenten in diesem Fall ebenfalls mit typisierten Werten arbeiten. Die Engine ist in der Lage, Werte der folgenden Typen automatisch zu erkennen:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Beachten Sie, dass für die automatische Erkennung von Datentypen die Zeichenkettenrepräsentationen der Werte einfacher XML-Elemente und Attribute unter Verwendung von Invariant-Culture-Einstellungen erstellt werden sollten.

Um das Standardverhalten beim Laden von XML-Daten zu überschreiben, initialisieren Sie eine [`XmlDataLoadOptions`](../xmldataloadoptions)-Instanz und übergeben Sie sie an einen Konstruktor dieser Klasse.

### Siehe auch

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
