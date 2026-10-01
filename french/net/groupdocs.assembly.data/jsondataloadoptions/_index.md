---
title: "JsonDataLoadOptions"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Représente les options pour l'analyse des données JSON."
type: docs
weight: 220
url: /fr/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

Représente les options pour l'analyse des données JSON.

```csharp
public class JsonDataLoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | Initialise une nouvelle instance de cette classe avec les options par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | Obtient ou définit un indicateur indiquant si une source de données générée contiendra toujours un objet pour un élément racine JSON. Si un élément racine JSON contient une seule propriété complexe, un tel objet n'est pas créé par défaut. |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | Obtient ou définit les formats exacts pour analyser les valeurs de date‑heure JSON lors du chargement du JSON. La valeur par défaut est **null**. |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | Obtient ou définit un mode d'analyse des valeurs simples JSON (null, booléen, nombre, entier et chaîne) lors du chargement du JSON. Un tel mode n'affecte pas l'analyse des valeurs de date‑heure. La valeur par défaut est Loose. |

### Remarques

Une instance de cette classe peut être transmise aux constructeurs de [`JsonDataSource`](../jsondatasource).

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
