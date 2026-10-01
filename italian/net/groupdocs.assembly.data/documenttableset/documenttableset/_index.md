---
title: "DocumentTableSet"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Crea una nuova istanza di questa classe caricando tutte le tabelle da un documento usando le impostazioni predefinite DocumentTableOptionsgroupdocs.assembly.data/documenttableoptions."
type: docs
weight: 10
url: /it/net/groupdocs.assembly.data/documenttableset/documenttableset/
---
## DocumentTableSet(string) {#constructor_2}

Crea una nuova istanza di questa classe caricando tutte le tabelle da un documento usando le impostazioni predefinite [`DocumentTableOptions`](../../documenttableoptions).

```csharp
public DocumentTableSet(string documentPath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentPath | String | Il percorso a un documento contenente tabelle da accedere. |

### Vedi anche

* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

---

## DocumentTableSet(string, IDocumentTableLoadHandler) {#constructor_3}

Crea una nuova istanza di questa classe.

```csharp
public DocumentTableSet(string documentPath, IDocumentTableLoadHandler loadHandler)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentPath | String | Il percorso a un documento contenente tabelle da accedere. |
| loadHandler | IDocumentTableLoadHandler | Una implementazione di [`IDocumentTableLoadHandler`](../../idocumenttableloadhandler) che controlla come vengono caricate le tabelle del documento. |

### Vedi anche

* interface [IDocumentTableLoadHandler](../../idocumenttableloadhandler)
* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

---

## DocumentTableSet(Stream) {#constructor}

Crea una nuova istanza di questa classe caricando tutte le tabelle da un documento usando le impostazioni predefinite [`DocumentTableOptions`](../../documenttableoptions).

```csharp
public DocumentTableSet(Stream documentStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentStream | Stream | Lo stream contenente un documento con tabelle da accedere. |

### Vedi anche

* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

---

## DocumentTableSet(Stream, IDocumentTableLoadHandler) {#constructor_1}

Crea una nuova istanza di questa classe.

```csharp
public DocumentTableSet(Stream documentStream, IDocumentTableLoadHandler loadHandler)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentStream | Stream | Lo stream contenente un documento con tabelle da accedere. |
| loadHandler | IDocumentTableLoadHandler | Una implementazione di [`IDocumentTableLoadHandler`](../../idocumenttableloadhandler) che controlla come vengono caricate le tabelle del documento. |

### Vedi anche

* interface [IDocumentTableLoadHandler](../../idocumenttableloadhandler)
* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
