---
title: "ExactDateTimeParseFormats"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit les formats exacts pour analyser les valeurs datetime JSON lors du chargement du JSON. La valeur par défaut est null."
type: docs
weight: 30
url: /fr/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

Obtient ou définit les formats exacts pour analyser les valeurs de date‑heure JSON lors du chargement du JSON. La valeur par défaut est **null**.

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### Remarques

Les chaînes encodées en utilisant le format de date‑heure JSON de Microsoft® (par exemple, "/Date(1224043200000)/") sont toujours reconnues comme des valeurs de date‑heure, quel que soit la valeur de cette propriété. La propriété définit des formats supplémentaires à utiliser lors de l'analyse des valeurs de date‑heure à partir des chaînes de la manière suivante :

* When `ExactDateTimeParseFormats` is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
* When `ExactDateTimeParseFormats` contains strings, they are used as additional date-time formats utilizing the current culture.
* When `ExactDateTimeParseFormats` is empty, no additional date-time formats are used.

### Voir aussi

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* namespace [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
