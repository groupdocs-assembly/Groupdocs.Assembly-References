---
title: CsvDataSource
second_title: GroupDocs.Assembly .NET API संदर्भ के लिए
description: कस दस्तवेज़ क असेंबल करते समय उपयग क जने वल CSV फ़इल य स्ट्रम के डेट तक पहुँच प्रदन करत है
type: docs
weight: 30
url: /hi/net/groupdocs.assembly.data/csvdatasource/
---
## CsvDataSource class

किसी दस्तावेज़ को असेंबल करते समय उपयोग की जाने वाली CSV फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है।

```csharp
public class CsvDataSource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [CsvDataSource](csvdatasource#constructor)(Stream) | CSV डेटा को पार्स करने के लिए डिफ़ॉल्ट विकल्पों का उपयोग करके CSV स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [CsvDataSource](csvdatasource#constructor_2)(string) | CSV डेटा को पार्स करने के लिए डिफ़ॉल्ट विकल्पों का उपयोग करके CSV फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [CsvDataSource](csvdatasource#constructor_1)(Stream, CsvDataLoadOptions) | CSV डेटा को पार्स करने के लिए निर्दिष्ट विकल्पों का उपयोग करके CSV स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [CsvDataSource](csvdatasource#constructor_3)(string, CsvDataLoadOptions) | CSV डेटा को पार्स करने के लिए निर्दिष्ट विकल्पों का उपयोग करके CSV फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। |

### टिप्पणियों

किसी दस्तावेज़ को असेंबल करते समय संबंधित फ़ाइल या स्ट्रीम के डेटा तक पहुँचने के लिए, इस वर्ग के एक उदाहरण को डेटा स्रोत के रूप में पास करें[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .इकट्ठा दस्तावेज़ ओवरलोड।

टेम्प्लेट दस्तावेज़ों में, a[`CsvDataSource`](../csvdatasource) उदाहरण को उसी तरह व्यवहार किया जाना चाहिए जैसे कि यह था aDataTableउदाहरण। अधिक जानकारी के लिए, टेम्पलेट सिंटैक्स संदर्भ देखें

डेटा प्रकार के अल्पविराम से अलग किए गए मान उनके स्ट्रिंग प्रस्तुतियों पर स्वचालित रूप से निर्धारित होते हैं। तो Template दस्तावेज़ों में, आप केवल स्ट्रिंग्स के बजाय टाइप किए गए मानों के साथ काम कर सकते हैं। इंजन स्वचालित रूप से निम्न प्रकार के मानों को पहचानने में सक्षम है:

* `लंबा?`
* `दोहरा?`
* `बूल?`
* `दिनांक समय?`
* `डोरी`

ध्यान दें कि काम करने के लिए डेटा प्रकारों की स्वचालित पहचान के लिए, अल्पविराम से अलग किए गए मानों के स्ट्रिंग प्रस्तुतीकरण को अपरिवर्तनीय संस्कृति सेटिंग्स का उपयोग करके बनाया जाना चाहिए।

सीएसवी डेटा लोडिंग के डिफ़ॉल्ट व्यवहार को ओवरराइड करने के लिए, प्रारंभ करें और पास करें[`CsvDataLoadOptions`](../csvdataloadoptions)इस वर्ग के निर्माता के लिए उदाहरण .

### यह सभी देखें

* नाम स्थान [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* सभा [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->