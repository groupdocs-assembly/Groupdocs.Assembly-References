---
title: "DataSource"
second_title: "Référence d'API GroupDocs.Assembly pour .NET"
description: "Obtient ou définit l'objet source de données."
type: docs
weight: 20
url: /fr/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

Obtient ou définit l'objet source de données.

```csharp
public object DataSource { get; set; }
```

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

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Assembly.dll -->
