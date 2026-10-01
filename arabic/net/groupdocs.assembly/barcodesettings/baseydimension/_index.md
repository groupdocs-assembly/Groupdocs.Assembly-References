---
title: "BaseYDimension"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يحدد بُعد y الأساسي وهو أصغر ارتفاع لوحدة وحدات الباركود ثنائية الأبعاد. يُقاس بوحدة GraphicsUnitgroupdocs.assembly/barcodesettings/graphicsunit."
type: docs
weight: 20
url: /ar/net/groupdocs.assembly/barcodesettings/baseydimension/
---
## BarcodeSettings.BaseYDimension property

يحصل أو يحدد بُعد y الأساسي، أي أصغر ارتفاع لوحدة وحدات الباركود ثنائية الأبعاد. يُقاس بـ [`GraphicsUnit`](../graphicsunit).

```csharp
public float BaseYDimension { get; set; }
```

### ملاحظات

قد تتجاهل بعض أنواع الباركود (مثل Data Matrix) بُعد y وتستخدم بُعد x لكلا وحدتي العرض والارتفاع.

عند تطبيق مقياس الباركود عبر قالب، يتم حساب بُعد y الفعلي بناءً على بُعد y الأساسي وعامل المقياس.

### انظر أيضًا

* class [BarcodeSettings](../../barcodesettings)
* namespace [GroupDocs.Assembly](../../barcodesettings)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
