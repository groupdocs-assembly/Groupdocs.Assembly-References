---
title: "ResourceLoadBaseUri"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit une URI de base pour résoudre les fichiers de ressources externes dont les URI relatives sont converties en URI absolues lors du chargement d'un document modèle HTML à assembler et à enregistrer dans un format non HTML. La valeur par défaut est une chaîne vide."
type: docs
weight: 20
url: /fr/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

Obtient ou définit une URI de base pour résoudre les URI relatives des fichiers de ressources externes en URI absolues lors du chargement d'un document modèle HTML à assembler et à enregistrer dans un format non HTML. La valeur par défaut est une chaîne vide.

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### Remarques

Lors du chargement d'un document HTML depuis un fichier, son dossier contenant est utilisé comme URI de base par défaut, ce qui n'est pas possible lors du chargement d'un document HTML depuis un flux. Définissez cette propriété pour spécifier une URI de base lors du chargement d'un document HTML depuis un flux ou pour remplacer l'URI de base par défaut lors du chargement d'un document HTML depuis un fichier.

Une valeur de cette propriété est ignorée dans les cas suivants :

* An HTML document being loaded contains a BASE HTML element providing a base URI.
* An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

### Voir aussi

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
