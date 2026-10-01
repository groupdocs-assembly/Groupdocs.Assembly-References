---
title: "LoadSaveOptions"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Spécifie des options supplémentaires pour le chargement et l'enregistrement d'un document à assembler."
type: docs
weight: 80
url: /fr/net/groupdocs.assembly/loadsaveoptions/
---
## LoadSaveOptions class

Spécifie des options supplémentaires pour le chargement et l'enregistrement d'un document à assembler.

```csharp
public class LoadSaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LoadSaveOptions](loadsaveoptions#constructor)() | Crée une nouvelle instance de cette classe sans aucune propriété spécifiée. |
| [LoadSaveOptions](loadsaveoptions#constructor_1)(FileFormat) | Crée une nouvelle instance de cette classe avec le format de fichier spécifié pour enregistrer un document assemblé. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ResourceLoadBaseUri](../../groupdocs.assembly/loadsaveoptions/resourceloadbaseuri) { get; set; } | Obtient ou définit une URI de base pour résoudre les URI relatives des fichiers de ressources externes en URI absolues lors du chargement d'un document modèle HTML à assembler et à enregistrer dans un format non HTML. La valeur par défaut est une chaîne vide. |
| [ResourceSaveFolder](../../groupdocs.assembly/loadsaveoptions/resourcesavefolder) { get; set; } | Obtient ou définit un chemin vers un dossier pour stocker les fichiers de ressources externes pendant qu'un document assemblé chargé depuis un format non HTML est enregistré en HTML. La valeur par défaut est une chaîne vide. |
| [SaveFormat](../../groupdocs.assembly/loadsaveoptions/saveformat) { get; set; } | Obtient ou définit un format de fichier pour enregistrer un document assemblé. Non spécifié est la valeur par défaut. |

### Voir aussi

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
