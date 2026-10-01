---
title: "LoadSaveOptions"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Specifica opzioni aggiuntive per il caricamento e il salvataggio di un documento da assemblare."
type: docs
weight: 80
url: /it/net/groupdocs.assembly/loadsaveoptions/
---
## LoadSaveOptions class

Specifica opzioni aggiuntive per il caricamento e il salvataggio di un documento da assemblare.

```csharp
public class LoadSaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LoadSaveOptions](loadsaveoptions#constructor)() | Crea una nuova istanza di questa classe senza specificare alcuna proprietà. |
| [LoadSaveOptions](loadsaveoptions#constructor_1)(FileFormat) | Crea una nuova istanza di questa classe con il formato file specificato per salvare un documento assemblato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ResourceLoadBaseUri](../../groupdocs.assembly/loadsaveoptions/resourceloadbaseuri) { get; set; } | Ottiene o imposta un URI di base per risolvere gli URI relativi dei file di risorse esterne in URI assoluti durante il caricamento di un documento modello HTML da assemblare e salvare in un formato non HTML. Il valore predefinito è una stringa vuota. |
| [ResourceSaveFolder](../../groupdocs.assembly/loadsaveoptions/resourcesavefolder) { get; set; } | Ottiene o imposta un percorso a una cartella per memorizzare i file di risorse esterne mentre un documento assemblato caricato da un formato non HTML viene salvato in HTML. Il valore predefinito è una stringa vuota. |
| [SaveFormat](../../groupdocs.assembly/loadsaveoptions/saveformat) { get; set; } | Ottiene o imposta un formato file per salvare un documento assemblato. Non specificato è il valore predefinito. |

### Vedi anche

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
