---
title: "Nom"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit le nom de cette colonne utilisé pour accéder aux données des colonnes dans un document modèle transmis à DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 30
url: /fr/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

Obtient ou définit le nom de cette colonne utilisé pour accéder aux données de la colonne dans un document modèle transmis à [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### Remarques

Si le nom de la colonne est lu à partir d'un document (voir [`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames)), le nom est automatiquement corrigé pour qu'il soit valide. Cependant, si le nom de la colonne est défini manuellement via cette propriété et que le nom est invalide, une exception est levée.

Le nom de la colonne est considéré comme valide si les conditions suivantes sont remplies :

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTable`](../../documenttable) object does not contain a [`DocumentTableColumn`](../../documenttablecolumn) instance with the same name.

### Voir aussi

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
