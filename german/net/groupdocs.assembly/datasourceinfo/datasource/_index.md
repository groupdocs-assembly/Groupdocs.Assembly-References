---
title: "DataSource"
second_title: "GroupDocs.Assembly für .NET API-Referenz"
description: "Liest oder setzt das Datenquellenobjekt."
type: docs
weight: 20
url: /de/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

Liest oder setzt das Datenquellenobjekt.

```csharp
public object DataSource { get; set; }
```

### Hinweise

Das Datenquellenobjekt kann einer der folgenden Typen sein:

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

Weitere Informationen darüber, wie man mit Datenquellen verschiedener Typen in Vorlagendokumenten arbeitet, finden Sie in der Referenz zur Vorlagensyntax (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### Siehe auch

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Assembly.dll -->
