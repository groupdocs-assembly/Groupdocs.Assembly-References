---
title: "DataSource"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يعيّن كائن مصدر البيانات."
type: docs
weight: 20
url: /ar/net/groupdocs.assembly/datasourceinfo/datasource/
---
## DataSourceInfo.DataSource property

يحصل أو يعيّن كائن مصدر البيانات.

```csharp
public object DataSource { get; set; }
```

### ملاحظات

يمكن أن يكون كائن مصدر البيانات أحد الأنواع التالية:

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

للحصول على معلومات حول كيفية العمل مع مصادر البيانات من أنواع مختلفة في مستندات القالب، راجع مرجع صsyntax القالب (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

### انظر أيضًا

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
