---
title: "CsvDataSource"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "दस्तावेज़ को असेंबल करते समय उपयोग के लिए CSV फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है।"
type: docs
weight: 110
url: /hi/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

दस्तावेज़ को असेंबल करते समय उपयोग के लिए CSV फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है।

```csharp
public class CsvDataSource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | डिफ़ॉल्ट विकल्पों का उपयोग करके CSV डेटा को पार्स करने हेतु CSV स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [CsvDataSource](csvdatasource#constructor_2)(string) | डिफ़ॉल्ट विकल्पों का उपयोग करके CSV डेटा को पार्स करने हेतु CSV फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | निर्दिष्ट विकल्पों का उपयोग करके CSV डेटा को पार्स करने हेतु CSV स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | निर्दिष्ट विकल्पों का उपयोग करके CSV डेटा को पार्स करने हेतु CSV फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। |

### टिप्पणियाँ

दस्तावेज़ को असेंबल करते समय संबंधित फ़ाइल या स्ट्रीम के डेटा तक पहुँचने के लिए, इस वर्ग का एक उदाहरण डेटा स्रोत के रूप में [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument ओवरलोड्स में से एक को पास करें।

टेम्प्लेट दस्तावेज़ों में, एक [`CsvDataSource`](../csvdatasource) इंस्टेंस को उसी तरह माना जाना चाहिए जैसे वह DataTable इंस्टेंस हो। अधिक जानकारी के लिए टेम्प्लेट सिंटैक्स रेफ़रेंस देखें (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)।

कॉमा-सेपरेटेड वैल्यूज़ के डेटा प्रकार उनके स्ट्रिंग प्रतिनिधित्व के आधार पर स्वचालित रूप से निर्धारित होते हैं। इसलिए टेम्प्लेट दस्तावेज़ों में, आप केवल स्ट्रिंग्स के बजाय टाइप्ड वैल्यूज़ के साथ काम कर सकते हैं। इंजन निम्नलिखित प्रकारों के वैल्यूज़ को स्वचालित रूप से पहचानने में सक्षम है:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

ध्यान दें कि डेटा प्रकारों की स्वचालित पहचान के कार्य करने के लिए, कॉमा-सेपरेटेड वैल्यूज़ के स्ट्रिंग प्रतिनिधित्व को इनवेरिएंट कल्चर सेटिंग्स का उपयोग करके बनाया जाना चाहिए।

CSV डेटा लोडिंग के डिफ़ॉल्ट व्यवहार को ओवरराइड करने के लिए, इस क्लास के कंस्ट्रक्टर में एक [`CsvDataLoadOptions`](../csvdataloadoptions) इंस्टेंस को इनिशियलाइज़ करके पास करें।

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
