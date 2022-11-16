---
title: DataSource
second_title: GroupDocs.Assembly för .NET API-referens
description: Hämtar eller ställer in datakällans objekt.
type: docs
weight: 20
url: /sv/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

Hämtar eller ställer in datakällans objekt.

```csharp
public object DataSource { get; set; }
```

### Anmärkningar

Datakällobjektet kan vara av en av följande typer:

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
* Alla andra godtyckliga icke-dynamiska och icke-anonyma .NET type

För information om hur man arbetar med datakällor av olika typer i malldokument, se mallsyntaxreferens (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2# TemplateSyntax-Part1of2-UsingDataSources).

### Se även

* class [DataSourceInfo](../../datasourceinfo)
* namnutrymme [GroupDocs.Assembly](../../datasourceinfo)
* hopsättning [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->