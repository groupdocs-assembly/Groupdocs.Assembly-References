---
title: "XmlDataSource"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Fournit un accès aux données d'un fichier XML ou d'un flux à utiliser lors de l'assemblage d'un document."
type: docs
weight: 260
url: /fr/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

Fournit un accès aux données d'un fichier XML ou d'un flux à utiliser lors de l'assemblage d'un document.

```csharp
public class XmlDataSource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | Crée une nouvelle source de données à partir d'un flux XML en utilisant les options par défaut pour le chargement des données XML. |
| [XmlDataSource](xmldatasource#constructor_4)(string) | Crée une nouvelle source de données à partir d'un fichier XML en utilisant les options par défaut pour le chargement des données XML. |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | Crée une nouvelle source de données à partir d'un flux XML en utilisant un flux de définition de schéma XML (XSD). Les options par défaut sont utilisées pour le chargement des données XML. |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | Crée une nouvelle source de données avec des données provenant d'un flux XML en utilisant les options spécifiées pour le chargement des données XML. |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | Crée une nouvelle source de données avec des données provenant d'un fichier XML en utilisant un fichier de définition de schéma XML. Les options par défaut sont utilisées pour le chargement des données XML. |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | Crée une nouvelle source de données avec des données provenant d'un fichier XML en utilisant les options spécifiées pour le chargement des données XML. |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | Crée une nouvelle source de données avec des données provenant d'un flux XML en utilisant un flux de définition de schéma XML. Les options spécifiées sont utilisées pour le chargement des données XML. |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | Crée une nouvelle source de données avec des données provenant d'un fichier XML en utilisant un fichier de définition de schéma XML. Les options spécifiées sont utilisées pour le chargement des données XML. |

### Remarques

Pour accéder aux données du fichier ou du flux correspondant lors de l'assemblage d'un document, transmettez une instance de cette classe comme source de données à l'une des surcharges de [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

Dans les documents modèle, si un élément XML de niveau supérieur ne contient qu’une liste d’éléments du même type, une instance de [`XmlDataSource`](../xmldatasource) doit être traitée de la même manière qu’une instance de DataTable. Sinon, une instance de [`XmlDataSource`](../xmldatasource) doit être traitée de la même manière qu’une instance de DataRow. Pour plus d’informations, consultez la référence de la syntaxe des modèles (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Lorsque la définition de schéma XML est passée au constructeur de cette classe, les types de données des valeurs des éléments XML simples et des attributs sont déterminés selon le schéma. Ainsi, dans les documents modèle, vous pouvez travailler avec des valeurs typées plutôt qu’avec de simples chaînes.

Lorsque la définition de schéma XML n’est pas passée au constructeur de cette classe, les types de données des valeurs des éléments XML simples et des attributs sont déterminés automatiquement à partir de leurs représentations sous forme de chaîne. Ainsi, dans les documents modèle, vous pouvez également travailler avec des valeurs typées dans ce cas. Le moteur est capable de reconnaître automatiquement les valeurs des types suivants :

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

Notez que, pour que la reconnaissance automatique des types de données fonctionne, les représentations sous forme de chaîne des valeurs des éléments XML simples et des attributs doivent être générées en utilisant les paramètres de culture invariante.

Pour remplacer le comportement par défaut du chargement des données XML, initialisez et transmettez une instance de [`XmlDataLoadOptions`](../xmldataloadoptions) au constructeur de cette classe.

### Voir aussi

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
