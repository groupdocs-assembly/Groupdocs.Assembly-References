---
title: "ExactDateTimeParseFormats"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يعيّن صيغًا دقيقة لتحليل قيم datetime في JSON أثناء تحميل JSON. القيمة الافتراضية هي null."
type: docs
weight: 30
url: /ar/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

يحصل أو يعيّن صيغًا دقيقة لتحليل قيم التاريخ والوقت في JSON أثناء تحميل JSON. القيمة الافتراضية هي **null**.

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### ملاحظات

السلاسل المشفرة باستخدام تنسيق تاريخ-وقت Microsoft® JSON (على سبيل المثال، "\/Date(1224043200000)\/" ) يتم دائمًا التعرف عليها كقيم تاريخ-وقت بغض النظر عن قيمة هذه الخاصية. تحدد الخاصية صيغًا إضافية تُستخدم أثناء تحليل قيم التاريخ-الوقت من السلاسل بالطريقة التالية:

* When `ExactDateTimeParseFormats` is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
* When `ExactDateTimeParseFormats` contains strings, they are used as additional date-time formats utilizing the current culture.
* When `ExactDateTimeParseFormats` is empty, no additional date-time formats are used.

### انظر أيضًا

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* namespace [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
