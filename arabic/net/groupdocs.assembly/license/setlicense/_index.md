---
title: "SetLicense"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "يمنح رخصة للمكوّن."
type: docs
weight: 30
url: /ar/net/groupdocs.assembly/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

يمنح رخصة للمكوّن.

```csharp
public void SetLicense(string licenseName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseName | String | يمكن أن يكون اسم ملف كامل أو قصير أو اسم مورد مضمّن. استخدم سلسلة فارغة للتبديل إلى وضع التقييم. |

### ملاحظات

يحاول العثور على الترخيص في المواقع التالية:

1. مسار صريح.

2. المجلد الذي يحتوي على تجميع مكوّن GroupDocs.

3. المجلد الذي يحتوي على تجميع استدعاء العميل.

4. المجلد الذي يحتوي على تجميع الدخول (التشغيل).

5. مورد مضمّن في تجميع استدعاء العميل.

### انظر أيضًا

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

---

## SetLicense(Stream) {#setlicense}

يمنح رخصة للمكوّن.

```csharp
public void SetLicense(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق يحتوي على الترخيص. |

### ملاحظات

استخدم هذه الطريقة لتحميل الترخيص من تدفق.

### انظر أيضًا

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
