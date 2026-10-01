---
title: "CsvDataSource"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Fournit un accès aux données d'un fichier CSV ou d'un flux à utiliser lors de l'assemblage d'un document."
type: docs
weight: 110
url: /fr/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

Fournit un accès aux données d'un fichier CSV ou d'un flux à utiliser lors de l'assemblage d'un document.

```csharp
public class CsvDataSource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | Crée une nouvelle source de données à partir d'un flux CSV en utilisant les options par défaut pour l'analyse des données CSV. |
| [CsvDataSource](csvdatasource#constructor_2)(string) | Crée une nouvelle source de données à partir d'un fichier CSV en utilisant les options par défaut pour l'analyse des données CSV. |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | Crée une nouvelle source de données à partir d'un flux CSV en utilisant les options spécifiées pour l'analyse des données CSV. |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | Crée une nouvelle source de données à partir d'un fichier CSV en utilisant les options spécifiées pour l'analyse des données CSV. |

### Remarques

Pour accéder aux données du fichier ou du flux correspondant lors de l'assemblage d'un document, transmettez une instance de cette classe comme source de données à l'une des surcharges de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Dans les documents modèle, une instance de [`CsvDataSource`](../csvdatasource) doit être traitée de la même manière qu'une instance de DataTable. Pour plus d'informations, consultez la référence de la syntaxe des modèles (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Les types de données des valeurs séparées par des virgules sont déterminés automatiquement à partir de leurs représentations sous forme de chaîne. Ainsi, dans les documents modèle, vous pouvez travailler avec des valeurs typées plutôt qu'avec de simples chaînes. Le moteur est capable de reconnaître automatiquement les valeurs des types suivants :

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Notez que, pour que la reconnaissance automatique des types de données fonctionne, les représentations sous forme de chaîne des valeurs séparées par des virgules doivent être générées en utilisant les paramètres de culture invariante.

Pour remplacer le comportement par défaut du chargement des données CSV, initialisez et transmettez une instance de [`CsvDataLoadOptions`](../csvdataloadoptions) au constructeur de cette classe.

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
