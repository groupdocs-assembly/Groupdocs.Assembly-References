---
title: "BarcodeSettings"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يمثل مجموعة من الإعدادات التي تتحكم في توليد الباركود أثناء تجميع مستند."
type: docs
weight: 10
url: /ar/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

يمثل مجموعة من الإعدادات التي تتحكم في توليد الباركود أثناء تجميع مستند.

```csharp
public class BarcodeSettings
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | يحصل أو يعيّن البُعد x الأساسي، أي أصغر عرض لوحدة أشرطة ومسافات الباركود. يُقاس بـ [`GraphicsUnit`](./graphicsunit). |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | يحصل أو يعيّن البُعد y الأساسي، أي أصغر ارتفاع لوحدة وحدات الباركود ثنائية الأبعاد. يُقاس بـ [`GraphicsUnit`](./graphicsunit). |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | يحصل أو يعيّن وحدة الرسومات المستخدمة لقياس [`BaseXDimension`](./basexdimension) و[`BaseYDimension`](./baseydimension). القيمة الافتراضية هي Millimeter. |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | يحصل أو يعيّن الدقة الأفقية والرأسية لصورة الباركود التي يتم إنشاؤها. تُقاس بالنقاط في البوصة. القيمة الافتراضية هي 96. |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تصحيح قيمة الباركود غير الصالحة تلقائيًا (إن أمكن) لتتناسب مع مواصفات الباركود أو يجب رمي استثناء للإشارة إلى الخطأ. القيمة الافتراضية هي true. |

### انظر أيضًا

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
