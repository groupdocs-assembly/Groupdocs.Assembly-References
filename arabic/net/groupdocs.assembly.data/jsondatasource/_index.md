---
title: JsonDataSource
second_title: GroupDocs.Assembly للحصول على مرجع .NET API
description: يوفر الوصول إلى بيانات ملف أو دفق JSON ليتم استخدامه أثناء تجميع مستند.
type: docs
weight: 150
url: /ar/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

يوفر الوصول إلى بيانات ملف أو دفق JSON ليتم استخدامه أثناء تجميع مستند.

```csharp
public class JsonDataSource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | إنشاء مصدر بيانات جديد ببيانات من دفق JSON باستخدام الخيارات الافتراضية لتحليل بيانات JSON. |
| [JsonDataSource](jsondatasource#constructor_2)(string) | إنشاء مصدر بيانات جديد ببيانات من ملف JSON باستخدام الخيارات الافتراضية لتحليل بيانات JSON. |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | إنشاء مصدر بيانات جديد ببيانات من دفق JSON باستخدام الخيارات المحددة لتحليل بيانات JSON. |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | إنشاء مصدر بيانات جديد ببيانات من ملف JSON باستخدام الخيارات المحددة لتحليل بيانات JSON. |

### ملاحظات

للوصول إلى بيانات الملف المقابل أو التدفق أثناء تجميع مستند ، قم بتمرير مثيل من هذه الفئة كـ مصدر بيانات إلى أحد[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .AssembleDocument التحميل الزائد .

في مستندات النموذج ، إذا كان عنصر JSON ذي المستوى الأعلى عبارة عن مصفوفة ، أ[`JsonDataSource`](../jsondatasource) يجب معاملة المثال be بنفس الطريقة كما لو كان ملفDataTable نموذج. إذا كان عنصر JSON عالي المستوى كائنًا ، فإن ملف[`JsonDataSource`](../jsondatasource) يجب معاملة المثيل بنفس الطريقة كما لو كان أDataRowنموذج. لمزيد من المعلومات ، راجع مرجع بناء جملة النموذج (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

في مستندات النموذج ، يمكنك التعامل مع القيم المكتوبة لعناصر JSON. للراحة ، يستبدل المحرك مجموعة لأنواع JSON البسيطة بالمجموعة التالية:

* Nullable
* Nullable
* Nullable
* Nullable
* String

يتعرف المحرك تلقائيًا على قيم الأنواع الإضافية بناءً على تمثيلات JSON الخاصة بهم.

لتجاوز السلوك الافتراضي لتحميل بيانات JSON ، قم بتهيئة وتمرير ملف[`JsonDataLoadOptions`](../jsondataloadoptions) example إلى مُنشئ هذه الفئة.

### أنظر أيضا

* مساحة الاسم [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* المجسم [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->