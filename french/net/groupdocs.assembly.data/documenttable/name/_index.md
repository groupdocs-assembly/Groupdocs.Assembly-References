---
title: "Nom"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit le nom de cette table utilisé pour accéder aux données de la table dans un document modèle transmis à DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 40
url: /fr/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

Obtient ou définit le nom de cette table utilisé pour accéder aux données de la table dans un document modèle transmis à [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### Remarques

Si le nom de la table est lu à partir d'un document, il est automatiquement corrigé pour qu'il soit valide. Cependant, si le nom de la table est défini manuellement via cette propriété et qu'il est invalide, une exception est levée.

Le nom de la table est considéré comme valide si les conditions suivantes sont remplies :

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTableSet`](../../documenttableset) object does not contain a [`DocumentTable`](../../documenttable) instance with the same name.

### Voir aussi

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
