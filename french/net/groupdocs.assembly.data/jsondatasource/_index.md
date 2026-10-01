---
title: "JsonDataSource"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Fournit un accès aux données d'un fichier JSON ou d'un flux à utiliser lors de l'assemblage d'un document."
type: docs
weight: 230
url: /fr/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

Fournit un accès aux données d'un fichier JSON ou d'un flux à utiliser lors de l'assemblage d'un document.

```csharp
public class JsonDataSource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | Crée une nouvelle source de données avec les données d'un flux JSON en utilisant les options par défaut pour l'analyse des données JSON. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | Crée une nouvelle source de données avec les données d'un fichier JSON en utilisant les options par défaut pour l'analyse des données JSON. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | Crée une nouvelle source de données avec les données d'un flux JSON en utilisant les options spécifiées pour l'analyse des données JSON. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | Crée une nouvelle source de données avec les données d'un fichier JSON en utilisant les options spécifiées pour l'analyse des données JSON. |

### Remarques

Pour accéder aux données du fichier ou du flux correspondant lors de l'assemblage d'un document, transmettez une instance de cette classe comme source de données à l'une des surcharges de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Dans les documents modèle, si un élément JSON de niveau supérieur est un tableau, une instance de [`JsonDataSource`](../jsondatasource) doit être traitée de la même manière qu'une instance de DataTable. Si un élément JSON de niveau supérieur est un objet, une instance de [`JsonDataSource`](../jsondatasource) doit être traitée de la même manière qu'une instance de DataRow. Pour plus d'informations, consultez la référence de la syntaxe du modèle (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Dans les documents modèle, vous pouvez travailler avec des valeurs typées des éléments JSON. Pour plus de commodité, le moteur remplace l'ensemble des types simples JSON par le suivant :

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Le moteur reconnaît automatiquement les valeurs des types supplémentaires à partir de leurs représentations JSON.

Pour remplacer le comportement par défaut du chargement des données JSON, initialisez et transmettez une instance de [`JsonDataLoadOptions`](../jsondataloadoptions) au constructeur de cette classe.

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
