---
title: "DataSource"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "डेटा स्रोत वस्तु को प्राप्त करता है या सेट करता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

डेटा स्रोत वस्तु को प्राप्त करता है या सेट करता है।

```csharp
public object DataSource { get; set; }
```

### टिप्पणियाँ

डेटा स्रोत ऑब्जेक्ट निम्नलिखित प्रकारों में से एक हो सकता है:

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

विभिन्न प्रकार के डेटा स्रोतों के साथ टेम्पलेट दस्तावेज़ों में काम करने के बारे में जानकारी के लिए, टेम्पलेट सिंटैक्स रेफ़रेंस देखें (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)।

### संबंधित देखें

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
