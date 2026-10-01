---
title: "UseReflectionOptimization"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يعيّن قيمة تشير إلى ما إذا كانت استدعاءات أعضاء النوع المخصص التي تُجرى عبر واجهة برمجة تطبيقات الانعكاس محسّنة باستخدام إنشاء فئة ديناميكية أم لا. القيمة الافتراضية هي true."
type: docs
weight: 60
url: /ar/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

يحصل أو يعيّن قيمة تشير إلى ما إذا كانت استدعاءات أعضاء النوع المخصص التي تُجرى عبر واجهة برمجة تطبيقات الانعكاس محسّنة باستخدام إنشاء فئة ديناميكية أم لا. القيمة الافتراضية هي true.

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### ملاحظات

هناك بعض السيناريوهات التي يُفضَّل فيها تعطيل هذا التحسين. على سبيل المثال، إذا كنت تتعامل مع مجموعات صغيرة من عناصر البيانات طوال الوقت، فإن تكلفة إنشاء الفئات الديناميكية قد تكون أكثر وضوحًا من تكلفة استدعاءات API الانعكاس المباشر.

### انظر أيضًا

* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
