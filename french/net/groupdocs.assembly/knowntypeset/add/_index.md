---
title: "Ajouter"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Ajoute l'objet Type spécifié à l'ensemble."
type: docs
weight: 20
url: /fr/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

Ajoute l'objet Type spécifié à l'ensemble.

Lance ArgumentException dans les cas suivants :

- *type* is null.

- *type* represents a void type.

- *type* represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

- *type* represents a generic type.

- *type* represents an array type.

- *type* has been added to the set already.

```csharp
public void Add(Type type)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | Type | Un objet Type à ajouter. |

### Voir aussi

* class [KnownTypeSet](../../knowntypeset)
* namespace [GroupDocs.Assembly](../../knowntypeset)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
