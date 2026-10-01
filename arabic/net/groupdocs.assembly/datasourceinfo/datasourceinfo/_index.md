---
title: "DataSourceInfo"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "ينشئ نسخة جديدة من هذه الفئة دون تحديد أي خصائص."
type: docs
weight: 10
url: /ar/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

ينشئ نسخة جديدة من هذه الفئة دون تحديد أي خصائص.

```csharp
public DataSourceInfo()
```

### انظر أيضًا

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

ينشئ نسخة جديدة من هذه الفئة مع كائن مصدر البيانات المحدد.

```csharp
public DataSourceInfo(object dataSource)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| dataSource | Object | كائن مصدر البيانات. |

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

---

## DataSourceInfo(object, string) {#constructor_2}

ينشئ نسخة جديدة من هذه الفئة مع كائن مصدر البيانات واسمه المحددين.

```csharp
public DataSourceInfo(object dataSource, string name)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| dataSource | Object | كائن مصدر البيانات. |
| name | String | اسم كائن مصدر البيانات الذي سيُستخدم للوصول إلى كائن مصدر البيانات في مستند القالب. |

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

عند تحديد اسم كائن مصدر البيانات، يمكنك الوصول إلى كائن مصدر البيانات وأعضائه في مستند القالب باستخدام الاسم.

عند كون اسم كائن مصدر البيانات فارغًا أو null، لا يزال بإمكانك الوصول إلى أعضاء كائن مصدر البيانات في مستند القالب باستخدام وصول أعضاء كائن السياق (انظر مرجع صsyntax القالب لمزيد من المعلومات)، لكن لا يمكنك الوصول إلى كائن مصدر البيانات نفسه.

عند تمرير عدة مثيلات من [`DataSourceInfo`](../../datasourceinfo) إلى [`DocumentAssembler`](../../documentassembler)، يمكن أن يكون اسم كائن مصدر البيانات الأول فقط null أو فارغ. يجب تحديد أسماء البقية وتكون فريدة.

### انظر أيضًا

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
