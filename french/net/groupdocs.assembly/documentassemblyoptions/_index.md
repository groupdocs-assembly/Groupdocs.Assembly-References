---
title: "DocumentAssemblyOptions"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Spécifie les options contrôlant le comportement de DocumentAssembler./documentassembler lors de l'assemblage d'un document."
type: docs
weight: 50
url: /fr/net/groupdocs.assembly/documentassemblyoptions/
---
## DocumentAssemblyOptions enumeration

Spécifie les options contrôlant le comportement de [`DocumentAssembler`](../documentassembler) lors de l'assemblage d'un document.

```csharp
[Flags]
public enum DocumentAssemblyOptions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Spécifie les options par défaut. |
| AllowMissingMembers | `1` | Spécifie que les membres d'objet manquants doivent être traités comme des littéraux null par l'assembleur. Cette option n'affecte que l'accès aux membres d'instance (c'est-à-dire non statiques) et aux méthodes d'extension. Si cette option n'est pas définie, l'assembleur lève une exception lorsqu'il rencontre un membre d'objet manquant. |
| UpdateFieldsAndFormulas | `2` | Spécifie que les champs des documents de traitement de texte résultants et les formules des documents de feuille de calcul résultants doivent être mis à jour par l'assembleur. |
| RemoveEmptyParagraphs | `4` | Spécifie que l'assembleur doit supprimer les paragraphes devenant vides après la suppression ou le remplacement par des valeurs vides des balises de syntaxe du modèle. |
| InlineErrorMessages | `8` | Spécifie que l'assembleur doit intégrer les messages d'erreur de syntaxe du modèle dans les documents de sortie. Si cette option n'est pas définie, l'assembleur lève une exception lorsqu'il rencontre une erreur de syntaxe. |
| UseSpreadsheetDataTypes | `10` | Concernant uniquement les documents Spreadsheet. Spécifie que les résultats d'expression évalués doivent être mappés aux types de données Spreadsheet correspondants, ce qui affecte également leur formatage par défaut dans les cellules. Si cette option n'est pas définie, les résultats d'expression sont toujours écrits en tant que chaînes par l'assembleur. Cette option n'a aucun effet lorsque les résultats d'expression sont formatés à l'aide de la syntaxe du modèle – les résultats d'expression sont alors également toujours écrits en tant que chaînes. |

### Voir aussi

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
