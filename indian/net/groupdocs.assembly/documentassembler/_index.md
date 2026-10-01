---
title: "DocumentAssembler"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "डेटा के साथ टेम्पलेट दस्तावेज़ों को भरने और इन प्रक्रियाओं को नियंत्रित करने के लिए सेटिंग्स के एक सेट के लिए रूटीन प्रदान करता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.assembly/documentassembler/
---
## DocumentAssembler class

डेटा के साथ टेम्पलेट दस्तावेज़ों को भरने और इन प्रक्रियाओं को नियंत्रित करने के लिए सेटिंग्स के एक सेट के लिए रूटीन प्रदान करता है।

```csharp
public class DocumentAssembler
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DocumentAssembler](documentassembler)() | इस वर्ग की नई इंस्टेंस को प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BarcodeSettings](../../groupdocs.assembly/documentassembler/barcodesettings) { get; } | दस्तावेज़ को असेंबल करते समय बारकोड जनरेशन को नियंत्रित करने वाली सेटिंग्स का सेट प्राप्त करता है। |
| [KnownTypes](../../groupdocs.assembly/documentassembler/knowntypes) { get; } | एक अनऑर्डर्ड सेट (अर्थात, अद्वितीय आइटमों का संग्रह) प्राप्त करता है जिसमें Type ऑब्जेक्ट्स होते हैं, जिनके पूर्ण या आंशिक योग्य नाम इस असेंबलर इंस्टेंस द्वारा प्रोसेस किए गए दस्तावेज़ टेम्प्लेट्स में उपयोग किए जा सकते हैं ताकि संबंधित प्रकारों के स्थैतिक सदस्य को कॉल किया जा सके, टाइप कास्ट किए जा सकें, आदि। |
| [Options](../../groupdocs.assembly/documentassembler/options) { get; set; } | दस्तावेज़ को असेंबल करते समय इस [`DocumentAssembler`](../documentassembler) इंस्टेंस के व्यवहार को नियंत्रित करने वाले फ़्लैग्स का सेट प्राप्त करता है या सेट करता है। |
| static [UseReflectionOptimization](../../groupdocs.assembly/documentassembler/usereflectionoptimization) { get; set; } | कस्टम टाइप सदस्यों के रिफ्लेक्शन API के माध्यम से किए गए कॉल को डायनामिक क्लास जेनरेशन द्वारा अनुकूलित किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान true है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument)(Stream, Stream, params DataSourceInfo[]) | निर्दिष्ट स्रोत स्ट्रीम से टेम्पलेट दस्तावेज़ लोड करता है, निर्दिष्ट एकल या कई स्रोतों से डेटा के साथ टेम्पलेट दस्तावेज़ को भरता है, और डिफ़ॉल्ट [`LoadSaveOptions`](../loadsaveoptions) का उपयोग करके परिणाम दस्तावेज़ को लक्ष्य स्ट्रीम में संग्रहीत करता है। |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_2)(string, string, params DataSourceInfo[]) | निर्दिष्ट स्रोत पथ से टेम्पलेट दस्तावेज़ लोड करता है, निर्दिष्ट एकल या कई स्रोतों से डेटा के साथ टेम्पलेट दस्तावेज़ को भरता है, और डिफ़ॉल्ट [`LoadSaveOptions`](../loadsaveoptions) का उपयोग करके परिणाम दस्तावेज़ को लक्ष्य पथ में संग्रहीत करता है। |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_1)(Stream, Stream, LoadSaveOptions, params DataSourceInfo[]) | निर्दिष्ट स्रोत स्ट्रीम से टेम्पलेट दस्तावेज़ लोड करता है, निर्दिष्ट एकल या कई स्रोतों से डेटा के साथ टेम्पलेट दस्तावेज़ को भरता है, और दिए गए [`LoadSaveOptions`](../loadsaveoptions) का उपयोग करके परिणाम दस्तावेज़ को लक्ष्य स्ट्रीम में संग्रहीत करता है। |
| [AssembleDocument](../../groupdocs.assembly/documentassembler/assembledocument#assembledocument_3)(string, string, LoadSaveOptions, params DataSourceInfo[]) | निर्दिष्ट स्रोत पथ से टेम्पलेट दस्तावेज़ लोड करता है, निर्दिष्ट एकल या कई स्रोतों से डेटा के साथ टेम्पलेट दस्तावेज़ को भरता है, और दिए गए [`LoadSaveOptions`](../loadsaveoptions) का उपयोग करके परिणाम दस्तावेज़ को लक्ष्य पथ में संग्रहीत करता है। |

### संबंधित देखें

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
