---
title: "JsonDataLoadOptions"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يمثل خيارات لتحليل بيانات JSON."
type: docs
weight: 220
url: /ar/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

يمثل خيارات لتحليل بيانات JSON.

```csharp
public class JsonDataLoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | يُهيئ نسخة جديدة من هذه الفئة باستخدام الخيارات الافتراضية. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | يحصل أو يعيّن علامة تشير إلى ما إذا كان مصدر البيانات المُنشأ سيحتوي دائمًا على كائن لجذر JSON. إذا كان جذر JSON يحتوي على خاصية مركبة واحدة، فلن يتم إنشاء مثل هذا الكائن افتراضيًا. |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | يحصل أو يعيّن صيغًا دقيقة لتحليل قيم التاريخ والوقت في JSON أثناء تحميل JSON. القيمة الافتراضية هي **null**. |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | يحصل أو يعيّن وضعًا لتحليل القيم البسيطة في JSON (null، boolean، number، integer، و string) أثناء تحميل JSON. هذا الوضع لا يؤثر على تحليل قيم التاريخ والوقت. القيمة الافتراضية هي Loose. |

### ملاحظات

يمكن تمرير نسخة من هذه الفئة إلى مُنشئات [`JsonDataSource`](../jsondatasource).

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
