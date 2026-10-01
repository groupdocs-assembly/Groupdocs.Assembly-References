---
title: "ExactDateTimeParseFormats"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta formati esatti per l'analisi dei valori datetime JSON durante il caricamento di JSON. Il valore predefinito è null."
type: docs
weight: 30
url: /it/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

Ottiene o imposta formati esatti per l'analisi dei valori data-ora JSON durante il caricamento di JSON. Il valore predefinito è **null**.

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### Osservazioni

Le stringhe codificate usando il formato data-ora JSON di Microsoft® (ad esempio, "/Date(1224043200000)/") sono sempre riconosciute come valori data-ora indipendentemente dal valore di questa proprietà. La proprietà definisce formati aggiuntivi da utilizzare durante l'analisi dei valori data-ora dalle stringhe nel modo seguente:

* When `ExactDateTimeParseFormats` is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
* When `ExactDateTimeParseFormats` contains strings, they are used as additional date-time formats utilizing the current culture.
* When `ExactDateTimeParseFormats` is empty, no additional date-time formats are used.

### Vedi anche

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* namespace [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
