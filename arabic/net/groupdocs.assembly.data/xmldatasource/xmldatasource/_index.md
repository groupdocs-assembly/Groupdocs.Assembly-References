---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly لـ .NET مرجع API"
description: "ينشئ مصدر بيانات جديد بالبيانات من ملف XML باستخدام الخيارات الافتراضية لتحميل بيانات XML."
type: docs
weight: 10
url: /ar/net/groupdocs.assembly.data/xmldatasource/xmldatasource/
---
## XmlDataSource(string) {#constructor_4}

ينشئ مصدر بيانات جديد بالبيانات من ملف XML باستخدام الخيارات الافتراضية لتحميل بيانات XML.

```csharp
public XmlDataSource(string xmlPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| xmlPath | String | المسار إلى ملف XML الذي سيُستخدم كمصدر للبيانات. |

### انظر أيضًا

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream) {#constructor}

ينشئ مصدر بيانات جديد بالبيانات من تدفق XML باستخدام الخيارات الافتراضية لتحميل بيانات XML.

```csharp
public XmlDataSource(Stream xmlStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| xmlStream | Stream | تدفق بيانات XML الذي سيُستخدم كمصدر للبيانات. |

### انظر أيضًا

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string) {#constructor_6}

إنشاء مصدر بيانات جديد باستخدام البيانات من ملف XML باستخدام ملف تعريف مخطط XML. تُستخدم الخيارات الافتراضية لتحميل بيانات XML.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| xmlPath | String | المسار إلى ملف XML الذي سيُستخدم كمصدر للبيانات. |
| xmlSchemaPath | String | المسار إلى ملف تعريف مخطط XML الذي يوفر المخطط لملف XML. |

### انظر أيضًا

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream) {#constructor_2}

ينشئ مصدر بيانات جديد بالبيانات من تدفق XML باستخدام تدفق تعريف مخطط XML. تُستخدم الخيارات الافتراضية لتحميل بيانات XML.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| xmlStream | Stream | تدفق بيانات XML الذي سيُستخدم كمصدر للبيانات. |
| xmlSchemaStream | Stream | تدفق تعريف مخطط XML الذي يوفر المخطط لبيانات XML. |

### انظر أيضًا

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, XmlDataLoadOptions) {#constructor_5}

إنشاء مصدر بيانات جديد باستخدام البيانات من ملف XML باستخدام الخيارات المحددة لتحميل بيانات XML.

```csharp
public XmlDataSource(string xmlPath, XmlDataLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| xmlPath | String | المسار إلى ملف XML الذي سيُستخدم كمصدر للبيانات. |
| options | XmlDataLoadOptions | خيارات تحميل بيانات XML. |

### انظر أيضًا

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, XmlDataLoadOptions) {#constructor_1}

إنشاء مصدر بيانات جديد باستخدام البيانات من تدفق XML باستخدام الخيارات المحددة لتحميل بيانات XML.

```csharp
public XmlDataSource(Stream xmlStream, XmlDataLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| xmlStream | Stream | تدفق بيانات XML الذي سيُستخدم كمصدر للبيانات. |
| options | XmlDataLoadOptions | خيارات تحميل بيانات XML. |

### انظر أيضًا

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string, XmlDataLoadOptions) {#constructor_7}

إنشاء مصدر بيانات جديد باستخدام البيانات من ملف XML باستخدام ملف تعريف مخطط XML. تُستخدم الخيارات المحددة لتحميل بيانات XML.

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath, XmlDataLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| xmlPath | String | المسار إلى ملف XML الذي سيُستخدم كمصدر للبيانات. |
| xmlSchemaPath | String | المسار إلى ملف تعريف مخطط XML الذي يوفر المخطط لملف XML. |
| options | XmlDataLoadOptions | خيارات تحميل بيانات XML. |

### انظر أيضًا

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream, XmlDataLoadOptions) {#constructor_3}

إنشاء مصدر بيانات جديد باستخدام البيانات من تدفق XML باستخدام تدفق تعريف مخطط XML. تُستخدم الخيارات المحددة لتحميل بيانات XML.

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream, XmlDataLoadOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| xmlStream | Stream | تدفق بيانات XML الذي سيُستخدم كمصدر للبيانات. |
| xmlSchemaStream | Stream | تدفق تعريف مخطط XML الذي يوفر المخطط لبيانات XML. |
| options | XmlDataLoadOptions | خيارات تحميل بيانات XML. |

### انظر أيضًا

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.Assembly.dll -->
