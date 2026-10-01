---
title: "JsonDataSource"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "दस्तावेज़ को असेंबल करते समय उपयोग के लिए JSON फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है।"
type: docs
weight: 230
url: /hi/net/groupdocs.assembly.data/jsondatasource/
---
## JsonDataSource class

दस्तावेज़ को असेंबल करते समय उपयोग के लिए JSON फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है।

```csharp
public class JsonDataSource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [JsonDataSource](jsondatasource#constructor)(Stream) | JSON डेटा को पार्स करने के लिए डिफ़ॉल्ट विकल्पों का उपयोग करके JSON स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [JsonDataSource](jsondatasource#constructor_2)(string) | JSON डेटा को पार्स करने के लिए डिफ़ॉल्ट विकल्पों का उपयोग करके JSON फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [JsonDataSource](jsondatasource#constructor_1)(Stream, JsonDataLoadOptions) | JSON डेटा को पार्स करने के लिए निर्दिष्ट विकल्पों का उपयोग करके JSON स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [JsonDataSource](jsondatasource#constructor_3)(string, JsonDataLoadOptions) | JSON डेटा को पार्स करने के लिए निर्दिष्ट विकल्पों का उपयोग करके JSON फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। |

### टिप्पणियाँ

दस्तावेज़ को असेंबल करते समय संबंधित फ़ाइल या स्ट्रीम के डेटा तक पहुँचने के लिए, इस वर्ग का एक उदाहरण डेटा स्रोत के रूप में [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument ओवरलोड्स में से एक को पास करें।

टेम्प्लेट दस्तावेज़ों में, यदि शीर्ष-स्तर का JSON तत्व एक एरे है, तो एक [`JsonDataSource`](../jsondatasource) उदाहरण को उसी तरह व्यवहार किया जाना चाहिए जैसे वह DataTable उदाहरण हो। यदि शीर्ष-स्तर का JSON तत्व एक ऑब्जेक्ट है, तो एक [`JsonDataSource`](../jsondatasource) उदाहरण को उसी तरह व्यवहार किया जाना चाहिए जैसे वह DataRow उदाहरण हो। अधिक जानकारी के लिए, टेम्प्लेट सिंटैक्स संदर्भ देखें (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)।

टेम्प्लेट दस्तावेज़ों में, आप JSON तत्वों के टाइप्ड मानों के साथ काम कर सकते हैं। सुविधा के लिए, इंजन JSON सरल प्रकारों के सेट को निम्नलिखित से बदल देता है:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

इंजन उनके JSON प्रतिनिधित्व पर अतिरिक्त प्रकारों के मानों को स्वचालित रूप से पहचानता है।

JSON डेटा लोडिंग के डिफ़ॉल्ट व्यवहार को ओवरराइड करने के लिए, इस वर्ग के कंस्ट्रक्टर को एक [`JsonDataLoadOptions`](../jsondataloadoptions) उदाहरण प्रारंभ करके पास करें।

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
