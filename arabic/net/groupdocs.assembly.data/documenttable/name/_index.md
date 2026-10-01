---
title: "الاسم"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "الحصول أو تعيين اسم هذا الجدول المستخدم للوصول إلى بيانات الجداول في مستند قالب يتم تمريره إلى DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 40
url: /ar/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

الحصول أو تعيين اسم هذا الجدول المستخدم للوصول إلى بيانات الجدول في مستند قالب يتم تمريره إلى [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### ملاحظات

إذا تم قراءة اسم الجدول من مستند، يتم تصحيح الاسم تلقائيًا ليكون صالحًا. ومع ذلك، إذا تم تعيين اسم الجدول يدويًا عبر هذه الخاصية وكان الاسم غير صالح، يتم إلقاء استثناء.

يُعتبر اسم الجدول صالحًا إذا تم استيفاء الشروط التالية:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTableSet`](../../documenttableset) object does not contain a [`DocumentTable`](../../documenttable) instance with the same name.

### انظر أيضًا

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
