---
title: "DataSourceInfo"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "इस क्लास का एक नया इंस्टेंस बनाता है बिना किसी प्रॉपर्टी के निर्दिष्ट किए।"
type: docs
weight: 10
url: /hi/net/groupdocs.assembly/datasourceinfo/datasourceinfo/
---
## DataSourceInfo() {#constructor}

इस क्लास का एक नया इंस्टेंस बनाता है बिना किसी प्रॉपर्टी के निर्दिष्ट किए।

```csharp
public DataSourceInfo()
```

### संबंधित देखें

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object) {#constructor_1}

निर्दिष्ट डेटा स्रोत वस्तु के साथ इस वर्ग की नई इंस्टेंस बनाता है।

```csharp
public DataSourceInfo(object dataSource)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataSource | Object | डेटा स्रोत ऑब्जेक्ट। |

### टिप्पणियाँ

डेटा स्रोत ऑब्जेक्ट निम्नलिखित प्रकारों में से एक हो सकता है:

* [`XmlDataSource`](../../../groupdocs.assembly.data/xmldatasource)
* [`JsonDataSource`](../../../groupdocs.assembly.data/jsondatasource)
* [`CsvDataSource`](../../../groupdocs.assembly.data/csvdatasource)
* [`DocumentTableSet`](../../../groupdocs.assembly.data/documenttableset)
* [`DocumentTable`](../../../groupdocs.assembly.data/documenttable)
* DataSet
* DataTable
* DataRow
* IDataReader
* IDataRecord
* DataView
* DataRowView
* Any other arbitrary non-dynamic and non-anonymous .NET type

विभिन्न प्रकार के डेटा स्रोतों के साथ टेम्पलेट दस्तावेज़ों में काम करने के बारे में जानकारी के लिए, टेम्पलेट सिंटैक्स रेफ़रेंस देखें (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)।

### संबंधित देखें

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

---

## DataSourceInfo(object, string) {#constructor_2}

डेटा स्रोत वस्तु और उसका नाम निर्दिष्ट करके इस वर्ग की नई इंस्टेंस बनाता है।

```csharp
public DataSourceInfo(object dataSource, string name)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dataSource | Object | डेटा स्रोत ऑब्जेक्ट। |
| name | String | टेम्पलेट दस्तावेज़ में डेटा स्रोत ऑब्जेक्ट तक पहुँचने के लिए उपयोग किए जाने वाले डेटा स्रोत ऑब्जेक्ट का नाम। |

### टिप्पणियाँ

डेटा स्रोत ऑब्जेक्ट निम्नलिखित प्रकारों में से एक हो सकता है:

* [`XmlDataSource`](../../../groupdocs.assembly.data/xmldatasource)
* [`JsonDataSource`](../../../groupdocs.assembly.data/jsondatasource)
* [`CsvDataSource`](../../../groupdocs.assembly.data/csvdatasource)
* [`DocumentTableSet`](../../../groupdocs.assembly.data/documenttableset)
* [`DocumentTable`](../../../groupdocs.assembly.data/documenttable)
* DataSet
* DataTable
* DataRow
* IDataReader
* IDataRecord
* DataView
* DataRowView
* Any other arbitrary non-dynamic and non-anonymous .NET type

विभिन्न प्रकार के डेटा स्रोतों के साथ टेम्पलेट दस्तावेज़ों में काम करने के बारे में जानकारी के लिए, टेम्पलेट सिंटैक्स रेफ़रेंस देखें (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)।

जब डेटा स्रोत ऑब्जेक्ट का नाम निर्दिष्ट किया जाता है, तो आप टेम्पलेट दस्तावेज़ में नाम का उपयोग करके डेटा स्रोत ऑब्जेक्ट और उसके सदस्यों तक पहुंच सकते हैं।

जब डेटा स्रोत ऑब्जेक्ट का नाम null या खाली हो, तो आप अभी भी टेम्पलेट दस्तावेज़ में कॉन्टेक्स्ट ऑब्जेक्ट सदस्य एक्सेस (अधिक जानकारी के लिए टेम्पलेट सिंटैक्स रेफ़रेंस देखें) का उपयोग करके डेटा स्रोत ऑब्जेक्ट के सदस्यों तक पहुंच सकते हैं, लेकिन आप डेटा स्रोत ऑब्जेक्ट स्वयं तक पहुंच नहीं सकते।

जब कई [`DataSourceInfo`](../../datasourceinfo) इंस्टेंस को [`DocumentAssembler`](../../documentassembler) को पास किया जाता है, तो केवल पहले डेटा स्रोत ऑब्जेक्ट का नाम null या खाली हो सकता है। शेष ऑब्जेक्ट्स के नाम निर्दिष्ट और अद्वितीय होने चाहिए।

### संबंधित देखें

* class [DataSourceInfo](../../datasourceinfo)
* namespace [GroupDocs.Assembly](../../datasourceinfo)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
