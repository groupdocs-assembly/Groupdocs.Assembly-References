---
title: "DataSource"
second_title: "GroupDocs.Assembly for .NET API Referansı"
description: "Veri kaynağı nesnesini alır veya ayarlar."
type: docs
weight: 20
url: /tr/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

Veri kaynağı nesnesini alır veya ayarlar.

```csharp
public object DataSource { get; set; }
```

### Açıklamalar

Veri kaynağı nesnesi aşağıdaki türlerden biri olabilir:

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

Şablon belgelerinde farklı türde veri kaynaklarıyla nasıl çalışılacağı hakkında bilgi için, şablon sözdizimi referansına bakın (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### Ayrıca Bakınız

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından oluşturulan GroupDocs.Assembly.dll -->
