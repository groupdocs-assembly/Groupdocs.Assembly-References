---
title: "JsonDataLoadOptions"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "JSON डेटा पार्स करने के विकल्प दर्शाता है।"
type: docs
weight: 220
url: /hi/net/groupdocs.assembly.data/jsondataloadoptions/
---
## JsonDataLoadOptions class

JSON डेटा पार्स करने के विकल्प दर्शाता है।

```csharp
public class JsonDataLoadOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [JsonDataLoadOptions](jsondataloadoptions)() | डिफ़ॉल्ट विकल्पों के साथ इस वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [AlwaysGenerateRootObject](../../groupdocs.assembly.data/jsondataloadoptions/alwaysgeneraterootobject) { get; set; } | एक फ़्लैग प्राप्त करता है या सेट करता है जो यह दर्शाता है कि क्या उत्पन्न डेटा स्रोत हमेशा एक JSON रूट तत्व के लिए एक वस्तु रखेगा। यदि एक JSON रूट तत्व में एक ही जटिल प्रॉपर्टी है, तो ऐसी वस्तु डिफ़ॉल्ट रूप से नहीं बनाई जाती। |
| [ExactDateTimeParseFormats](../../groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats) { get; set; } | JSON लोड करते समय JSON तिथि-समय मानों को पार्स करने के लिए सटीक फ़ॉर्मेट प्राप्त करता है या सेट करता है। डिफ़ॉल्ट **null** है। |
| [SimpleValueParseMode](../../groupdocs.assembly.data/jsondataloadoptions/simplevalueparsemode) { get; set; } | JSON लोड करते समय JSON सरल मानों (null, boolean, number, integer, और string) को पार्स करने के लिए एक मोड प्राप्त करता है या सेट करता है। ऐसा मोड तिथि-समय मानों के पार्सिंग को प्रभावित नहीं करता। डिफ़ॉल्ट Loose है। |

### टिप्पणियाँ

इस वर्ग की एक इंस्टेंस को [`JsonDataSource`](../jsondatasource) के कंस्ट्रक्टर्स में पास किया जा सकता है।

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
