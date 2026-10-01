---
title: "JsonDataSource"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Fornisce l'accesso ai dati di un file JSON o di uno stream da utilizzare durante l'assemblaggio di un documento."
type: docs
weight: 230
url: /it/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

Fornisce l'accesso ai dati di un file JSON o di uno stream da utilizzare durante l'assemblaggio di un documento.

```csharp
public class JsonDataSource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | Crea una nuova origine dati con i dati provenienti da uno stream JSON utilizzando le opzioni predefinite per l'analisi dei dati JSON. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | Crea una nuova origine dati con i dati provenienti da un file JSON utilizzando le opzioni predefinite per l'analisi dei dati JSON. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | Crea una nuova origine dati con i dati provenienti da uno stream JSON utilizzando le opzioni specificate per l'analisi dei dati JSON. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | Crea una nuova origine dati con i dati provenienti da un file JSON utilizzando le opzioni specificate per l'analisi dei dati JSON. |

### Osservazioni

Per accedere ai dati del file o stream corrispondente durante l'assemblaggio di un documento, passa un'istanza di questa classe come origine dati a una delle overload di [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Nei documenti modello, se un elemento JSON di livello superiore è un array, un'istanza di [`JsonDataSource`](../jsondatasource) deve essere trattata allo stesso modo di un'istanza di DataTable. Se un elemento JSON di livello superiore è un oggetto, un'istanza di [`JsonDataSource`](../jsondatasource) deve essere trattata allo stesso modo di un'istanza di DataRow. Per ulteriori informazioni, consultare il riferimento sulla sintassi dei modelli (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Nei documenti modello, è possibile lavorare con valori tipizzati degli elementi JSON. Per comodità, il motore sostituisce l'insieme dei tipi semplici JSON con il seguente:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Il motore riconosce automaticamente i valori dei tipi aggiuntivi in base alle loro rappresentazioni JSON.

Per sovrascrivere il comportamento predefinito del caricamento dei dati JSON, inizializza e passa un'istanza di [`JsonDataLoadOptions`](../jsondataloadoptions) al costruttore di questa classe.

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
