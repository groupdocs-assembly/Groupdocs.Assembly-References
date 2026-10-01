---
title: "إضافة"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يضيف كائن Type المحدد إلى المجموعة."
type: docs
weight: 20
url: /ar/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

يضيف كائن Type المحدد إلى المجموعة.

يرمي استثناء ArgumentException في الحالات التالية:

- *type* is null.

- *type* represents a void type.

- *type* represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

- *type* represents a generic type.

- *type* represents an array type.

- *type* has been added to the set already.

```csharp
public void Add(Type type)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | نوع | كائن Type للإضافة. |

### انظر أيضًا

* class [KnownTypeSet](../../knowntypeset)
* namespace [GroupDocs.Assembly](../../knowntypeset)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
