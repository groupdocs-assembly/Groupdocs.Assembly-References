---
title: "JsonDataSource"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt Zugriff auf Daten einer JSON-Datei oder eines Streams bereit, die beim Zusammenstellen eines Dokuments verwendet werden."
type: docs
weight: 230
url: /de/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

Stellt Zugriff auf Daten einer JSON-Datei oder eines Streams bereit, die beim Zusammenstellen eines Dokuments verwendet werden.

```csharp
public class JsonDataSource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | Erstellt eine neue Datenquelle mit Daten aus einem JSON‑Stream unter Verwendung der Standardoptionen zum Parsen von JSON‑Daten. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | Erstellt eine neue Datenquelle mit Daten aus einer JSON‑Datei unter Verwendung der Standardoptionen zum Parsen von JSON‑Daten. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | Erstellt eine neue Datenquelle mit Daten aus einem JSON‑Stream unter Verwendung der angegebenen Optionen zum Parsen von JSON‑Daten. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | Erstellt eine neue Datenquelle mit Daten aus einer JSON‑Datei unter Verwendung der angegebenen Optionen zum Parsen von JSON‑Daten. |

### Hinweise

Um auf die Daten der entsprechenden Datei oder des Streams beim Zusammenstellen eines Dokuments zuzugreifen, übergeben Sie eine Instanz dieser Klasse als Datenquelle an eine der Überladungen von [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

In Vorlagendokumenten sollte, wenn ein JSON-Element der obersten Ebene ein Array ist, eine [`JsonDataSource`](../jsondatasource)-Instanz so behandelt werden, als wäre sie eine DataTable-Instanz. Wenn ein JSON-Element der obersten Ebene ein Objekt ist, sollte eine [`JsonDataSource`](../jsondatasource)-Instanz so behandelt werden, als wäre sie eine DataRow-Instanz. Weitere Informationen finden Sie in der Referenz zur Vorlagensyntax (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

In Vorlagendokumenten können Sie mit typisierten Werten von JSON-Elementen arbeiten. Zur Vereinfachung ersetzt die Engine die Menge der einfachen JSON-Typen durch die folgende:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Die Engine erkennt automatisch Werte der zusätzlichen Typen anhand ihrer JSON-Darstellungen.

Um das Standardverhalten beim Laden von JSON-Daten zu überschreiben, initialisieren Sie eine [`JsonDataLoadOptions`](../jsondataloadoptions)-Instanz und übergeben Sie sie dem Konstruktor dieser Klasse.

### Siehe auch

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
