---
title: "DocumentTableColumnCollection"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Représente une collection en lecture seule d'objets DocumentTableColumn./documenttablecolumn d'une instance particulière de DocumentTable./documenttable."
type: docs
weight: 150
url: /fr/net/groupdocs.assembly.data/documenttablecolumncollection/
---
## DocumentTableColumnCollection class

Représente une collection en lecture seule d'objets [`DocumentTableColumn`](../documenttablecolumn) d'une instance particulière de [`DocumentTable`](../documenttable).

```csharp
public class DocumentTableColumnCollection : IEnumerable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecolumncollection/count) { get; } | Obtient le nombre total d'objets [`DocumentTableColumn`](../documenttablecolumn) dans la collection. |
| [Item](../../groupdocs.assembly.data/documenttablecolumncollection/item) { get; } | Obtient une instance de [`DocumentTableColumn`](../documenttablecolumn) de la collection à l'index spécifié. (2 indexeurs) |

## Méthodes

| Nom | Description |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains)(DocumentTableColumn) | Renvoie une valeur indiquant si cette collection contient la colonne spécifiée. |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains_1)(string) | Renvoie une valeur indiquant si cette collection contient une colonne portant le nom spécifié. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecolumncollection/getenumerator)() | Renvoie un énumérateur pour parcourir les objets [`DocumentTableColumn`](../documenttablecolumn) de cette collection. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof)(DocumentTableColumn) | Renvoie l'index de la colonne spécifiée dans cette collection. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof_1)(string) | Renvoie l'index d'une colonne portant le nom spécifié dans cette collection. |

### Remarques

La collection est remplie automatiquement lors du chargement de la table correspondante depuis un document et ne peut pas être modifiée. Cependant, les propriétés des objets [`DocumentTableColumn`](../documenttablecolumn) contenus dans la collection peuvent être modifiées.

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
