---
title: "DocumentTableSet"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يوفر الوصول إلى بيانات جداول أو جداول بيانات متعددة موجودة في مستند خارجي لاستخدامها أثناء تجميع المستند. كما يتيح تعريف علاقات الأب-ابن للجداول في المستند مما يبسط الوصول إلى البيانات المرتبطة داخل مستندات القالب."
type: docs
weight: 200
url: /ar/net/groupdocs.assembly.data/documenttableset/
---
## DocumentTableSet class

يوفر إمكانية الوصول إلى بيانات جداول متعددة (أو جداول بيانات) موجودة في مستند خارجي لاستخدامها أثناء تجميع المستند. كما يتيح تعريف علاقات أب-ابن لجداول المستند مما يبسط الوصول إلى البيانات المرتبطة داخل مستندات القالب.

```csharp
public class DocumentTableSet
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DocumentTableSet](documenttableset#constructor)(Stream) | ينشئ مثيلًا جديدًا لهذه الفئة يحمل جميع الجداول من مستند باستخدام الخيارات الافتراضية [`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTableSet](documenttableset#constructor_2)(string) | ينشئ مثيلًا جديدًا لهذه الفئة يحمل جميع الجداول من مستند باستخدام الخيارات الافتراضية [`DocumentTableOptions`](../documenttableoptions). |
| [DocumentTableSet](documenttableset#constructor_1)(Stream, IDocumentTableLoadHandler) | ينشئ مثيلًا جديدًا لهذه الفئة. |
| [DocumentTableSet](documenttableset#constructor_3)(string, IDocumentTableLoadHandler) | ينشئ مثيلًا جديدًا لهذه الفئة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Relations](../../groupdocs.assembly.data/documenttableset/relations) { get; } | يحصل على مجموعة العلاقات بين الأب والابن المعرفة لجداول المستند في هذه المجموعة. |
| [Tables](../../groupdocs.assembly.data/documenttableset/tables) { get; } | يحصل على مجموعة كائنات [`DocumentTable`](../documenttable) التي تمثل جداول هذه المجموعة. |

### ملاحظات

بالنسبة للمستندات ذات صيغ ملفات جداول البيانات، يمثل كائن [`DocumentTableSet`](../documenttableset) مجموعة من الأوراق. بالنسبة للمستندات ذات الصيغ الأخرى، يمثل كائن [`DocumentTableSet`](../documenttableset) مجموعة من الجداول.

للوصول إلى بيانات الجداول المقابلة أثناء تجميع المستند، مرر مثيلًا لهذه الفئة كمصدر بيانات إلى إحدى التحميلات الزائدة لـ [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument.

في مستندات القالب، يجب التعامل مع كائن [`DocumentTableSet`](../documenttableset) كما لو كان كائن DataSet. راجع مرجع صياغة القالب لمزيد من المعلومات.

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
