---
title: "XmlDataSource"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Fornisce l'accesso ai dati di un file XML o di uno stream da utilizzare durante l'assemblaggio di un documento."
type: docs
weight: 260
url: /it/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

Fornisce l'accesso ai dati di un file XML o di uno stream da utilizzare durante l'assemblaggio di un documento.

```csharp
public class XmlDataSource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | Crea una nuova origine dati con i dati da un flusso XML utilizzando le opzioni predefinite per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_4)(string) | Crea una nuova origine dati con i dati da un file XML utilizzando le opzioni predefinite per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | Crea una nuova origine dati con i dati da un flusso XML utilizzando un flusso di definizione XML Schema. Vengono utilizzate le opzioni predefinite per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | Crea una nuova origine dati con i dati provenienti da un flusso XML utilizzando le opzioni specificate per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | Crea una nuova origine dati con i dati provenienti da un file XML utilizzando un file di definizione dello schema XML. Vengono utilizzate le opzioni predefinite per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | Crea una nuova origine dati con i dati provenienti da un file XML utilizzando le opzioni specificate per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | Crea una nuova origine dati con i dati provenienti da un flusso XML utilizzando un flusso di definizione dello schema XML. Vengono utilizzate le opzioni specificate per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | Crea una nuova origine dati con i dati provenienti da un file XML utilizzando un file di definizione dello schema XML. Vengono utilizzate le opzioni specificate per il caricamento dei dati XML. |

### Osservazioni

Per accedere ai dati del file o stream corrispondente durante l'assemblaggio di un documento, passa un'istanza di questa classe come origine dati a una delle overload di [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Nei documenti modello, se un elemento XML di livello superiore contiene solo un elenco di elementi dello stesso tipo, un'istanza di [`XmlDataSource`](../xmldatasource) dovrebbe essere trattata allo stesso modo di un'istanza DataTable. In caso contrario, un'istanza di [`XmlDataSource`](../xmldatasource) dovrebbe essere trattata allo stesso modo di un'istanza DataRow. Per ulteriori informazioni, vedere il riferimento alla sintassi del modello (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Quando la definizione dello schema XML viene passata al costruttore di questa classe, i tipi di dati dei valori dei semplici elementi XML e degli attributi vengono determinati in base allo schema. Pertanto, nei documenti modello, è possibile lavorare con valori tipizzati anziché solo con stringhe.

Quando la definizione dello schema XML non viene passata al costruttore di questa classe, i tipi di dati dei valori dei semplici elementi XML e degli attributi vengono determinati automaticamente in base alle loro rappresentazioni stringa. Pertanto, nei documenti modello, è possibile lavorare con valori tipizzati anche in questo caso. Il motore è in grado di riconoscere automaticamente i valori dei seguenti tipi:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Nota che, per far funzionare il riconoscimento automatico dei tipi di dati, le rappresentazioni stringa dei valori dei semplici elementi XML e degli attributi devono essere formate utilizzando impostazioni culturali invarianti.

Per sovrascrivere il comportamento predefinito del caricamento dei dati XML, inizializza e passa un'istanza di [`XmlDataLoadOptions`](../xmldataloadoptions) al costruttore di questa classe.

### Vedi anche

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
