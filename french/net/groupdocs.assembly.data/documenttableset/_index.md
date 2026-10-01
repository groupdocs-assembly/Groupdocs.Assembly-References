---
title: "DocumentTableSet"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Fournit un accès aux données de plusieurs tables ou feuilles de calcul situées dans un document externe à utiliser lors de l'assemblage d'un document. Permet également de définir des relations parent‑enfant pour les tables du document, simplifiant ainsi l'accès aux données associées dans les documents modèle."
type: docs
weight: 200
url: /fr/net/groupdocs.assembly.data/documenttableset/
---
## DocumentTableSet class

Fournit un accès aux données de plusieurs tables (ou feuilles de calcul) situées dans un document externe à utiliser lors de l'assemblage d'un document. Permet également de définir des relations parent-enfant pour les tables de document, simplifiant ainsi l'accès aux données liées dans les documents modèles.

```csharp
public class DocumentTableSet
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DocumentTableSet](documenttableset#constructor)(Stream) | Crée une nouvelle instance de cette classe en chargeant toutes les tables d'un document en utilisant les [`DocumentTableOptions`](../documenttableoptions) par défaut. |
| [DocumentTableSet](documenttableset#constructor_2)(string) | Crée une nouvelle instance de cette classe en chargeant toutes les tables d'un document en utilisant les [`DocumentTableOptions`](../documenttableoptions) par défaut. |
| [DocumentTableSet](documenttableset#constructor_1)(Stream, IDocumentTableLoadHandler) | Crée une nouvelle instance de cette classe. |
| [DocumentTableSet](documenttableset#constructor_3)(string, IDocumentTableLoadHandler) | Crée une nouvelle instance de cette classe. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Relations](../../groupdocs.assembly.data/documenttableset/relations) { get; } | Obtient la collection des relations parent‑enfant définies pour les tables de document de cet ensemble. |
| [Tables](../../groupdocs.assembly.data/documenttableset/tables) { get; } | Obtient la collection des objets [`DocumentTable`](../documenttable) représentant les tables de cet ensemble. |

### Remarques

Pour les documents au format de feuille de calcul, une instance de [`DocumentTableSet`](../documenttableset) représente un ensemble de feuilles. Pour les documents d'autres formats de fichier, une instance de [`DocumentTableSet`](../documenttableset) représente un ensemble de tables.

Pour accéder aux données des tables correspondantes lors de l'assemblage d'un document, transmettez une instance de cette classe en tant que source de données à l'une des surcharges de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Dans les documents modèle, une instance de [`DocumentTableSet`](../documenttableset) doit être traitée de la même manière qu'une instance de DataSet. Consultez la référence de la syntaxe des modèles pour plus d'informations.

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
