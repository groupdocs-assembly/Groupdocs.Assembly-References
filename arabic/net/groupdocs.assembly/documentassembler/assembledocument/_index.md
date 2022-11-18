---
title: AssembleDocument
second_title: GroupDocs.Assembly للحصول على مرجع .NET API
description: يقوم بتحميل مستند نموذج من مسار المصدر المحدد  ويملأ مستند القالب ببيانات من من المصادر الفردية أو المتعددة المحددة  ويخزن المستند الناتج إلى المسار الهدف باستخدام default LoadSaveOptionsgroupdocs.assembly/loadsaveoptions .
type: docs
weight: 50
url: /ar/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

يقوم بتحميل مستند نموذج من مسار المصدر المحدد ، ويملأ مستند القالب ببيانات من من المصادر الفردية أو المتعددة المحددة ، ويخزن المستند الناتج إلى المسار الهدف باستخدام default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sourcePath | String | المسار إلى مستند قالب ليتم ملؤه بالبيانات. |
| targetPath | String | المسار إلى وثيقة نتيجة. |
| dataSourceInfos | DataSourceInfo[] | يوفر معلومات عن كائنات مصدر البيانات التي سيتم استخدامها. |

### قيمة الإرجاع

إشارة تشير إلى نجاح تحليل مستند القالب. تكون العلامة التي تم إرجاعها منطقية فقط إذا كانت قيمة [`Options`](../options) تشمل الممتلكاتInlineErrorMessages خيار .

### أنظر أيضا

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* مساحة الاسم [GroupDocs.Assembly](../../documentassembler)
* المجسم [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

يقوم بتحميل مستند نموذج من مسار المصدر المحدد ، ويملأ مستند القالب ببيانات من من المصادر الفردية أو المتعددة المحددة ، ويخزن المستند الناتج إلى المسار الهدف باستخدام المعطى [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sourcePath | String | المسار إلى مستند قالب ليتم ملؤه بالبيانات. |
| targetPath | String | المسار إلى وثيقة نتيجة. |
| loadSaveOptions | LoadSaveOptions | يحدد خيارات إضافية لتحميل المستندات وحفظها. |
| dataSourceInfos | DataSourceInfo[] | يوفر معلومات عن كائنات مصدر البيانات التي سيتم استخدامها. |

### قيمة الإرجاع

إشارة تشير إلى نجاح تحليل مستند القالب. تكون العلامة التي تم إرجاعها منطقية فقط إذا كانت قيمة [`Options`](../options) تشمل الممتلكاتInlineErrorMessages خيار .

### أنظر أيضا

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* مساحة الاسم [GroupDocs.Assembly](../../documentassembler)
* المجسم [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

تحميل مستند نموذج من دفق المصدر المحدد ، وملء مستند القالب ببيانات من المصدر الفردي أو المتعدد المحدد ، وتخزين المستند الناتج إلى التدفق الهدف باستخدام default [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sourceStream | Stream | الدفق لقراءة مستند نموذج منه. |
| targetStream | Stream | تيار لكتابة وثيقة نتيجة. |
| dataSourceInfos | DataSourceInfo[] | يوفر معلومات عن كائنات مصدر البيانات التي سيتم استخدامها. |

### قيمة الإرجاع

إشارة تشير إلى نجاح تحليل مستند القالب. تكون العلامة التي تم إرجاعها منطقية فقط إذا كانت قيمة [`Options`](../options) تشمل الممتلكاتInlineErrorMessages خيار .

### أنظر أيضا

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* مساحة الاسم [GroupDocs.Assembly](../../documentassembler)
* المجسم [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

تحميل مستند نموذج من دفق المصدر المحدد ، وملء مستند القالب ببيانات من المصدر المحدد الفردي أو المتعدد ، وتخزين المستند الناتج إلى التدفق الهدف باستخدام المعطى [`LoadSaveOptions`](../../loadsaveoptions) .

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| sourceStream | Stream | الدفق لقراءة مستند نموذج منه. |
| targetStream | Stream | تيار لكتابة وثيقة نتيجة. |
| loadSaveOptions | LoadSaveOptions | يحدد خيارات إضافية لتحميل المستندات وحفظها. |
| dataSourceInfos | DataSourceInfo[] | يوفر معلومات عن كائنات مصدر البيانات التي سيتم استخدامها. |

### قيمة الإرجاع

إشارة تشير إلى نجاح تحليل مستند القالب. تكون العلامة التي تم إرجاعها منطقية فقط إذا كانت قيمة [`Options`](../options) تشمل الممتلكاتInlineErrorMessages خيار .

### أنظر أيضا

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* مساحة الاسم [GroupDocs.Assembly](../../documentassembler)
* المجسم [GroupDocs.Assembly](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
