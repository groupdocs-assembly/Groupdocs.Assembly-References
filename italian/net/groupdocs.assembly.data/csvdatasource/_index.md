---
title: "CsvDataSource"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Fornisce l'accesso ai dati di un file CSV o di uno stream da utilizzare durante l'assemblaggio di un documento."
type: docs
weight: 110
url: /it/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

Fornisce l'accesso ai dati di un file CSV o di uno stream da utilizzare durante l'assemblaggio di un documento.

```csharp
public class CsvDataSource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | Crea una nuova origine dati con i dati da un flusso CSV utilizzando le opzioni predefinite per l'analisi dei dati CSV. |
| [CsvDataSource](csvdatasource#constructor_2)(string) | Crea una nuova origine dati con i dati da un file CSV utilizzando le opzioni predefinite per l'analisi dei dati CSV. |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | Crea una nuova origine dati con i dati da un flusso CSV utilizzando le opzioni specificate per l'analisi dei dati CSV. |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | Crea una nuova origine dati con i dati da un file CSV utilizzando le opzioni specificate per l'analisi dei dati CSV. |

### Osservazioni

Per accedere ai dati del file o stream corrispondente durante l'assemblaggio di un documento, passa un'istanza di questa classe come origine dati a una delle overload di [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Nei documenti modello, un'istanza di [`CsvDataSource`](../csvdatasource) dovrebbe essere trattata allo stesso modo di un'istanza DataTable. Per ulteriori informazioni, vedere il riferimento alla sintassi del modello (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

I tipi di dati dei valori separati da virgola vengono determinati automaticamente in base alle loro rappresentazioni stringa. Quindi nei documenti modello, è possibile lavorare con valori tipizzati anziché solo stringhe. Il motore è in grado di riconoscere automaticamente i valori dei seguenti tipi:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Nota che, per far funzionare il riconoscimento automatico dei tipi di dati, le rappresentazioni stringa dei valori separati da virgola devono essere formate utilizzando le impostazioni di cultura invarianti.

Per sovrascrivere il comportamento predefinito del caricamento dei dati CSV, inizializza e passa un'istanza di [`CsvDataLoadOptions`](../csvdataloadoptions) al costruttore di questa classe.

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
