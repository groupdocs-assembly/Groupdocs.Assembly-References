---
title: "DataSourceInfo"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Crée une nouvelle instance de cette classe sans aucune propriété spécifiée."
type: docs
weight: 10
url: /fr/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

Crée une nouvelle instance de cette classe sans aucune propriété spécifiée.

```csharp
public DataSourceInfo()
```

### Voir aussi

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

Crée une nouvelle instance de cette classe avec l'objet source de données spécifié.

```csharp
public DataSourceInfo(object dataSource)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dataSource | Object | L'objet source de données. |

### Remarques

L'objet source de données peut être de l'un des types suivants :

* [`XmlDataSource`](../../../groupdocs.assembly.data/xmldatasource)
* [`JsonDataSource`](../../../groupdocs.assembly.data/jsondatasource)
* [`CsvDataSource`](../../../groupdocs.assembly.data/csvdatasource)
* [`DocumentTableSet`](../../../groupdocs.assembly.data/documenttableset)
* [`DocumentTable`](../../../groupdocs.assembly.data/documenttable)
* DataSet
* DataTable
* DataRow
* IDataReader
* IDataRecord
* DataView
* DataRowView
* Any other arbitrary non-dynamic and non-anonymous .NET type

Pour obtenir des informations sur la façon de travailler avec des sources de données de différents types dans les documents modèle, consultez la référence de la syntaxe du modèle (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### Voir aussi

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object, string) {#constructor_2}

Crée une nouvelle instance de cette classe avec l'objet source de données et son nom spécifiés.

```csharp
public DataSourceInfo(object dataSource, string name)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| dataSource | Object | L'objet source de données. |
| name | String | Le nom de l'objet source de données à utiliser pour accéder à l'objet source de données dans un document modèle. |

### Remarques

L'objet source de données peut être de l'un des types suivants :

* [`XmlDataSource`](../../../groupdocs.assembly.data/xmldatasource)
* [`JsonDataSource`](../../../groupdocs.assembly.data/jsondatasource)
* [`CsvDataSource`](../../../groupdocs.assembly.data/csvdatasource)
* [`DocumentTableSet`](../../../groupdocs.assembly.data/documenttableset)
* [`DocumentTable`](../../../groupdocs.assembly.data/documenttable)
* DataSet
* DataTable
* DataRow
* IDataReader
* IDataRecord
* DataView
* DataRowView
* Any other arbitrary non-dynamic and non-anonymous .NET type

Pour obtenir des informations sur la façon de travailler avec des sources de données de différents types dans les documents modèle, consultez la référence de la syntaxe du modèle (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

Lorsque le nom de l'objet source de données est spécifié, vous pouvez accéder à l'objet source de données et à ses membres dans un document modèle en utilisant le nom.

Lorsque le nom de l'objet source de données est nul ou vide, vous pouvez toujours accéder aux membres de l'objet source de données dans un document modèle en utilisant l'accès aux membres de l'objet de contexte (voir Référence de la syntaxe du modèle pour plus d'informations), mais vous ne pouvez pas accéder à l'objet source de données lui‑même.

Lors du passage de plusieurs instances de [`DataSourceInfo`](../../datasourceinfo) à [`DocumentAssembler`](../../documentassembler), seul le nom du premier objet source de données peut être nul ou vide. Les noms des autres doivent être spécifiés et uniques.

### Voir aussi

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
