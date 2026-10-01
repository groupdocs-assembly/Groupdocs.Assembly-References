---
title: "DocumentTable"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "एक बाहरी दस्तावेज़ में स्थित एकल तालिका या स्प्रेडशीट के डेटा तक पहुंच प्रदान करता है, जिसका उपयोग दस्तावेज़ को असेंबल करते समय किया जाता है।"
type: docs
weight: 120
url: /hi/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

बाहरी दस्तावेज़ में स्थित एकल तालिका (या स्प्रेडशीट) के डेटा तक पहुँच प्रदान करता है, जिसे दस्तावेज़ को असेंबल करते समय उपयोग किया जाता है।

```csharp
public class DocumentTable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | डिफ़ॉल्ट [`DocumentTableOptions`](../documenttableoptions) का उपयोग करके इस क्लास का एक नया इंस्टेंस बनाता है। |
| [DocumentTable](documenttable#constructor_2)(string, int) | डिफ़ॉल्ट [`DocumentTableOptions`](../documenttableoptions) का उपयोग करके इस क्लास का एक नया इंस्टेंस बनाता है। |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | इस क्लास की नई इंस्टेंस बनाता है। |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | इस क्लास की नई इंस्टेंस बनाता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | संबंधित तालिका के कॉलमों को दर्शाने वाले [`DocumentTableColumn`](../documenttablecolumn) ऑब्जेक्ट्स का संग्रह प्राप्त करता है। |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | स्रोत दस्तावेज़ के अनुसार संबंधित तालिका का मूल शून्य-आधारित इंडेक्स प्राप्त करता है। |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | इस तालिका का वह नाम प्राप्त करता है या सेट करता है जिसका उपयोग टेम्पलेट दस्तावेज़ में तालिका के डेटा तक पहुंचने के लिए किया जाता है, जिसे [`DocumentAssembler`](../../groupdocs.assembly/documentassembler) को पास किया गया है। |

### टिप्पणियाँ

स्प्रेडशीट फ़ाइल फ़ॉर्मेट के दस्तावेज़ों के लिए, एक [`DocumentTable`](../documenttable) इंस्टेंस एकल शीट का प्रतिनिधित्व करता है। अन्य फ़ाइल फ़ॉर्मेट के दस्तावेज़ों के लिए, एक [`DocumentTable`](../documenttable) इंस्टेंस एकल तालिका का प्रतिनिधित्व करता है।

दस्तावेज़ को असेंबल करते समय संबंधित तालिका के डेटा तक पहुंचने के लिए, इस क्लास का एक इंस्टेंस डेटा स्रोत के रूप में [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument ओवरलोड्स में से किसी एक को पास करें।

टेम्पलेट दस्तावेज़ों में, एक [`DocumentTable`](../documenttable) इंस्टेंस को उसी तरह माना जाना चाहिए जैसे वह DataTable इंस्टेंस हो। अधिक जानकारी के लिए टेम्पलेट सिंटैक्स रेफ़रेंस देखें।

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
