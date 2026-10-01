---
title: "ResourceSaveFolder"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta un percorso a una cartella per memorizzare i file di risorse esterne mentre un documento assemblato caricato da un formato non HTML viene salvato in HTML. Il valore predefinito è una stringa vuota."
type: docs
weight: 30
url: /it/net/groupdocs.assembly/loadsaveoptions/resourcesavefolder/
---
## LoadSaveOptions.ResourceSaveFolder property

Ottiene o imposta un percorso a una cartella per memorizzare i file di risorse esterne mentre un documento assemblato caricato da un formato non HTML viene salvato in HTML. Il valore predefinito è una stringa vuota.

```csharp
public string ResourceSaveFolder { get; set; }
```

### Osservazioni

Per impostazione predefinita, quando si salva un documento assemblato in un file HTML, i file di risorse esterne vengono archiviati in una cartella che ha lo stesso nome del file HTML senza estensione, più il suffisso "_files". Questa cartella si trova nella stessa cartella del file HTML. Tuttavia, ciò non è possibile quando si salva un documento assemblato in un flusso HTML. Impostare questa proprietà per specificare un percorso a una cartella per memorizzare i file di risorse esterne quando si salva un documento assemblato in un flusso HTML o per sovrascrivere la cartella predefinita quando si salva un documento assemblato in un file HTML.

Un valore di questa proprietà viene ignorato se un documento assemblato salvato in HTML è stato caricato anche da HTML (i file di risorse esterne non vengono memorizzati e i collegamenti a essi non vengono modificati).

### Vedi anche

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
