---
title: "JsonSimpleValueParseMode"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Specifica una modalità per l'analisi dei valori semplici JSON null boolean number integer e string durante il caricamento di JSON. Tale modalità non influisce sull'analisi dei valori datetime."
type: docs
weight: 240
url: /it/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

Specifica una modalità per l'analisi dei valori semplici JSON (null, booleano, numero, intero e stringa) durante il caricamento di JSON. Tale modalità non influisce sull'analisi dei valori data-ora.

```csharp
public enum JsonSimpleValueParseMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Loose | `0` | Specifica la modalità in cui i tipi dei valori semplici JSON vengono determinati durante l'analisi delle loro rappresentazioni stringa. Ad esempio, il tipo di 'prop' nello snippet JSON '{ prop: \"123\" }' viene determinato come integer in questa modalità. |
| Strict | `1` | Specifica la modalità in cui i tipi dei valori semplici JSON vengono determinati dalla notazione JSON stessa. Ad esempio, il tipo di 'prop' nello snippet JSON '{ prop: \"123\" }' viene determinato come string in questa modalità. |

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
