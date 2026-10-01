---
title: "CsvDataSource"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يوفر إمكانية الوصول إلى بيانات ملف CSV أو تدفق لاستخدامها أثناء تجميع المستند."
type: docs
weight: 110
url: /ar/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

يوفر إمكانية الوصول إلى بيانات ملف CSV أو تدفق لاستخدامها أثناء تجميع المستند.

```csharp
public class CsvDataSource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | ينشئ مصدر بيانات جديد بالبيانات من تدفق CSV باستخدام الخيارات الافتراضية لتحليل بيانات CSV. |
| [CsvDataSource](csvdatasource#constructor_2)(string) | ينشئ مصدر بيانات جديد بالبيانات من ملف CSV باستخدام الخيارات الافتراضية لتحليل بيانات CSV. |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | ينشئ مصدر بيانات جديد بالبيانات من تدفق CSV باستخدام الخيارات المحددة لتحليل بيانات CSV. |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | ينشئ مصدر بيانات جديد بالبيانات من ملف CSV باستخدام الخيارات المحددة لتحليل بيانات CSV. |

### ملاحظات

للوصول إلى بيانات الملف أو التدفق المقابل أثناء تجميع مستند، مرّر مثيلًا من هذه الفئة كمصدر بيانات إلى أحد إصدارات الدالة [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

في مستندات القالب، يجب التعامل مع كائن [`CsvDataSource`](../csvdatasource) كما لو كان كائن DataTable. لمزيد من المعلومات، راجع مرجع صياغة القالب (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

يتم تحديد أنواع البيانات للقيم المفصولة بفواصل تلقائيًا بناءً على تمثيلها النصي. لذا في مستندات القالب، يمكنك العمل بالقيم ذات النوع بدلاً من السلاسل النصية فقط. يستطيع المحرك التعرف تلقائيًا على القيم من الأنواع التالية:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

لاحظ أنه لكي يعمل التعرف التلقائي على أنواع البيانات، يجب تشكيل تمثيلات السلاسل النصية للقيم المفصولة بفواصل باستخدام إعدادات الثقافة الثابتة.

لتجاوز السلوك الافتراضي لتحميل بيانات CSV، قم بتهيئة وتمرير كائن [`CsvDataLoadOptions`](../csvdataloadoptions) إلى مُنشئ هذه الفئة.

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
