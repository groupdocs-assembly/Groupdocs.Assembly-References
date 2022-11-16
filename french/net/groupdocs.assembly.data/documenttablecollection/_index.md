---
title: DocumentTableCollection
second_title: Référence de l'API GroupDocs.Assembly pour .NET
description: Représente une collection en lecture seule deDocumentTable./documenttable objets dun particulierDocumentTableSet./documenttableset instance.
type: docs
weight: 50
url: /fr/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

Représente une collection en lecture seule de[`DocumentTable`](../documenttable) objets d'un particulier[`DocumentTableSet`](../documenttableset) instance.

```csharp
public class DocumentTableCollection : IEnumerable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | Obtient le nombre total de[`DocumentTable`](../documenttable) objets de la collection. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | Obtient un[`DocumentTable`](../documenttable) instance de la collection à l'index spécifié. (2 indexers) |

## Méthodes

| Nom | La description |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | Renvoie une valeur indiquant si cette collection contient la table spécifiée. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | Renvoie une valeur indiquant si cette collection contient une table avec le nom spécifié. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | Renvoie un énumérateur à itérer[`DocumentTable`](../documenttable) objets de cette collection. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | Renvoie l'index de la table spécifiée dans cette collection. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | Renvoie l'index d'une table avec le nom spécifié dans cette collection. |

### Remarques

La collection est remplie automatiquement lors du chargement des tableaux correspondants à partir d'un document et ne peut pas être modifiée. Cependant, les propriétés de[`DocumentTable`](../documenttable)les objets contenus dans la collection peuvent être modifiés.

### Voir également

* espace de noms [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* Assemblée [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->