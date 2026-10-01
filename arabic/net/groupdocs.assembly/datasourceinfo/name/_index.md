---
title: "الاسم"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يحصل أو يعيّن اسم كائن مصدر البيانات الذي سيُستخدم للوصول إلى كائن مصدر البيانات في مستند القالب."
type: docs
weight: 30
url: /ar/net/groupdocs.assembly/datasourceinfo/name/
---
## DataSourceInfo.Name property

يحصل أو يعيّن اسم كائن مصدر البيانات الذي سيُستخدم للوصول إلى كائن مصدر البيانات في مستند القالب.

```csharp
public string Name { get; set; }
```

### ملاحظات

عند تحديد اسم كائن مصدر البيانات، يمكنك الوصول إلى كائن مصدر البيانات وأعضائه في مستند القالب باستخدام الاسم.

عند كون اسم كائن مصدر البيانات فارغًا أو null، لا يزال بإمكانك الوصول إلى أعضاء كائن مصدر البيانات في مستند القالب باستخدام وصول أعضاء كائن السياق (انظر مرجع صsyntax القالب لمزيد من المعلومات)، لكن لا يمكنك الوصول إلى كائن مصدر البيانات نفسه.

عند تمرير عدة مثيلات من [`DataSourceInfo`](../../datasourceinfo) إلى [`DocumentAssembler`](../../documentassembler)، يمكن أن يكون اسم كائن مصدر البيانات الأول فقط null أو فارغ. يجب تحديد أسماء البقية وتكون فريدة.

### انظر أيضًا

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
