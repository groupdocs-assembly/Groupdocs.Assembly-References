---
title: KnownTypeSet
second_title: Référence de l'API GroupDocs.Assembly pour .NET
description: Représente un ensemble non ordonné cestàdire une collection déléments uniques contenantType objets dont les noms entièrement ou partiellement qualifiés peuvent être utilisés dans les modèles de document pour invoquer les membres statiques des types correspondants effectuer des conversions de type etc.
type: docs
weight: 230
url: /fr/net/groupdocs.assembly/knowntypeset/
---
## KnownTypeSet class

Représente un ensemble non ordonné (c'est-à-dire une collection d'éléments uniques) contenantType objets dont les noms entièrement ou partiellement qualifiés peuvent être utilisés dans les modèles de document pour invoquer les membres statiques des types correspondants, effectuer des conversions de type, etc.

```csharp
public class KnownTypeSet : IEnumerable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../groupdocs.assembly/knowntypeset/count) { get; } | Obtient le nombre d'éléments dans l'ensemble. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Add](../../groupdocs.assembly/knowntypeset/add)(Type) | Ajoute le spécifiéType s'opposer à l'ensemble. LanceArgumentException dans les cas suivants : |
| [Clear](../../groupdocs.assembly/knowntypeset/clear)() | Supprime tous les éléments de l'ensemble. |
| [GetEnumerator](../../groupdocs.assembly/knowntypeset/getenumerator)() | Renvoie UnIEnumerator objet à itérer sur les éléments de l'ensemble. |
| [Remove](../../groupdocs.assembly/knowntypeset/remove)(Type) | Supprime le spécifiéType objet de l'ensemble. LanceArgumentException si *type* est nul. |

### Voir également

* espace de noms [GroupDocs.Assembly](../../groupdocs.assembly)
* Assemblée [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->