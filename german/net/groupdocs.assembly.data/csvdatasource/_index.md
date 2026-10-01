---
title: "CsvDataSource"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt Zugriff auf Daten einer CSV-Datei oder eines Streams bereit, die beim Zusammenstellen eines Dokuments verwendet werden."
type: docs
weight: 110
url: /de/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

Stellt Zugriff auf Daten einer CSV-Datei oder eines Streams bereit, die beim Zusammenstellen eines Dokuments verwendet werden.

```csharp
public class CsvDataSource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | Erstellt eine neue Datenquelle mit Daten aus einem CSV‑Stream unter Verwendung der Standardoptionen zum Parsen von CSV‑Daten. |
| [CsvDataSource](csvdatasource#constructor_2)(string) | Erstellt eine neue Datenquelle mit Daten aus einer CSV‑Datei unter Verwendung der Standardoptionen zum Parsen von CSV‑Daten. |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | Erstellt eine neue Datenquelle mit Daten aus einem CSV‑Stream unter Verwendung der angegebenen Optionen zum Parsen von CSV‑Daten. |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | Erstellt eine neue Datenquelle mit Daten aus einer CSV‑Datei unter Verwendung der angegebenen Optionen zum Parsen von CSV‑Daten. |

### Hinweise

Um auf die Daten der entsprechenden Datei oder des Streams beim Zusammenstellen eines Dokuments zuzugreifen, übergeben Sie eine Instanz dieser Klasse als Datenquelle an eine der Überladungen von [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

In Vorlagendokumenten sollte eine [`CsvDataSource`](../csvdatasource)-Instanz so behandelt werden, als wäre sie eine DataTable-Instanz. Weitere Informationen finden Sie in der Referenz zur Vorlagensyntax (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Datentypen von kommagetrennten Werten werden automatisch anhand ihrer String-Darstellungen ermittelt. Daher können Sie in Vorlagendokumenten mit typisierten Werten statt nur Zeichenketten arbeiten. Die Engine ist in der Lage, Werte der folgenden Typen automatisch zu erkennen:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Beachten Sie, dass für die automatische Erkennung von Datentypen die String-Darstellungen kommagetrennter Werte mit invariantem Kulturformat erstellt werden müssen.

Um das Standardverhalten beim Laden von CSV-Daten zu überschreiben, initialisieren Sie eine [`CsvDataLoadOptions`](../csvdataloadoptions)-Instanz und übergeben Sie sie dem Konstruktor dieser Klasse.

### Siehe auch

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
