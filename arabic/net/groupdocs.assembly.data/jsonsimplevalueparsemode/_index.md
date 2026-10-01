---
title: "JsonSimpleValueParseMode"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحدد وضعًا لتحليل القيم البسيطة في JSON مثل null و boolean و number و integer و string أثناء تحميل JSON. هذا الوضع لا يؤثر على تحليل قيم datetime."
type: docs
weight: 240
url: /ar/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

يحدد وضعًا لتحليل القيم البسيطة في JSON (null، boolean، number، integer، وstring) أثناء تحميل JSON. هذا الوضع لا يؤثر على تحليل قيم التاريخ والوقت.

```csharp
public enum JsonSimpleValueParseMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Loose | `0` | يحدد الوضع الذي يتم فيه تحديد أنواع القيم البسيطة في JSON عند تحليل تمثيلها النصي. على سبيل المثال، يتم تحديد نوع 'prop' من مقتطف JSON '{ prop: "123" }' كعدد صحيح في هذا الوضع. |
| Strict | `1` | يحدد الوضع الذي يتم فيه تحديد أنواع القيم البسيطة في JSON من تدوين JSON نفسه. على سبيل المثال، يتم تحديد نوع 'prop' من مقتطف JSON '{ prop: "123" }' كسلسلة نصية في هذا الوضع. |

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
