---
title: DocumentTable
second_title: GroupDocs.Assembly .NET API संदर्भ के लिए
description: एक बहर दस्तवेज़ में स्थत एक एकल तलक य स्प्रेडशट के डेट तक पहुँच प्रदन करत है जसक उपयग दस्तवेज़ क असेंबल करते समय कय जत है
type: docs
weight: 40
url: /hi/net/groupdocs.assembly.data/documenttable/
---
## DocumentTable class

एक बाहरी दस्तावेज़ में स्थित एक एकल तालिका (या स्प्रेडशीट) के डेटा तक पहुँच प्रदान करता है जिसका उपयोग दस्तावेज़ को असेंबल करते समय किया जाता है।

```csharp
public class DocumentTable
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DocumentTable](documenttable#constructor)(Stream, int) | डिफ़ॉल्ट का उपयोग करके इस वर्ग का एक नया उदाहरण बनाता है[`DocumentTableOptions`](../documenttableoptions) . |
| [DocumentTable](documenttable#constructor_2)(string, int) | डिफ़ॉल्ट का उपयोग करके इस वर्ग का एक नया उदाहरण बनाता है[`DocumentTableOptions`](../documenttableoptions) . |
| [DocumentTable](documenttable#constructor_1)(Stream, int, DocumentTableOptions) | इस वर्ग का एक नया उदाहरण बनाता है। |
| [DocumentTable](documenttable#constructor_3)(string, int, DocumentTableOptions) | इस वर्ग का एक नया उदाहरण बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Columns](../../groupdocs.assembly.data/documenttable/columns) { get; } | का संग्रह प्राप्त करता है[`DocumentTableColumn`](../documenttablecolumn) संबंधित तालिका के स्तंभों का प्रतिनिधित्व करने वाली वस्तुएं। |
| [IndexInDocument](../../groupdocs.assembly.data/documenttable/indexindocument) { get; } | स्रोत दस्तावेज़ के अनुसार संबंधित तालिका का मूल शून्य-आधारित सूचकांक प्राप्त करता है। |
| [Name](../../groupdocs.assembly.data/documenttable/name) { get; set; } | को पास किए गए टेम्पलेट दस्तावेज़ में तालिका के डेटा तक पहुंचने के लिए उपयोग की जाने वाली इस तालिका का नाम प्राप्त या सेट करता है[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) . |

### टिप्पणियों

स्प्रेडशीट फ़ाइल स्वरूपों के दस्तावेज़ों के लिए, a[`DocumentTable`](../documenttable) उदाहरण एक शीट का प्रतिनिधित्व करता है। अन्य फ़ाइल स्वरूपों के दस्तावेज़ों के लिए, ए[`DocumentTable`](../documenttable) उदाहरण एक एकल तालिका का प्रतिनिधित्व करता है।

किसी दस्तावेज़ को असेंबल करते समय संबंधित तालिका के डेटा तक पहुँचने के लिए, इस वर्ग का एक उदाहरण डेटा स्रोत के रूप में पास करें[`DocumentAssembler`](../../groupdocs.assembly/documentassembler) .इकट्ठाDocument अधिभार।

टेम्प्लेट दस्तावेज़ों में, a[`DocumentTable`](../documenttable) उदाहरण को उसी तरह व्यवहार किया जाना चाहिए जैसे कि यह था aDataTable उदाहरण। अधिक जानकारी के लिए टेम्प्लेट सिंटैक्स संदर्भ देखें।

### यह सभी देखें

* नाम स्थान [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* सभा [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->