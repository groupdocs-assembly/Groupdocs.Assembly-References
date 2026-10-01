---
title: "SaveFormat"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit un format de fichier pour enregistrer un document assemblé. Non spécifié est la valeur par défaut."
type: docs
weight: 40
url: /fr/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

Obtient ou définit un format de fichier pour enregistrer un document assemblé. Non spécifié est la valeur par défaut.

```csharp
public FileFormat SaveFormat { get; set; }
```

### Remarques

Lorsque la valeur de cette propriété n'est pas spécifiée, [`DocumentAssembler`](../../documentassembler) se comporte comme suit :

- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

Attention, il n'est pas toujours possible d'enregistrer un document assemblé dans n'importe quel format de fichier avec GroupDocs.Assembly. Par exemple, il est impossible d'enregistrer un document chargé depuis un format de traitement de texte (tel que DOCX) dans un format de feuille de calcul (tel que XLSX). Pour plus d'informations sur les combinaisons possibles de formats de chargement et d'enregistrement pris en charge par GroupDocs.Assembly, veuillez consulter la documentation en ligne de GroupDocs.Assembly.

### Voir aussi

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
