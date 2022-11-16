---
title: JsonSimpleValueParseMode
second_title: Référence de l'API GroupDocs.Assembly pour .NET
description: Spécifie un mode danalyse des valeurs simples JSON nulle booléenne nombre entier et chaîne lors du chargement de JSON. Un tel mode naffecte pas lanalyse des valeurs dateheure.
type: docs
weight: 160
url: /fr/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

Spécifie un mode d'analyse des valeurs simples JSON (nulle, booléenne, nombre, entier et chaîne) lors du chargement de JSON. Un tel mode n'affecte pas l'analyse des valeurs date-heure.

```csharp
public enum JsonSimpleValueParseMode
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Loose | `0` | Spécifie le mode dans lequel les types de valeurs simples JSON sont déterminés lors de l'analyse de leurs représentations sous forme de chaîne. Par exemple, le type de 'prop' de l'extrait JSON '{ prop: "123" }' est déterminé comme entier dans ce mode. |
| Strict | `1` | Spécifie le mode dans lequel les types de valeurs simples JSON sont déterminés à partir de la notation JSON elle-même. Par exemple, le type de 'prop' de l'extrait JSON '{ prop: "123" }' est déterminé comme chaîne dans ce mode. |

### Voir également

* espace de noms [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* Assemblée [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->