---
title: "IDocumentTableLoadHandler"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Remplace le chargement par défaut des objets DocumentTable./documenttable lors de la création d'une instance de DocumentTableSet./documenttableset."
type: docs
weight: 210
url: /fr/net/groupdocs.assembly.data/idocumenttableloadhandler/
---
## IDocumentTableLoadHandler interface

Remplace le chargement par défaut des objets [`DocumentTable`](../documenttable) lors de la création d'une instance de [`DocumentTableSet`](../documenttableset).

```csharp
public interface IDocumentTableLoadHandler
```

## Méthodes

| Nom | Description |
| --- | --- |
| [Handle](../../groupdocs.assembly.data/idocumenttableloadhandler/handle)(DocumentTableLoadArgs) | Remplace le chargement par défaut d'un objet [`DocumentTable`](../documenttable) particulier lors de la création d'une instance de [`DocumentTableSet`](../documenttableset). |

### Remarques

Implémentez cette interface si vous souhaitez ignorer le chargement de certains objets [`DocumentTable`](../documenttable) ou fournir des [`DocumentTableOptions`](../documenttableoptions) spécifiques pour les tables de document en cours de chargement.

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
