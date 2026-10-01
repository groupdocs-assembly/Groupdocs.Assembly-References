---
title: "SaveFormat"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يعيّن تنسيق ملف لحفظ مستند مُجمَّع إليه. غير محدد هو الافتراضي."
type: docs
weight: 40
url: /ar/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

يحصل أو يعيّن تنسيق ملف لحفظ مستند مُجمَّع إليه. غير محدد هو الافتراضي.

```csharp
public FileFormat SaveFormat { get; set; }
```

### ملاحظات

عند عدم تحديد قيمة هذه الخاصية، يتصرف [`DocumentAssembler`](../../documentassembler) كما يلي:

- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

احذر أنه ليس من الممكن دائمًا حفظ مستند مُجمّع إلى أي تنسيق ملف باستخدام GroupDocs.Assembly. على سبيل المثال، لا يمكن حفظ مستند تم تحميله من تنسيق معالجة نصوص (مثل DOCX) إلى تنسيق جدول بيانات (مثل XLSX). للحصول على مزيد من المعلومات حول التركيبات الممكنة لتنسيقات التحميل والحفظ المدعومة من قبل GroupDocs.Assembly، يرجى مراجعة وثائق GroupDocs.Assembly على الإنترنت.

### انظر أيضًا

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
