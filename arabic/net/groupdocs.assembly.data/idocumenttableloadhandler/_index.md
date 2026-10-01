---
title: "IDocumentTableLoadHandler"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يتجاوز التحميل الافتراضي لكائنات DocumentTable./documenttable أثناء إنشاء مثيل DocumentTableSet./documenttableset."
type: docs
weight: 210
url: /ar/net/groupdocs.assembly.data/idocumenttableloadhandler/
---
## IDocumentTableLoadHandler interface

يتجاوز التحميل الافتراضي لكائنات [`DocumentTable`](../documenttable) أثناء إنشاء مثيل [`DocumentTableSet`](../documenttableset).

```csharp
public interface IDocumentTableLoadHandler
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Handle](../../groupdocs.assembly.data/idocumenttableloadhandler/handle)(DocumentTableLoadArgs) | يتجاوز التحميل الافتراضي لكائن [`DocumentTable`](../documenttable) معين أثناء إنشاء مثيل [`DocumentTableSet`](../documenttableset). |

### ملاحظات

نفّذ هذه الواجهة إذا كنت تريد إلغاء تحميل كائنات [`DocumentTable`](../documenttable) محددة أو توفير [`DocumentTableOptions`](../documenttableoptions) معينة للجداول التي يتم تحميلها.

### انظر أيضًا

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
