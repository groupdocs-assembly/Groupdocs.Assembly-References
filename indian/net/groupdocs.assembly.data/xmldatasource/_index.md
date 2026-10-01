---
title: "XmlDataSource"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "दस्तावेज़ को असेंबल करते समय उपयोग के लिए XML फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है।"
type: docs
weight: 260
url: /hi/net/groupdocs.assembly.data/xmldatasource/
---
## XmlDataSource class

दस्तावेज़ को असेंबल करते समय उपयोग के लिए XML फ़ाइल या स्ट्रीम के डेटा तक पहुँच प्रदान करता है।

```csharp
public class XmlDataSource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [XmlDataSource](xmldatasource#constructor)(Stream) | XML डेटा लोडिंग के डिफ़ॉल्ट विकल्पों का उपयोग करके XML स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [XmlDataSource](xmldatasource#constructor_4)(string) | XML डेटा लोडिंग के डिफ़ॉल्ट विकल्पों का उपयोग करके XML फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [XmlDataSource](xmldatasource#constructor_2)(Stream, Stream) | XML स्कीमा डिफ़िनिशन स्ट्रीम का उपयोग करके XML स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। XML डेटा लोडिंग के लिए डिफ़ॉल्ट विकल्पों का उपयोग किया जाता है। |
| [XmlDataSource](xmldatasource#constructor_1)(Stream, XmlDataLoadOptions) | निर्दिष्ट विकल्पों का उपयोग करके XML डेटा लोडिंग के लिए XML स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [XmlDataSource](xmldatasource#constructor_6)(string, string) | XML स्कीमा डिफिनिशन फ़ाइल का उपयोग करके XML फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। XML डेटा लोडिंग के लिए डिफ़ॉल्ट विकल्पों का उपयोग किया जाता है। |
| [XmlDataSource](xmldatasource#constructor_5)(string, XmlDataLoadOptions) | XML डेटा लोडिंग के लिए निर्दिष्ट विकल्पों का उपयोग करके XML फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। |
| [XmlDataSource](xmldatasource#constructor_3)(Stream, Stream, XmlDataLoadOptions) | XML स्कीमा डिफिनिशन स्ट्रीम का उपयोग करके XML स्ट्रीम से डेटा के साथ एक नया डेटा स्रोत बनाता है। XML डेटा लोडिंग के लिए निर्दिष्ट विकल्पों का उपयोग किया जाता है। |
| [XmlDataSource](xmldatasource#constructor_7)(string, string, XmlDataLoadOptions) | XML स्कीमा डिफिनिशन फ़ाइल का उपयोग करके XML फ़ाइल से डेटा के साथ एक नया डेटा स्रोत बनाता है। XML डेटा लोडिंग के लिए निर्दिष्ट विकल्पों का उपयोग किया जाता है। |

### टिप्पणियाँ

दस्तावेज़ को असेंबल करते समय संबंधित फ़ाइल या स्ट्रीम के डेटा तक पहुँचने के लिए, इस वर्ग का एक उदाहरण डेटा स्रोत के रूप में [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument ओवरलोड्स में से एक को पास करें।

टेम्पलेट दस्तावेज़ों में, यदि एक शीर्ष-स्तर XML तत्व केवल समान प्रकार के तत्वों की सूची रखता है, तो एक [`XmlDataSource`](../xmldatasource) इंस्टेंस को उसी तरह माना जाना चाहिए जैसे वह DataTable इंस्टेंस हो। अन्यथा, एक [`XmlDataSource`](../xmldatasource) इंस्टेंस को उसी तरह माना जाना चाहिए जैसे वह DataRow इंस्टेंस हो। अधिक जानकारी के लिए, टेम्पलेट सिंटैक्स रेफ़रेंस देखें (https://docs.groupdocs.com/display/assemblynet/Template+Syntax+-+Part+1+of+2#TemplateSyntax-Part1of2-UsingDataSources)।

जब इस क्लास के कंस्ट्रक्टर को XML स्कीमा डिफिनिशन पास किया जाता है, तो सरल XML तत्वों और एट्रिब्यूट्स के मानों के डेटा प्रकार स्कीमा के अनुसार निर्धारित होते हैं। इसलिए टेम्पलेट दस्तावेज़ों में, आप केवल स्ट्रिंग्स के बजाय टाइप्ड मानों के साथ काम कर सकते हैं।

जब इस क्लास के कंस्ट्रक्टर को XML स्कीमा डिफिनिशन पास नहीं किया जाता है, तो सरल XML तत्वों और एट्रिब्यूट्स के मानों के डेटा प्रकार उनके स्ट्रिंग प्रतिनिधित्व पर स्वचालित रूप से निर्धारित होते हैं। इसलिए टेम्पलेट दस्तावेज़ों में, आप इस मामले में भी टाइप्ड मानों के साथ काम कर सकते हैं। इंजन निम्नलिखित प्रकारों के मानों को स्वचालित रूप से पहचानने में सक्षम है:

* `long?`
* `double?`
* `bool?`
* `DateTime?`
* `string`

ध्यान दें कि डेटा प्रकारों की स्वचालित पहचान के काम करने के लिए, सरल XML तत्वों और एट्रिब्यूट्स के मानों के स्ट्रिंग प्रतिनिधित्व को इनवेरिएंट कल्चर सेटिंग्स का उपयोग करके बनाना चाहिए।

XML डेटा लोडिंग के डिफ़ॉल्ट व्यवहार को ओवरराइड करने के लिए, एक [`XmlDataLoadOptions`](../xmldataloadoptions) इंस्टेंस को इनिशियलाइज़ करें और इस क्लास के कंस्ट्रक्टर को पास करें।

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
