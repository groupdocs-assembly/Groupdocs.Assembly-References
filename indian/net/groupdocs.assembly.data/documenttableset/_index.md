---
title: "DocumentTableSet"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "बाहरी दस्तावेज़ में स्थित कई टेबल्स या स्प्रेडशीट्स के डेटा तक पहुंच प्रदान करता है जिसे दस्तावेज़ असेंबल करते समय उपयोग किया जा सकता है। साथ ही दस्तावेज़ टेबल्स के लिए पैरेंट-चाइल्ड संबंध निर्धारित करने की सुविधा देता है, जिससे टेम्प्लेट दस्तावेज़ों में संबंधित डेटा तक पहुंच सरल हो जाती है।"
type: docs
weight: 200
url: /hi/net/groupdocs.assembly.data/documenttableset/
---
## DocumentTableSet class

बाहरी दस्तावेज़ में स्थित कई तालिकाओं (या स्प्रेडशीट) के डेटा तक पहुँच प्रदान करता है, जिसे दस्तावेज़ को असेंबल करते समय उपयोग किया जाता है। साथ ही, दस्तावेज़ तालिकाओं के लिए पैरेंट-चाइल्ड संबंध निर्धारित करने की सुविधा देता है, जिससे टेम्पलेट दस्तावेज़ों में संबंधित डेटा तक पहुँच सरल हो जाती है।

```csharp
public class DocumentTableSet
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DocumentTableSet](documenttableset#constructor)(Stream) | डिफ़ॉल्ट [`DocumentTableOptions`](../documenttableoptions) का उपयोग करके एक दस्तावेज़ से सभी टेबल्स लोड करते हुए इस क्लास का एक नया इंस्टेंस बनाता है। |
| [DocumentTableSet](documenttableset#constructor_2)(string) | डिफ़ॉल्ट [`DocumentTableOptions`](../documenttableoptions) का उपयोग करके एक दस्तावेज़ से सभी टेबल्स लोड करते हुए इस क्लास का एक नया इंस्टेंस बनाता है। |
| [DocumentTableSet](documenttableset#constructor_1)(Stream, IDocumentTableLoadHandler) | इस क्लास की नई इंस्टेंस बनाता है। |
| [DocumentTableSet](documenttableset#constructor_3)(string, IDocumentTableLoadHandler) | इस क्लास की नई इंस्टेंस बनाता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Relations](../../groupdocs.assembly.data/documenttableset/relations) { get; } | इस सेट के दस्तावेज़ टेबल्स के लिए परिभाषित पैरेंट-चाइल्ड संबंधों का संग्रह प्राप्त करता है। |
| [Tables](../../groupdocs.assembly.data/documenttableset/tables) { get; } | इस सेट की टेबल्स का प्रतिनिधित्व करने वाले [`DocumentTable`](../documenttable) ऑब्जेक्ट्स का संग्रह प्राप्त करता है। |

### टिप्पणियाँ

स्प्रेडशीट फ़ाइल फ़ॉर्मेट के दस्तावेज़ों के लिए, एक [`DocumentTableSet`](../documenttableset) इंस्टेंस शीट्स का सेट दर्शाता है। अन्य फ़ाइल फ़ॉर्मेट के दस्तावेज़ों के लिए, एक [`DocumentTableSet`](../documenttableset) इंस्टेंस टेबल्स का सेट दर्शाता है।

दस्तावेज़ असेंबल करते समय संबंधित टेबल्स के डेटा तक पहुंचने के लिए, इस क्लास का एक इंस्टेंस डेटा स्रोत के रूप में [`DocumentAssembler`](../../groupdocs.assembly/documentassembler).AssembleDocument के ओवरलोड्स में से किसी एक को पास करें।

टेम्प्लेट दस्तावेज़ों में, एक [`DocumentTableSet`](../documenttableset) इंस्टेंस को उसी तरह माना जाना चाहिए जैसे वह DataSet इंस्टेंस हो। अधिक जानकारी के लिए टेम्प्लेट सिंटैक्स रेफ़रेंस देखें।

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
