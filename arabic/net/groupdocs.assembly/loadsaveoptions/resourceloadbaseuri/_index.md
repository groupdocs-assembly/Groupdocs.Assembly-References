---
title: "ResourceLoadBaseUri"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يضبط عنوان URI أساسي لحل ملفات الموارد الخارجية من مسارات URI نسبية إلى مسارات مطلقة أثناء تحميل مستند قالب HTML ليتم تجميعه وحفظه بتنسيق غير HTML. القيمة الافتراضية هي سلسلة فارغة."
type: docs
weight: 20
url: /ar/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

يحصل أو يعيّن URI أساسي لحل عناوين ملفات الموارد الخارجية النسبية إلى عناوين مطلقة أثناء تحميل مستند قالب HTML ليُجمَّع ويُحفظ إلى تنسيق غير HTML. القيمة الافتراضية هي سلسلة فارغة.

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### ملاحظات

عند تحميل مستند HTML من ملف، يُستخدم المجلد المحتوي كعنوان URI أساسي بشكل افتراضي، وهو ما لا يمكن حدوثه عند تحميل مستند HTML من دفق. اضبط هذه الخاصية لتحديد عنوان URI أساسي عند تحميل مستند HTML من دفق أو لتجاوز عنوان URI الأساسي الافتراضي عند تحميل مستند HTML من ملف.

يتم تجاهل قيمة هذه الخاصية في الحالات التالية:

* An HTML document being loaded contains a BASE HTML element providing a base URI.
* An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

### انظر أيضًا

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
