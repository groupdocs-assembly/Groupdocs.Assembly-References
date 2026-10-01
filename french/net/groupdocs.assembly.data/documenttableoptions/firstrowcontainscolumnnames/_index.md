---
title: "FirstRowContainsColumnNames"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit une valeur indiquant si les noms de colonnes doivent être obtenus à partir de la première ligne extraite d’une table de document. La valeur par défaut est false."
type: docs
weight: 20
url: /fr/net/groupdocs.assembly.data/documenttableoptions/firstrowcontainscolumnnames/
---
## DocumentTableOptions.FirstRowContainsColumnNames property

Obtient ou définit une valeur indiquant si les noms de colonnes doivent être obtenus à partir de la première ligne extraite d’une table de document. La valeur par défaut est false.

```csharp
public bool FirstRowContainsColumnNames { get; set; }
```

### Remarques

Si les noms de colonnes ne sont pas définis pour être obtenus à partir de la première ligne extraite d'une table de document, des noms de colonnes par défaut sont utilisés à la place. Pour les documents au format de feuille de calcul, les noms de colonnes par défaut sont définis comme A, B, C, ... Z, AA, AB, etc. Pour les documents d'autres formats de fichier, les noms de colonnes par défaut sont définis comme Column1, Column2, Column3, etc.

### Voir aussi

* class [DocumentTableOptions](../../documenttableoptions)
* namespace [GroupDocs.Assembly.Data](../../documenttableoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
