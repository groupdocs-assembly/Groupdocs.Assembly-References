---
title: "ResourceSaveFolder"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit un chemin vers un dossier pour stocker les fichiers de ressources externes pendant qu'un document assemblé chargé à partir d'un format non HTML est enregistré au format HTML. La valeur par défaut est une chaîne vide."
type: docs
weight: 30
url: /fr/net/groupdocs.assembly/loadsaveoptions/resourcesavefolder/
---
## LoadSaveOptions.ResourceSaveFolder property

Obtient ou définit un chemin vers un dossier pour stocker les fichiers de ressources externes pendant qu'un document assemblé chargé depuis un format non HTML est enregistré en HTML. La valeur par défaut est une chaîne vide.

```csharp
public string ResourceSaveFolder { get; set; }
```

### Remarques

Par défaut, lors de l'enregistrement d'un document assemblé dans un fichier HTML, les fichiers de ressources externes sont stockés dans un dossier portant le même nom que le fichier HTML sans extension, suivi du suffixe "_files". Ce dossier se trouve dans le même répertoire que le fichier HTML. Cependant, cela n'est pas possible lors de l'enregistrement d'un document assemblé dans un flux HTML. Définissez cette propriété pour spécifier un chemin vers un dossier afin de stocker les fichiers de ressources externes lors de l'enregistrement d'un document assemblé dans un flux HTML ou pour remplacer le dossier par défaut lors de l'enregistrement d'un document assemblé dans un fichier HTML.

Une valeur de cette propriété est ignorée si le document assemblé enregistré au format HTML a également été chargé depuis du HTML (les fichiers de ressources externes ne sont alors pas stockés et les liens vers ceux‑ci ne sont pas modifiés).

### Voir aussi

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
