---
title: "JsonSimpleValueParseMode"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Spécifie un mode d'analyse des valeurs simples JSON null, boolean, number, integer et string lors du chargement du JSON. Un tel mode n'affecte pas l'analyse des valeurs datetime."
type: docs
weight: 240
url: /fr/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

Spécifie un mode d'analyse des valeurs simples JSON (null, booléen, nombre, entier et chaîne) lors du chargement du JSON. Un tel mode n'affecte pas l'analyse des valeurs de date‑heure.

```csharp
public enum JsonSimpleValueParseMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Loose | `0` | Spécifie le mode où les types des valeurs simples JSON sont déterminés lors de l'analyse de leurs représentations sous forme de chaîne. Par exemple, le type de 'prop' dans l'extrait JSON '{ prop: \"123\" }' est déterminé comme integer dans ce mode. |
| Strict | `1` | Spécifie le mode où les types des valeurs simples JSON sont déterminés à partir de la notation JSON elle‑même. Par exemple, le type de 'prop' dans l'extrait JSON '{ prop: \"123\" }' est déterminé comme string dans ce mode. |

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
