---
title: Name
second_title: GroupDocs.Assembly للحصول على مرجع .NET API
description: الحصول على أو تعيين اسم هذا الجدول المستخدم للوصول إلى بيانات الجدول في مستند نموذج تم تمريره إلى DocumentAssemblergroupdocs.assembly/documentassembler .
type: docs
weight: 40
url: /ar/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

الحصول على أو تعيين اسم هذا الجدول المستخدم للوصول إلى بيانات الجدول في مستند نموذج تم تمريره إلى [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler) .

```csharp
public string Name { get; set; }
```

### ملاحظات

إذا تمت قراءة اسم الجدول من مستند ، فسيتم تصحيح الاسم تلقائيًا حتى يكون صالحًا. ومع ذلك ، إذا تم تعيين اسم الجدول يدويًا من خلال هذه الخاصية وكان الاسم غير صالح ، فسيتم طرح استثناء.

يعتبر اسم الجدول صالحًا ، إذا تم استيفاء الشروط التالية:

* الاسم ليس فارغًا .
* الحرف الأول من الاسم هو حرف أو شرطة سفلية .
* باقي أحرف الاسم عبارة عن أحرف أو شرطات سفلية أو أرقام أو الأحرف التالية: "@" أو "#" أو "$" .
* المقابل[`DocumentTableSet`](../../documenttableset) لا يحتوي الكائن على[`DocumentTable`](../../documenttable) مثيل بنفس الاسم.

### أنظر أيضا

* class [DocumentTable](../../documenttable)
* مساحة الاسم [GroupDocs.Assembly.Data](../../documenttable)
* المجسم [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
