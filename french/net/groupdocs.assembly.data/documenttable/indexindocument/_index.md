---
title: "IndexInDocument"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient l'index d'origine basé sur zéro de la table correspondante selon le document source."
type: docs
weight: 30
url: /fr/net/groupdocs.assembly.data/documenttable/indexindocument/
---
## DocumentTable.IndexInDocument property

Obtient l’indice d’origine basé sur zéro de la table correspondante tel qu’il apparaît dans le document source.

```csharp
public int IndexInDocument { get; }
```

### Remarques

Selon l'implémentation fournie de [`IDocumentTableLoadHandler`](../../idocumenttableloadhandler), cet index peut différer de l'index de cette instance [`DocumentTable`](../../documenttable) au sein de la collection de tables de l'instance correspondante [`DocumentTableSet`](../../documenttableset), le cas échéant.

### Voir aussi

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
