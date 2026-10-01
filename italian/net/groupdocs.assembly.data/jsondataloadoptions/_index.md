---
title: "JsonDataLoadOptions"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Rappresenta le opzioni per l'analisi dei dati JSON."
type: docs
weight: 220
url: /it/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

Rappresenta le opzioni per l'analisi dei dati JSON.

```csharp
public class JsonDataLoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | Inizializza una nuova istanza di questa classe con le opzioni predefinite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | Ottiene o imposta un flag che indica se una data source generata conterrà sempre un oggetto per un elemento radice JSON. Se un elemento radice JSON contiene una singola proprietà complessa, tale oggetto non viene creato per impostazione predefinita. |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | Ottiene o imposta formati esatti per l'analisi dei valori data-ora JSON durante il caricamento di JSON. Il valore predefinito è **null**. |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | Ottiene o imposta una modalità per l'analisi dei valori semplici JSON (null, boolean, number, integer e string) durante il caricamento di JSON. Tale modalità non influisce sull'analisi dei valori data-ora. Il valore predefinito è Loose. |

### Osservazioni

Un'istanza di questa classe può essere passata ai costruttori di [`JsonDataSource`](../jsondatasource).

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
