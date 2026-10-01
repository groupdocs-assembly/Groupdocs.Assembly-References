---
title: "ResourceLoadBaseUri"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta un URI di base per risolvere i file di risorse esterne, convertendo gli URI relativi in URI assoluti durante il caricamento di un documento modello HTML da assemblare e salvare in un formato non HTML. Il valore predefinito è una stringa vuota."
type: docs
weight: 20
url: /it/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

Ottiene o imposta un URI di base per risolvere gli URI relativi dei file di risorse esterne in URI assoluti durante il caricamento di un documento modello HTML da assemblare e salvare in un formato non HTML. Il valore predefinito è una stringa vuota.

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### Osservazioni

Durante il caricamento di un documento HTML da un file, la cartella contenente il file viene utilizzata come URI di base per impostazione predefinita, cosa che non può avvenire durante il caricamento di un documento HTML da uno stream. Imposta questa proprietà per specificare un URI di base quando si carica un documento HTML da uno stream o per sovrascrivere l'URI di base predefinito quando si carica un documento HTML da un file.

Un valore di questa proprietà viene ignorato nei seguenti casi:

* An HTML document being loaded contains a BASE HTML element providing a base URI.
* An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

### Vedi anche

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
