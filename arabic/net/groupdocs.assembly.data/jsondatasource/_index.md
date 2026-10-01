---
title: "JsonDataSource"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يوفر إمكانية الوصول إلى بيانات ملف JSON أو تدفق لاستخدامها أثناء تجميع المستند."
type: docs
weight: 230
url: /ar/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

يوفر إمكانية الوصول إلى بيانات ملف JSON أو تدفق لاستخدامها أثناء تجميع المستند.

```csharp
public class JsonDataSource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | ينشئ مصدر بيانات جديد باستخدام بيانات من تدفق JSON باستخدام الخيارات الافتراضية لتحليل بيانات JSON. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | ينشئ مصدر بيانات جديد باستخدام بيانات من ملف JSON باستخدام الخيارات الافتراضية لتحليل بيانات JSON. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | ينشئ مصدر بيانات جديد باستخدام بيانات من تدفق JSON باستخدام الخيارات المحددة لتحليل بيانات JSON. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | ينشئ مصدر بيانات جديد باستخدام بيانات من ملف JSON باستخدام الخيارات المحددة لتحليل بيانات JSON. |

### ملاحظات

للوصول إلى بيانات الملف أو التدفق المقابل أثناء تجميع مستند، مرّر مثيلًا من هذه الفئة كمصدر بيانات إلى أحد إصدارات الدالة [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

في مستندات القالب، إذا كان عنصر JSON من المستوى الأعلى مصفوفة، يجب معالجة مثيل [`JsonDataSource`](../jsondatasource) كما لو كان مثيل DataTable. إذا كان عنصر JSON من المستوى الأعلى كائنًا، يجب معالجة مثيل [`JsonDataSource`](../jsondatasource) كما لو كان مثيل DataRow. لمزيد من المعلومات، راجع مرجع صياغة القالب (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

في مستندات القالب، يمكنك العمل مع القيم ذات النوع لعناصر JSON. للتسهيل، يستبدل المحرك مجموعة الأنواع البسيطة لـ JSON بالنوع التالي:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

المحرك يتعرف تلقائيًا على قيم الأنواع الإضافية بناءً على تمثيلاتها في JSON.

لتجاوز السلوك الافتراضي لتحميل بيانات JSON، قم بتهيئة وتمرير مثيل [`JsonDataLoadOptions`](../jsondataloadoptions) إلى مُنشئ هذه الفئة.

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
