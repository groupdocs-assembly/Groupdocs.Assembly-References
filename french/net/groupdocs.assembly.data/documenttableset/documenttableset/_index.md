---
title: "DocumentTableSet"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Crée une nouvelle instance de cette classe chargeant toutes les tables d'un document en utilisant les DocumentTableOptionsgroupdocs.assembly.data/documenttableoptions par défaut."
type: docs
weight: 10
url: /fr/net/groupdocs.assembly.data/documenttableset/documenttableset/
---
## DocumentTableSet(string) {#constructor_2}

Crée une nouvelle instance de cette classe chargeant toutes les tables d'un document en utilisant les [`DocumentTableOptions`](../../documenttableoptions) par défaut.

```csharp
public DocumentTableSet(string documentPath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentPath | String | Le chemin vers un document contenant des tables à accéder. |

### Voir aussi

* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

---

## DocumentTableSet(string, IDocumentTableLoadHandler) {#constructor_3}

Crée une nouvelle instance de cette classe.

```csharp
public DocumentTableSet(string documentPath, IDocumentTableLoadHandler loadHandler)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentPath | String | Le chemin vers un document contenant des tables à accéder. |
| loadHandler | IDocumentTableLoadHandler | Une implémentation de [`IDocumentTableLoadHandler`](../../idocumenttableloadhandler) contrôlant la façon dont les tables de document sont chargées. |

### Voir aussi

* interface [IDocumentTableLoadHandler](../../idocumenttableloadhandler)
* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

---

## DocumentTableSet(Stream) {#constructor}

Crée une nouvelle instance de cette classe chargeant toutes les tables d'un document en utilisant les [`DocumentTableOptions`](../../documenttableoptions) par défaut.

```csharp
public DocumentTableSet(Stream documentStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentStream | Stream | Le flux contenant un document avec des tables à accéder. |

### Voir aussi

* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

---

## DocumentTableSet(Stream, IDocumentTableLoadHandler) {#constructor_1}

Crée une nouvelle instance de cette classe.

```csharp
public DocumentTableSet(Stream documentStream, IDocumentTableLoadHandler loadHandler)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentStream | Stream | Le flux contenant un document avec des tables à accéder. |
| loadHandler | IDocumentTableLoadHandler | Une implémentation de [`IDocumentTableLoadHandler`](../../idocumenttableloadhandler) contrôlant la façon dont les tables de document sont chargées. |

### Voir aussi

* interface [IDocumentTableLoadHandler](../../idocumenttableloadhandler)
* class [DocumentTableSet](../../documenttableset)
* namespace [GroupDocs.Assembly.Data](../../documenttableset)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
