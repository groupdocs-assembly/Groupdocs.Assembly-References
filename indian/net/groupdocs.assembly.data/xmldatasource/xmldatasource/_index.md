---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "XML डेटा लोडिंग के डिफ़ॉल्ट विकल्पों का उपयोग करके XML फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.assembly.data/xmldatasource/xmldatasource/
---
## XmlDataSource(string) {#constructor_4}

XML डेटा लोडिंग के डिफ़ॉल्ट विकल्पों का उपयोग करके XML फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है।

```csharp
public XmlDataSource(string xmlPath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlPath | String | डेटा स्रोत के रूप में उपयोग किए जाने वाले XML फ़ाइल का पथ। |

### संबंधित देखें

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream) {#constructor}

XML डेटा लोडिंग के डिफ़ॉल्ट विकल्पों का उपयोग करके XML स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है।

```csharp
public XmlDataSource(Stream xmlStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlStream | Stream | डेटा स्रोत के रूप में उपयोग किए जाने वाले XML डेटा की स्ट्रीम। |

### संबंधित देखें

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string) {#constructor_6}

XML स्कीमा डिफिनिशन फ़ाइल का उपयोग करके XML फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। XML डेटा लोडिंग के लिए डिफ़ॉल्ट विकल्पों का उपयोग किया जाता है।

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlPath | String | डेटा स्रोत के रूप में उपयोग किए जाने वाले XML फ़ाइल का पथ। |
| xmlSchemaPath | String | XML फ़ाइल के लिए स्कीमा प्रदान करने वाली XML Schema Definition फ़ाइल का पथ। |

### संबंधित देखें

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream) {#constructor_2}

XML स्कीमा डिफ़िनिशन स्ट्रीम का उपयोग करके XML स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। XML डेटा लोडिंग के लिए डिफ़ॉल्ट विकल्पों का उपयोग किया जाता है।

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlStream | Stream | डेटा स्रोत के रूप में उपयोग किए जाने वाले XML डेटा की स्ट्रीम। |
| xmlSchemaStream | Stream | XML डेटा के लिए स्कीमा प्रदान करने वाली XML Schema Definition की स्ट्रीम। |

### संबंधित देखें

* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, XmlDataLoadOptions) {#constructor_5}

XML डेटा लोडिंग के लिए निर्दिष्ट विकल्पों का उपयोग करके XML फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है।

```csharp
public XmlDataSource(string xmlPath, XmlDataLoadOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlPath | String | डेटा स्रोत के रूप में उपयोग किए जाने वाले XML फ़ाइल का पथ। |
| options | XmlDataLoadOptions | XML डेटा लोड करने के विकल्प। |

### संबंधित देखें

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, XmlDataLoadOptions) {#constructor_1}

निर्दिष्ट विकल्पों का उपयोग करके XML डेटा लोडिंग के लिए XML स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है।

```csharp
public XmlDataSource(Stream xmlStream, XmlDataLoadOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlStream | Stream | डेटा स्रोत के रूप में उपयोग किए जाने वाले XML डेटा की स्ट्रीम। |
| options | XmlDataLoadOptions | XML डेटा लोड करने के विकल्प। |

### संबंधित देखें

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(string, string, XmlDataLoadOptions) {#constructor_7}

XML स्कीमा डिफिनिशन फ़ाइल का उपयोग करके XML फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। XML डेटा लोडिंग के लिए निर्दिष्ट विकल्पों का उपयोग किया जाता है।

```csharp
public XmlDataSource(string xmlPath, string xmlSchemaPath, XmlDataLoadOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlPath | String | डेटा स्रोत के रूप में उपयोग किए जाने वाले XML फ़ाइल का पथ। |
| xmlSchemaPath | String | XML फ़ाइल के लिए स्कीमा प्रदान करने वाली XML Schema Definition फ़ाइल का पथ। |
| options | XmlDataLoadOptions | XML डेटा लोड करने के विकल्प। |

### संबंधित देखें

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

---

## XmlDataSource(Stream, Stream, XmlDataLoadOptions) {#constructor_3}

XML स्कीमा डिफिनिशन स्ट्रीम का उपयोग करके XML स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। XML डेटा लोडिंग के लिए निर्दिष्ट विकल्पों का उपयोग किया जाता है।

```csharp
public XmlDataSource(Stream xmlStream, Stream xmlSchemaStream, XmlDataLoadOptions options)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmlStream | Stream | डेटा स्रोत के रूप में उपयोग किए जाने वाले XML डेटा की स्ट्रीम। |
| xmlSchemaStream | Stream | XML डेटा के लिए स्कीमा प्रदान करने वाली XML Schema Definition की स्ट्रीम। |
| options | XmlDataLoadOptions | XML डेटा लोड करने के विकल्प। |

### संबंधित देखें

* class [XmlDataLoadOptions](../../xmldataloadoptions)
* class [XmlDataSource](../../xmldatasource)
* namespace [GroupDocs.Assembly.Data](../../xmldatasource)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
