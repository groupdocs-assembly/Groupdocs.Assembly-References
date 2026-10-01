---
title: "DocumentTable"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Fournit un accès aux données d’une seule table ou feuille de calcul située dans un document externe à utiliser lors de l’assemblage d’un document."
type: docs
weight: 120
url: /fr/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

Fournit un accès aux données d'une seule table (ou feuille de calcul) située dans un document externe à utiliser lors de l'assemblage d'un document.

```csharp
public class DocumentTable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | Crée une nouvelle instance de cette classe en utilisant les [`DocumentTableOptions`](../documenttableoptions) par défaut. |
| [DocumentTable](documenttable#constructor_2)(string, int) | Crée une nouvelle instance de cette classe en utilisant les [`DocumentTableOptions`](../documenttableoptions) par défaut. |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | Crée une nouvelle instance de cette classe. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | Crée une nouvelle instance de cette classe. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | Obtient la collection d’objets [`DocumentTableColumn`](../documenttablecolumn) représentant les colonnes de la table correspondante. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | Obtient l’indice d’origine basé sur zéro de la table correspondante tel qu’il apparaît dans le document source. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | Obtient ou définit le nom de cette table utilisé pour accéder aux données de la table dans un document modèle transmis à [`DocumentAssembler`](../../groupdocs.assembly/documentassembler). |

### Remarques

Pour les documents au format de feuille de calcul, une instance de [`DocumentTable`](../documenttable) représente une seule feuille. Pour les documents d’autres formats de fichier, une instance de [`DocumentTable`](../documenttable) représente une seule table.

Pour accéder aux données de la table correspondante lors de l’assemblage d’un document, transmettez une instance de cette classe comme source de données à l’une des surcharges de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Dans les documents modèle, une instance de [`DocumentTable`](../documenttable) doit être traitée de la même manière qu’une instance de DataTable. Consultez la référence de la syntaxe des modèles pour plus d’informations.

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
