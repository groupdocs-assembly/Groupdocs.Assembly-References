---
title: "AssembleDocument"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يقوم بتحميل مستند قالب من مسار المصدر المحدد، ويملأ مستند القالب بالبيانات من المصدر (المصدر) المفرد أو المتعدد المحدد، ثم يخزن مستند النتيجة إلى مسار الهدف باستخدام الإعدادات الافتراضية LoadSaveOptionsgroupdocs.assembly/loadsaveoptions."
type: docs
weight: 50
url: /ar/net/groupdocs.assembly/documentassembler/assembledocument/
---
## AssembleDocument(string, string, params DataSourceInfo[]) {#assembledocument_2}

يقوم بتحميل مستند قالب من مسار المصدر المحدد، ويملأ مستند القالب بالبيانات من المصدر (المصادر) المفرد أو المتعدد المحدد، ثم يخزن مستند النتيجة إلى مسار الهدف باستخدام الإعدادات الافتراضية [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, 
    params DataSourceInfo[] dataSourceInfos)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | المسار إلى مستند القالب الذي سيُملأ بالبيانات. |
| targetPath | String | المسار إلى مستند النتيجة. |
| dataSourceInfos | DataSourceInfo[] | يوفر معلومات حول كائنات مصدر البيانات التي سيتم استخدامها. |

### قيمة الإرجاع

علامة تشير إلى ما إذا كان تحليل مستند القالب قد نجح. تكون العلامة المرجعة ذات معنى فقط إذا كان قيمة خاصية [`Options`](../options) تتضمن خيار InlineErrorMessages.

### انظر أيضًا

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(string, string, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_3}

يقوم بتحميل مستند قالب من مسار المصدر المحدد، ويملأ مستند القالب بالبيانات من المصدر (المصادر) المفرد أو المتعدد المحدد، ثم يخزن مستند النتيجة إلى مسار الهدف باستخدام [`LoadSaveOptions`](../../loadsaveoptions) المحدد.

```csharp
public bool AssembleDocument(string sourcePath, string targetPath, LoadSaveOptions loadSaveOptions, 
    params DataSourceInfo[] dataSourceInfos)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | المسار إلى مستند القالب الذي سيُملأ بالبيانات. |
| targetPath | String | المسار إلى مستند النتيجة. |
| loadSaveOptions | LoadSaveOptions | يحدد خيارات إضافية لتحميل المستند وحفظه. |
| dataSourceInfos | DataSourceInfo[] | يوفر معلومات حول كائنات مصدر البيانات التي سيتم استخدامها. |

### قيمة الإرجاع

علامة تشير إلى ما إذا كان تحليل مستند القالب قد نجح. تكون العلامة المرجعة ذات معنى فقط إذا كان قيمة خاصية [`Options`](../options) تتضمن خيار InlineErrorMessages.

### انظر أيضًا

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, params DataSourceInfo[]) {#assembledocument}

يقوم بتحميل مستند قالب من الدفق المصدر المحدد، ويملأ مستند القالب بالبيانات من المصدر (المصادر) المفرد أو المتعدد المحدد، ثم يخزن مستند النتيجة إلى الدفق الهدف باستخدام الإعدادات الافتراضية [`LoadSaveOptions`](../../loadsaveoptions).

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    params DataSourceInfo[] dataSourceInfos)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceStream | Stream | الدفق لقراءة مستند القالب منه. |
| targetStream | Stream | الدفق لكتابة مستند النتيجة. |
| dataSourceInfos | DataSourceInfo[] | يوفر معلومات حول كائنات مصدر البيانات التي سيتم استخدامها. |

### قيمة الإرجاع

علامة تشير إلى ما إذا كان تحليل مستند القالب قد نجح. تكون العلامة المرجعة ذات معنى فقط إذا كان قيمة خاصية [`Options`](../options) تتضمن خيار InlineErrorMessages.

### انظر أيضًا

* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

---

## AssembleDocument(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) {#assembledocument_1}

يقوم بتحميل مستند قالب من الدفق المصدر المحدد، ويملأ مستند القالب بالبيانات من المصدر (المصادر) المفرد أو المتعدد المحدد، ثم يخزن مستند النتيجة إلى الدفق الهدف باستخدام [`LoadSaveOptions`](../../loadsaveoptions) المحدد.

```csharp
public bool AssembleDocument(Stream sourceStream, Stream targetStream, 
    LoadSaveOptions loadSaveOptions, params DataSourceInfo[] dataSourceInfos)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceStream | Stream | الدفق لقراءة مستند القالب منه. |
| targetStream | Stream | الدفق لكتابة مستند النتيجة. |
| loadSaveOptions | LoadSaveOptions | يحدد خيارات إضافية لتحميل المستند وحفظه. |
| dataSourceInfos | DataSourceInfo[] | يوفر معلومات حول كائنات مصدر البيانات التي سيتم استخدامها. |

### قيمة الإرجاع

علامة تشير إلى ما إذا كان تحليل مستند القالب قد نجح. تكون العلامة المرجعة ذات معنى فقط إذا كان قيمة خاصية [`Options`](../options) تتضمن خيار InlineErrorMessages.

### انظر أيضًا

* class [LoadSaveOptions](../../loadsaveoptions)
* class [DataSourceInfo](../../datasourceinfo)
* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
