---
title: "DocumentTableCollection"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يمثل مجموعة للقراءة فقط من كائنات DocumentTable./documenttable الخاصة بمثيل DocumentTableSet./documenttableset معين."
type: docs
weight: 130
url: /ar/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

يمثل مجموعة للقراءة فقط من كائنات [`DocumentTable`](../documenttable) الخاصة بمثيل [`DocumentTableSet`](../documenttableset) معين.

```csharp
public class DocumentTableCollection : IEnumerable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | الحصول على العدد الإجمالي لكائنات [`DocumentTable`](../documenttable) في المجموعة. |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | الحصول على نسخة [`DocumentTable`](../documenttable) من المجموعة عند الفهرس المحدد. (2 indexers) |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | إرجاع قيمة تشير إلى ما إذا كانت هذه المجموعة تحتوي على الجدول المحدد. |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | إرجاع قيمة تشير إلى ما إذا كانت هذه المجموعة تحتوي على جدول بالاسم المحدد. |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | إرجاع عداد للتكرار عبر كائنات [`DocumentTable`](../documenttable) في هذه المجموعة. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | إرجاع الفهرس للجدول المحدد داخل هذه المجموعة. |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | إرجاع الفهرس لجدول بالاسم المحدد داخل هذه المجموعة. |

### ملاحظات

يتم ملء المجموعة تلقائيًا أثناء تحميل الجداول المقابلة من مستند ولا يمكن تعديلها. ومع ذلك، يمكن تعديل خصائص كائنات [`DocumentTable`](../documenttable) الموجودة داخل المجموعة.

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
