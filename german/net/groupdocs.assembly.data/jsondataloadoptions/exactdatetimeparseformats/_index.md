---
title: "ExactDateTimeParseFormats"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Liest oder setzt genaue Formate zum Parsen von JSON‑Datum‑Uhrzeit‑Werten beim Laden von JSON. Der Standard ist null."
type: docs
weight: 30
url: /de/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

Liest oder setzt genaue Formate zum Parsen von JSON-Datums‑ und Zeitwerten beim Laden von JSON. Der Standardwert ist **null**.

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### Hinweise

Zeichenketten, die mit dem Microsoft®‑JSON‑Datum‑Uhrzeit‑Format codiert sind (z. B. "/Date(1224043200000)/"), werden stets als Datum‑Uhrzeit‑Werte erkannt, unabhängig vom Wert dieser Eigenschaft. Die Eigenschaft definiert zusätzliche Formate, die beim Parsen von Datum‑Uhrzeit‑Werten aus Zeichenketten wie folgt verwendet werden:

* When `ExactDateTimeParseFormats` is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
* When `ExactDateTimeParseFormats` contains strings, they are used as additional date-time formats utilizing the current culture.
* When `ExactDateTimeParseFormats` is empty, no additional date-time formats are used.

### Siehe auch

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* namespace [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
