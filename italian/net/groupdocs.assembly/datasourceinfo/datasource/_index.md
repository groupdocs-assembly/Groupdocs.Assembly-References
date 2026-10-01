---
title: "DataSource"
second_title: "Riferimento API di GroupDocs.Assembly per .NET"
description: "Ottiene o imposta l'oggetto data source."
type: docs
weight: 20
url: /it/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

Ottiene o imposta l'oggetto data source.

```csharp
public object DataSource { get; set; }
```

### Osservazioni

L'oggetto data source può essere di uno dei seguenti tipi:

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

Per informazioni su come lavorare con data source di diversi tipi nei documenti modello, vedere il riferimento alla sintassi del modello (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### Vedi anche

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.Assembly.dll -->
