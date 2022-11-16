---
title: Name
second_title: Référence de l'API GroupDocs.Assembly pour .NET
description: Obtient ou définit le nom de cette colonne utilisée pour accéder aux données de la colonne dans un modèle de document transmis à DocumentAssemblergroupdocs.assembly/documentassembler .
type: docs
weight: 30
url: /fr/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

Obtient ou définit le nom de cette colonne utilisée pour accéder aux données de la colonne dans un modèle de document transmis à [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler) .

```csharp
public string Name { get; set; }
```

### Remarques

Si le nom de la colonne est lu à partir d'un document (voir[`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames) ), le nom est automatiquement corrigé afin qu'il soit valide. Cependant, si le nom de la colonne est défini manuellement via cette propriété et que le nom n'est pas valide, une exception est levée.

Le nom de la colonne est considéré comme valide si les conditions suivantes sont remplies :

* Le nom n'est pas vide.
* Le premier caractère du nom est une lettre ou un trait de soulignement.
* Les autres caractères du nom sont des lettres, des traits de soulignement, des chiffres ou les caractères suivants : '@', '#', '$'.
* Le correspondant[`DocumentTable`](../../documenttable) l'objet ne contient pas de[`DocumentTableColumn`](../../documenttablecolumn)instance avec le même nom.

### Voir également

* class [DocumentTableColumn](../../documenttablecolumn)
* espace de noms [GroupDocs.Assembly.Data](../../documenttablecolumn)
* Assemblée [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->