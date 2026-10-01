---
title: "DocumentTableColumnCollection"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يمثل مجموعة للقراءة فقط من كائنات DocumentTableColumn./documenttablecolumn لمثيل DocumentTable./documenttable معين."
type: docs
weight: 150
url: /ar/net/groupdocs.assembly.data/documenttablecolumncollection/
---
## DocumentTableColumnCollection class

يمثل مجموعة للقراءة فقط من كائنات [`DocumentTableColumn`](../documenttablecolumn) لمثيل [`DocumentTable`](../documenttable) معين.

```csharp
public class DocumentTableColumnCollection : IEnumerable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecolumncollection/count) { get; } | يحصل على العدد الإجمالي لكائنات [`DocumentTableColumn`](../documenttablecolumn) في المجموعة. |
| [Item](../../groupdocs.assembly.data/documenttablecolumncollection/item) { get; } | يحصل على مثيل [`DocumentTableColumn`](../documenttablecolumn) من المجموعة عند الفهرس المحدد. (2 فهارس) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains)(DocumentTableColumn) | يرجع قيمة تشير إلى ما إذا كانت هذه المجموعة تحتوي على العمود المحدد. |
| [Contains](../../groupdocs.assembly.data/documenttablecolumncollection/contains#contains_1)(string) | يرجع قيمة تشير إلى ما إذا كانت هذه المجموعة تحتوي على عمود بالاسم المحدد. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecolumncollection/getenumerator)() | يرجع كائن عداد للتنقل عبر كائنات [`DocumentTableColumn`](../documenttablecolumn) في هذه المجموعة. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof)(DocumentTableColumn) | يرجع فهرس العمود المحدد داخل هذه المجموعة. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecolumncollection/indexof#indexof_1)(string) | يرجع فهرس العمود الذي يحمل الاسم المحدد داخل هذه المجموعة. |

### ملاحظات

يتم ملء المجموعة تلقائيًا أثناء تحميل الجدول المقابل من مستند ولا يمكن تعديلها. ومع ذلك، يمكن تعديل خصائص كائنات [`DocumentTableColumn`](../documenttablecolumn) الموجودة داخل المجموعة.

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
