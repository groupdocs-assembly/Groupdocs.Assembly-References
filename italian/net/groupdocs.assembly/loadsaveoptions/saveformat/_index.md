---
title: "SaveFormat"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta un formato file per salvare un documento assemblato. Non specificato è il valore predefinito."
type: docs
weight: 40
url: /it/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

Ottiene o imposta un formato file per salvare un documento assemblato. Non specificato è il valore predefinito.

```csharp
public FileFormat SaveFormat { get; set; }
```

### Osservazioni

Quando il valore di questa proprietà non è specificato, [`DocumentAssembler`](../../documentassembler) si comporta come segue:

- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

Attenzione, non è sempre possibile salvare un documento assemblato in qualsiasi formato file utilizzando GroupDocs.Assembly. Ad esempio, è impossibile salvare un documento caricato da un formato di elaborazione testi (come DOCX) in un formato di foglio di calcolo (come XLSX). Per ulteriori informazioni sulle possibili combinazioni di formati di file di caricamento e salvataggio supportate da GroupDocs.Assembly, consultare la documentazione online di GroupDocs.Assembly.

### Vedi anche

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
