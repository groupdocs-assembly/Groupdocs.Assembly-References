---
title: "ResourceSaveFolder"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يحدد مسارًا لمجلد لتخزين ملفات الموارد الخارجية أثناء حفظ مستند مُجمّع تم تحميله من تنسيق غير HTML إلى HTML. القيمة الافتراضية هي سلسلة فارغة."
type: docs
weight: 30
url: /ar/net/groupdocs.assembly/loadsaveoptions/resourcesavefolder/
---
## LoadSaveOptions.ResourceSaveFolder property

يحصل أو يعيّن مسار إلى مجلد لتخزين ملفات الموارد الخارجية أثناء حفظ مستند مُجمَّع تم تحميله من تنسيق غير HTML إلى HTML. القيمة الافتراضية هي سلسلة فارغة.

```csharp
public string ResourceSaveFolder { get; set; }
```

### ملاحظات

بشكل افتراضي، عند حفظ مستند مُجمّع إلى ملف HTML، يتم تخزين ملفات الموارد الخارجية في مجلد يحمل نفس اسم ملف HTML بدون الامتداد مضافًا إليه اللاحقة "_files". يقع هذا المجلد في نفس المجلد الذي يحتوي على ملف HTML. ومع ذلك، لا يمكن القيام بذلك عند حفظ المستند المُجمّع إلى تدفق HTML. قم بتعيين هذه الخاصية لتحديد مسار لمجلد لتخزين ملفات الموارد الخارجية عند حفظ المستند المُجمّع إلى تدفق HTML أو لتجاوز المجلد الافتراضي عند حفظ المستند المُجمّع إلى ملف HTML.

يتم تجاهل قيمة هذه الخاصية إذا كان المستند المُجمّع الذي يتم حفظه إلى HTML قد تم تحميله من HTML أيضًا (لا يتم تخزين ملفات الموارد الخارجية ولا يتم تعديل الروابط إليها).

### انظر أيضًا

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
