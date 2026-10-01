---
title: "JsonDataLoadOptions"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Stellt Optionen für das Parsen von JSON-Daten dar."
type: docs
weight: 220
url: /de/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

Stellt Optionen für das Parsen von JSON-Daten dar.

```csharp
public class JsonDataLoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | Initialisiert eine neue Instanz dieser Klasse mit Standardoptionen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | Liest oder setzt ein Flag, das angibt, ob eine erzeugte Datenquelle immer ein Objekt für ein JSON‑Stammelement enthält. Wenn ein JSON‑Stammelement eine einzelne komplexe Eigenschaft enthält, wird ein solches Objekt standardmäßig nicht erstellt. |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | Liest oder setzt genaue Formate zum Parsen von JSON-Datums‑ und Zeitwerten beim Laden von JSON. Der Standardwert ist **null**. |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | Liest oder setzt einen Modus zum Parsen einfacher JSON‑Werte (null, boolean, number, integer und string) beim Laden von JSON. Ein solcher Modus beeinflusst das Parsen von Datums‑ und Zeitwerten nicht. Der Standardwert ist Loose. |

### Hinweise

Eine Instanz dieser Klasse kann an die Konstruktoren von [`JsonDataSource`](../jsondatasource) übergeben werden.

### Siehe auch

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
