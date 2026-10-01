---
title: "AssembleDocument"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Carica un documento modello dal percorso di origine specificato, popola il documento modello con i dati dalla sorgente singola o multipla specificata e salva il documento risultato nel percorso di destinazione utilizzando le impostazioni predefinite LoadSaveOptionsgroupdocs.assembly/loadsaveoptions."
type: docs
weight: 50
url: /it/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Carica un documento modello dal percorso di origine specificato, popola il documento modello con i dati dalla sorgente singola o multipla specificata e salva il documento risultato nel percorso di destinazione utilizzando le impostazioni predefinite [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Il percorso a un documento modello da popolare con i dati. |
| targetPath | String | Il percorso a un documento risultato. |
| dataSourceInfos | DataSourceInfo[] | Fornisce informazioni sugli oggetti sorgente dati da utilizzare. |

### Valore di ritorno

Un flag che indica se l'analisi del documento modello è stata completata con successo. Il flag restituito ha senso solo se il valore della proprietà [`Options`](../options) include l'opzione InlineErrorMessages.

### Vedi anche

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Carica un documento modello dal percorso di origine specificato, popola il documento modello con i dati dalla sorgente singola o multipla specificata e salva il documento risultato nel percorso di destinazione utilizzando le [`LoadSaveOptions`](../../loadsaveoptions) specificate.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Il percorso a un documento modello da popolare con i dati. |
| targetPath | String | Il percorso a un documento risultato. |
| loadSaveOptions | LoadSaveOptions | Specifica opzioni aggiuntive per il caricamento e il salvataggio dei documenti. |
| dataSourceInfos | DataSourceInfo[] | Fornisce informazioni sugli oggetti sorgente dati da utilizzare. |

### Valore di ritorno

Un flag che indica se l'analisi del documento modello è stata completata con successo. Il flag restituito ha senso solo se il valore della proprietà [`Options`](../options) include l'opzione InlineErrorMessages.

### Vedi anche

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Carica un documento modello dallo stream di origine specificato, popola il documento modello con i dati dalla sorgente singola o multipla specificata e salva il documento risultato nello stream di destinazione utilizzando le impostazioni predefinite [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceStream | Stream | Lo stream da cui leggere un documento modello. |
| targetStream | Stream | Lo stream su cui scrivere un documento risultato. |
| dataSourceInfos | DataSourceInfo[] | Fornisce informazioni sugli oggetti sorgente dati da utilizzare. |

### Valore di ritorno

Un flag che indica se l'analisi del documento modello è stata completata con successo. Il flag restituito ha senso solo se il valore della proprietà [`Options`](../options) include l'opzione InlineErrorMessages.

### Vedi anche

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Carica un documento modello dallo stream di origine specificato, popola il documento modello con i dati dalla sorgente singola o multipla specificata e salva il documento risultato nello stream di destinazione utilizzando le [`LoadSaveOptions`](../../loadsaveoptions) specificate.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceStream | Stream | Lo stream da cui leggere un documento modello. |
| targetStream | Stream | Lo stream su cui scrivere un documento risultato. |
| loadSaveOptions | LoadSaveOptions | Specifica opzioni aggiuntive per il caricamento e il salvataggio dei documenti. |
| dataSourceInfos | DataSourceInfo[] | Fornisce informazioni sugli oggetti sorgente dati da utilizzare. |

### Valore di ritorno

Un flag che indica se l'analisi del documento modello è stata completata con successo. Il flag restituito ha senso solo se il valore della proprietà [`Options`](../options) include l'opzione InlineErrorMessages.

### Vedi anche

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
