---
title: BarcodeSettings
second_title: GroupDocs.Assembly للحصول على مرجع .NET API
description: يمثل مجموعة من الإعدادات التي تتحكم في إنشاء الرمز الشريطي أثناء تجميع مستند.
type: docs
weight: 10
url: /ar/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

يمثل مجموعة من الإعدادات التي تتحكم في إنشاء الرمز الشريطي أثناء تجميع مستند.

```csharp
public class BarcodeSettings
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | الحصول على أو تحديد بُعد x أساسي ، أي أصغر عرض لوحدة أشرطة ومسافات الباركود.[`GraphicsUnit`](./graphicsunit) . |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | الحصول على أو تحديد بُعد ص أساسي ، أي أصغر ارتفاع لوحدة وحدات الباركود ثنائية الأبعاد.[`GraphicsUnit`](./graphicsunit) . |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | الحصول على أو تعيين وحدة رسومات مستخدمة للقياس[`BaseXDimension`](./basexdimension) و[`BaseYDimension`](./baseydimension) . القيمة الافتراضية هيMillimeter . |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | الحصول على أو تعيين الدقة الأفقية والرأسية لصورة الرمز الشريطي التي يتم إنشاؤها. تقاس بالنقاط لكل بوصة. القيمة الافتراضية هي 96. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب تصحيح قيمة الرمز الشريطي غير الصالحة تلقائيًا (إن أمكن) لتلائم مواصفات الباركود أو يجب طرح استثناء للإشارة إلى الخطأ. القيمة الافتراضية هي true . |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Assembly](../../groupdocs.assembly)
* المجسم [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
