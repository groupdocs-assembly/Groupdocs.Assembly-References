---
title: "DocumentAssembler"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يوفر روتينات لملء مستندات القالب بالبيانات ومجموعة من الإعدادات للتحكم في هذه الروتينات."
type: docs
weight: 40
url: /ar/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

يوفر روتينات لملء مستندات القالب بالبيانات ومجموعة من الإعدادات للتحكم في هذه الروتينات.

```csharp
public class DocumentAssembler
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DocumentAssembler](documentassembler)() | يُهيئ نسخة جديدة من هذه الفئة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | يحصل على مجموعة من الإعدادات التي تتحكم في توليد الباركود أثناء تجميع مستند. |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | يحصل على مجموعة غير مرتبة (أي مجموعة من العناصر الفريدة) تحتوي على كائنات Type التي يمكن استخدام أسمائها المؤهلة بالكامل أو جزئياً داخل قوالب المستند التي يعالجها هذا المثيل من المجمع لاستدعاء الأعضاء الثابتة للأنواع المقابلة، وإجراء تحويلات النوع، إلخ. |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | يحصل على أو يعيّن مجموعة من العلامات التي تتحكم في سلوك هذا [`DocumentAssembler`](../documentassembler) المثيل أثناء تجميع مستند. |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت استدعاءات أعضاء النوع المخصص التي تُجرى عبر واجهة برمجة تطبيقات الانعكاس محسّنة باستخدام إنشاء فئة ديناميكية أم لا. القيمة الافتراضية هي true. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | يقوم بتحميل مستند قالب من تدفق المصدر المحدد، يملأ مستند القالب بالبيانات من المصدر (المصادر) المفرد أو المتعدد المحدد، ويخزن مستند النتيجة إلى تدفق الهدف باستخدام الإعدادات الافتراضية [`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | يقوم بتحميل مستند قالب من مسار المصدر المحدد، يملأ مستند القالب بالبيانات من المصدر (المصادر) المفرد أو المتعدد المحدد، ويخزن مستند النتيجة إلى المسار الهدف باستخدام الإعدادات الافتراضية [`LoadSaveOptions`](../loadsaveoptions). |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | يقوم بتحميل مستند قالب من تدفق المصدر المحدد، يملأ مستند القالب بالبيانات من المصدر (المصادر) المفرد أو المتعدد المحدد، ويخزن مستند النتيجة إلى تدفق الهدف باستخدام [`LoadSaveOptions`](../loadsaveoptions) المحدد. |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | يقوم بتحميل مستند قالب من مسار المصدر المحدد، يملأ مستند القالب بالبيانات من المصدر (المصادر) المفرد أو المتعدد المحدد، ويخزن مستند النتيجة إلى المسار الهدف باستخدام [`LoadSaveOptions`](../loadsaveoptions) المحدد. |

### انظر أيضًا

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
