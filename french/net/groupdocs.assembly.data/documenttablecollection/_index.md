---
title: "DocumentTableCollection"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Représente une collection en lecture seule d'objets DocumentTable./documenttable d'une instance particulière de DocumentTableSet./documenttableset."
type: docs
weight: 130
url: /fr/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

Représente une collection en lecture seule d'objets [`DocumentTable`](../documenttable) d'une instance particulière de [`DocumentTableSet`](../documenttableset).

```csharp
public class DocumentTableCollection : IEnumerable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | Obtient le nombre total d'objets [`DocumentTable`](../documenttable) dans la collection. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | Obtient une instance [`DocumentTable`](../documenttable) de la collection à l'index spécifié. (2 indexeurs) |

## Méthodes

| Nom | Description |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | Renvoie une valeur indiquant si cette collection contient la table spécifiée. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | Renvoie une valeur indiquant si cette collection contient une table portant le nom spécifié. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | Renvoie un énumérateur pour parcourir les objets [`DocumentTable`](../documenttable) de cette collection. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | Renvoie l'index de la table spécifiée dans cette collection. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | Renvoie l'index d'une table portant le nom spécifié dans cette collection. |

### Remarques

La collection est remplie automatiquement lors du chargement des tables correspondantes depuis un document et ne peut pas être modifiée. Cependant, les propriétés des objets [`DocumentTable`](../documenttable) contenus dans la collection peuvent être modifiées.

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
