---
title: "محسوب"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يوفر طرقًا للعمل مع الترخيص القائم على القياس."
type: docs
weight: 90
url: /ar/net/groupdocs.assembly/metered/
---
## Metered class

يوفر طرقًا للعمل مع الترخيص القائم على القياس.

```csharp
public class Metered
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered)() | ينشئ مثيلًا جديدًا لهذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | يفعل الترخيص المقاس للمكوّن عن طريق تحديد المفاتيح العامة والخاصة المقاسة المناسبة. |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | يعيد العدد الحالي المستهلك من الاعتمادات. |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | يعيد العدد الحالي المستهلك من الميجابايت. |

### أمثلة

في هذا المثال، تم محاولة ضبط المفاتيح العامة والخاصة المقاسة:

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### انظر أيضًا

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
