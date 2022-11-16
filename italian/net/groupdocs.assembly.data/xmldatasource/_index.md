---
title: XmlDataSource
second_title: Riferimento API GroupDocs.Assembly per .NET
description: Fornisce laccesso ai dati di un file o flusso XML da utilizzare durante lassemblaggio di un documento.
type: docs
weight: 180
url: /it/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

Fornisce l'accesso ai dati di un file o flusso XML da utilizzare durante l'assemblaggio di un documento.

```csharp
public class XmlDataSource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | Crea una nuova origine dati con dati da un flusso XML utilizzando le opzioni predefinite per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_4)(string) | Crea una nuova origine dati con dati da un file XML utilizzando le opzioni predefinite per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | Crea una nuova origine dati con i dati da un flusso XML utilizzando un flusso XML Schema Definition. Le opzioni predefinite vengono utilizzate per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | Crea una nuova origine dati con i dati da un flusso XML utilizzando le opzioni specificate per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | Crea una nuova origine dati con i dati di un file XML utilizzando un file XML Schema Definition. Le opzioni predefinite vengono utilizzate per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | Crea una nuova origine dati con i dati di un file XML utilizzando le opzioni specificate per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | Crea una nuova origine dati con i dati di un flusso XML utilizzando un flusso XML Schema Definition. Le opzioni specificate vengono utilizzate per il caricamento dei dati XML. |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | Crea una nuova origine dati con dati da un file XML utilizzando un file XML Schema Definition. Le opzioni specificate vengono utilizzate per il caricamento dei dati XML. |

### Osservazioni

Per accedere ai dati del file o del flusso corrispondente durante l'assemblaggio di un documento, passa un'istanza di questa classe come un'origine dati a uno dei[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .AssembleDocument sovraccarica.

Nei documenti modello, se un elemento XML di primo livello contiene solo un elenco di elementi dello stesso tipo, an[`XmlDataSource`](../xmldatasource) instance dovrebbe essere trattato come se fosse aDataTable esempio. In caso contrario, un[`XmlDataSource`](../xmldatasource) l'istanza dovrebbe essere trattata come se fosse aDataRowesempio. Per ulteriori informazioni, vedere il riferimento alla sintassi del modello (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Quando la definizione dello schema XML viene passata a un costruttore di questa classe, i tipi di dati dei valori degli elementi e degli attributi XML semplici vengono determinati in base allo schema. Pertanto, nei documenti modello, puoi lavorare con valori digitati anziché solo stringhe.

Quando XML Schema Definition non viene passato a un costruttore di questa classe, i tipi di dati dei valori di semplici elementi XML e gli attributi vengono determinati automaticamente in base alle loro rappresentazioni di stringa. Quindi, nei documenti modello, puoi lavorare anche in questo caso con valori tipizzati. Il motore è in grado di riconoscere automaticamente valori dei seguenti tipi:

* Nullable
* Nullable
* Nullable
* Nullable
* String

Si noti che affinché il riconoscimento automatico dei tipi di dati funzioni, le rappresentazioni di stringa dei valori di elementi e attributi XML semplici devono essere formate utilizzando impostazioni di cultura invarianti.

Per sovrascrivere il comportamento predefinito del caricamento dei dati XML, inizializzare e passare a[`XmlDataLoadOptions`](../xmldataloadoptions) istanza a un costruttore di questa classe.

### Guarda anche

* spazio dei nomi [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assemblea [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->