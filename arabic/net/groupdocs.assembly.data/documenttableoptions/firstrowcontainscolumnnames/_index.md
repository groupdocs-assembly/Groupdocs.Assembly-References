---
title: "FirstRowContainsColumnNames"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب الحصول على أسماء الأعمدة من الصف المستخرج الأول لجدول المستند. القيمة الافتراضية هي false."
type: docs
weight: 20
url: /ar/net/groupdocs.assembly.data/documenttableoptions/firstrowcontainscolumnnames/
---
## DocumentTableOptions.FirstRowContainsColumnNames property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب الحصول على أسماء الأعمدة من الصف المستخرج الأول لجدول المستند. القيمة الافتراضية هي false.

```csharp
public bool FirstRowContainsColumnNames { get; set; }
```

### ملاحظات

إذا لم يتم تعيين أسماء الأعمدة لتُستخرج من الصف الأول المستخرج من جدول المستند، تُستخدم أسماء الأعمدة الافتراضية بدلاً من ذلك. بالنسبة للمستندات ذات صيغ ملفات جداول البيانات، تُعرّف أسماء الأعمدة الافتراضية كـ A، B، C، ... Z، AA، AB، وهكذا. بالنسبة للمستندات ذات صيغ ملفات أخرى، تُعرّف أسماء الأعمدة الافتراضية كـ Column1، Column2، Column3، وهكذا.

### انظر أيضًا

* class [DocumentTableOptions](../../documenttableoptions)
* namespace [GroupDocs.Assembly.Data](../../documenttableoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
