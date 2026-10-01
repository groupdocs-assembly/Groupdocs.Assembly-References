---
title: "DocumentTable"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يوفر إمكانية الوصول إلى بيانات جدول أو جدول بيانات واحد موجود في مستند خارجي لاستخدامه أثناء تجميع المستند."
type: docs
weight: 120
url: /ar/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

يوفر إمكانية الوصول إلى بيانات جدول واحد (أو جدول بيانات) موجود في مستند خارجي لاستخدامه أثناء تجميع المستند.

```csharp
public class DocumentTable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | إنشاء نسخة جديدة من هذه الفئة باستخدام [`DocumentTableOptions`](../documenttableoptions) الافتراضية. |
| [DocumentTable](documenttable#constructor_2)(string, int) | إنشاء نسخة جديدة من هذه الفئة باستخدام [`DocumentTableOptions`](../documenttableoptions) الافتراضية. |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | ينشئ مثيلًا جديدًا لهذه الفئة. |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | ينشئ مثيلًا جديدًا لهذه الفئة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | يحصل على مجموعة كائنات [`DocumentTableColumn`](../documenttablecolumn) التي تمثل أعمدة الجدول المقابل. |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | يحصل على الفهرس الأصلي صفر‑الأساس للجدول المقابل وفقًا للمستند المصدر. |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | يحصل أو يعيّن اسم هذا الجدول المستخدم للوصول إلى بيانات الجدول في مستند قالب يُمرّر إلى [`DocumentAssembler`](../../groupdocs.assembly/documentassembler). |

### ملاحظات

بالنسبة للمستندات ذات صيغ ملفات جدول البيانات، تمثل نسخة [`DocumentTable`](../documenttable) ورقة واحدة. بالنسبة للمستندات ذات الصيغ الأخرى، تمثل نسخة [`DocumentTable`](../documenttable) جدولًا واحدًا.

للوصول إلى بيانات الجدول المقابل أثناء تجميع مستند، مرّر نسخة من هذه الفئة كمصدر بيانات إلى أحد التحميلات الزائدة لـ [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

في مستندات القالب، يجب التعامل مع نسخة [`DocumentTable`](../documenttable) كما لو كانت نسخة DataTable. راجع مرجع بناء جملة القالب لمزيد من المعلومات.

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
