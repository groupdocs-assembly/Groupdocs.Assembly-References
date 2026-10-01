---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يوفر إمكانية الوصول إلى بيانات ملف XML أو تدفق لاستخدامها أثناء تجميع المستند."
type: docs
weight: 260
url: /ar/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

يوفر إمكانية الوصول إلى بيانات ملف XML أو تدفق لاستخدامها أثناء تجميع المستند.

```csharp
public class XmlDataSource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | ينشئ مصدر بيانات جديد بالبيانات من تدفق XML باستخدام الخيارات الافتراضية لتحميل بيانات XML. |
| [XmlDataSource](xmldatasource#constructor_4)(string) | ينشئ مصدر بيانات جديد بالبيانات من ملف XML باستخدام الخيارات الافتراضية لتحميل بيانات XML. |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | ينشئ مصدر بيانات جديد بالبيانات من تدفق XML باستخدام تدفق تعريف مخطط XML. تُستخدم الخيارات الافتراضية لتحميل بيانات XML. |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | إنشاء مصدر بيانات جديد باستخدام البيانات من تدفق XML باستخدام الخيارات المحددة لتحميل بيانات XML. |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | إنشاء مصدر بيانات جديد باستخدام البيانات من ملف XML باستخدام ملف تعريف مخطط XML. تُستخدم الخيارات الافتراضية لتحميل بيانات XML. |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | إنشاء مصدر بيانات جديد باستخدام البيانات من ملف XML باستخدام الخيارات المحددة لتحميل بيانات XML. |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | إنشاء مصدر بيانات جديد باستخدام البيانات من تدفق XML باستخدام تدفق تعريف مخطط XML. تُستخدم الخيارات المحددة لتحميل بيانات XML. |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | إنشاء مصدر بيانات جديد باستخدام البيانات من ملف XML باستخدام ملف تعريف مخطط XML. تُستخدم الخيارات المحددة لتحميل بيانات XML. |

### ملاحظات

للوصول إلى بيانات الملف أو التدفق المقابل أثناء تجميع مستند، مرّر مثيلًا من هذه الفئة كمصدر بيانات إلى أحد إصدارات الدالة [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

في مستندات القالب، إذا كان عنصر XML من المستوى الأعلى يحتوي فقط على قائمة من العناصر من نفس النوع، يجب التعامل مع كائن [`XmlDataSource`](../xmldatasource) كما لو كان كائن DataTable. وإلا، يجب التعامل مع كائن [`XmlDataSource`](../xmldatasource) كما لو كان كائن DataRow. لمزيد من المعلومات، راجع مرجع بناء جملة القالب (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources).

عند تمرير تعريف مخطط XML إلى مُنشئ هذه الفئة، يتم تحديد أنواع البيانات لقيم عناصر XML البسيطة والسمات وفقًا للمخطط. لذا في مستندات القالب، يمكنك العمل بالقيم ذات النوع بدلاً من السلاسل النصية فقط.

عند عدم تمرير تعريف مخطط XML إلى مُنشئ هذه الفئة، يتم تحديد أنواع البيانات لقيم عناصر XML البسيطة والسمات تلقائيًا بناءً على تمثيلها النصي. لذا في مستندات القالب، يمكنك أيضًا العمل بالقيم ذات النوع في هذه الحالة. يستطيع المحرك التعرف تلقائيًا على القيم من الأنواع التالية:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

لاحظ أنه لكي يعمل التعرف التلقائي على أنواع البيانات، يجب تشكيل التمثيلات النصية لقيم عناصر XML البسيطة والسمات باستخدام إعدادات الثقافة الثابتة.

لتجاوز السلوك الافتراضي لتحميل بيانات XML، قم بتهيئة وتمرير كائن [`XmlDataLoadOptions`](../xmldataloadoptions) إلى مُنشئ هذه الفئة.

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
