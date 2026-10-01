---
title: "DocumentAssembler"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Fornisce routine per popolare i documenti modello con dati e un insieme di impostazioni per controllare queste routine."
type: docs
weight: 40
url: /it/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

Fornisce routine per popolare i documenti modello con dati e un insieme di impostazioni per controllare queste routine.

```csharp
public class DocumentAssembler
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocumentAssembler](documentassembler)() | Inizializza una nuova istanza di questa classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | Ottiene un insieme di impostazioni che controllano la generazione di codici a barre durante l'assemblaggio di un documento. |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | Ottiene un insieme non ordinato (cioè una collezione di elementi unici) contenente oggetti Type i cui nomi completamente o parzialmente qualificati possono essere utilizzati nei modelli di documento elaborati da questa istanza dell'assembler per invocare i membri statici dei tipi corrispondenti, eseguire cast di tipo, ecc. |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | Ottiene o imposta un insieme di flag che controllano il comportamento di questa istanza di [`DocumentAssembler`](../documentassembler) durante l'assemblaggio di un documento. |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | Ottiene o imposta un valore che indica se le invocazioni dei membri di tipo personalizzato eseguite tramite l'API di riflessione sono ottimizzate mediante generazione dinamica di classi o meno. Il valore predefinito è true. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | Carica un documento modello dallo stream di origine specificato, popola il documento modello con i dati provenienti dalla singola o dalle più fonti specificate, e salva il documento risultante nello stream di destinazione utilizzando le [`LoadSaveOptions`](../loadsaveoptions) predefinite. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | Carica un documento modello dal percorso di origine specificato, popola il documento modello con i dati provenienti dalla singola o dalle più fonti specificate, e salva il documento risultante nel percorso di destinazione utilizzando le [`LoadSaveOptions`](../loadsaveoptions) predefinite. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | Carica un documento modello dallo stream di origine specificato, popola il documento modello con i dati provenienti dalla singola o dalle più fonti specificate, e salva il documento risultante nello stream di destinazione utilizzando le [`LoadSaveOptions`](../loadsaveoptions) fornite. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | Carica un documento modello dal percorso di origine specificato, popola il documento modello con i dati provenienti dalla singola o dalle più fonti specificate, e salva il documento risultante nel percorso di destinazione utilizzando le [`LoadSaveOptions`](../loadsaveoptions) fornite. |

### Vedi anche

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
