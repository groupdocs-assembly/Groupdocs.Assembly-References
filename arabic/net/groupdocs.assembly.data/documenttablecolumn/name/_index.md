---
title: "الاسم"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يعيّن اسم هذا العمود المستخدم للوصول إلى بيانات الأعمدة في مستند قالب يُمرّر إلى DocumentAssemblergroupdocs.assembly/documentassembler."
type: docs
weight: 30
url: /ar/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

يحصل أو يعيّن اسم هذا العمود المستخدم للوصول إلى بيانات العمود في مستند قالب يُمرّر إلى [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler).

```csharp
public string Name { get; set; }
```

### ملاحظات

إذا تم قراءة اسم العمود من مستند (انظر [`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames))، يتم تصحيح الاسم تلقائيًا ليكون صالحًا. ومع ذلك، إذا تم تعيين اسم العمود يدويًا عبر هذه الخاصية وكان الاسم غير صالح، يتم إلقاء استثناء.

يُعتبر اسم العمود صالحًا إذا تم استيفاء الشروط التالية:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTable`](../../documenttable) object does not contain a [`DocumentTableColumn`](../../documenttablecolumn) instance with the same name.

### انظر أيضًا

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
