---
title: AssembleDocument
second_title: Riferimento API GroupDocs.Assembly per .NET
description: Carica un documento modello dal percorso di origine specificato popola il documento modello con i dati da le origini singole o multiple specificate e archivia il documento risultante nel percorso di destinazione utilizzando default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /it/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

Carica un documento modello dal percorso di origine specificato, popola il documento modello con i dati da le origini singole o multiple specificate e archivia il documento risultante nel percorso di destinazione utilizzando default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Il percorso di un documento modello da compilare con i dati. |
| targetPath | String | Il percorso di un documento risultato. |
| dataSourceInfos | DataSourceInfo[] | Fornisce informazioni sugli oggetti origine dati da utilizzare. |

### Valore di ritorno

Un flag che indica se l'analisi del documento modello è riuscita. Il flag restituito ha senso solo se è un valore di[`Options`](../options) la proprietà comprende ilInlineErrorMessages opzione.

### Guarda anche

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* spazio dei nomi [GroupDocs.Assembly](../../documentassembler)
* assemblea [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

Carica un documento modello dal percorso di origine specificato, popola il documento modello con i dati provenienti da le origini singole o multiple specificate e memorizza il documento risultante nel percorso di destinazione utilizzando given [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourcePath | String | Il percorso di un documento modello da compilare con i dati. |
| targetPath | String | Il percorso di un documento risultato. |
| loadSaveOptions | LoadSaveOptions | Specifica opzioni aggiuntive per il caricamento e il salvataggio dei documenti. |
| dataSourceInfos | DataSourceInfo[] | Fornisce informazioni sugli oggetti origine dati da utilizzare. |

### Valore di ritorno

Un flag che indica se l'analisi del documento modello è riuscita. Il flag restituito ha senso solo se è un valore di[`Options`](../options) la proprietà comprende ilInlineErrorMessages opzione.

### Guarda anche

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* spazio dei nomi [GroupDocs.Assembly](../../documentassembler)
* assemblea [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

Carica un documento modello dal flusso di origine specificato, popola il documento modello con i dati provenienti da le origini singole o multiple specificate e memorizza il documento risultante nel flusso di destinazione utilizzando default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceStream | Stream | Il flusso da cui leggere un documento modello. |
| targetStream | Stream | Il flusso per scrivere un documento di risultato. |
| dataSourceInfos | DataSourceInfo[] | Fornisce informazioni sugli oggetti origine dati da utilizzare. |

### Valore di ritorno

Un flag che indica se l'analisi del documento modello è riuscita. Il flag restituito ha senso solo se è un valore di[`Options`](../options) la proprietà comprende ilInlineErrorMessages opzione.

### Guarda anche

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* spazio dei nomi [GroupDocs.Assembly](../../documentassembler)
* assemblea [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

Carica un documento modello dal flusso di origine specificato, popola il documento modello con i dati provenienti da le origini singole o multiple specificate e memorizza il documento risultante nel flusso di destinazione utilizzando il given [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceStream | Stream | Il flusso da cui leggere un documento modello. |
| targetStream | Stream | Il flusso per scrivere un documento di risultato. |
| loadSaveOptions | LoadSaveOptions | Specifica opzioni aggiuntive per il caricamento e il salvataggio dei documenti. |
| dataSourceInfos | DataSourceInfo[] | Fornisce informazioni sugli oggetti origine dati da utilizzare. |

### Valore di ritorno

Un flag che indica se l'analisi del documento modello è riuscita. Il flag restituito ha senso solo se è un valore di[`Options`](../options) la proprietà comprende ilInlineErrorMessages opzione.

### Guarda anche

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* spazio dei nomi [GroupDocs.Assembly](../../documentassembler)
* assemblea [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
