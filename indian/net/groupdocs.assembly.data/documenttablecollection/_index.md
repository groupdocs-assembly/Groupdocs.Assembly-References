---
title: "DocumentTableCollection"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "एक विशिष्ट DocumentTableSet./documenttableset इंस्टेंस के DocumentTable./documenttable ऑब्जेक्ट्स का केवल-पढ़ने योग्य संग्रह दर्शाता है।"
type: docs
weight: 130
url: /hi/net/groupdocs.assembly.data/documenttablecollection/
---
## DocumentTableCollection class

एक विशिष्ट [`DocumentTableSet`](../documenttableset) इंस्टेंस के [`DocumentTable`](../documenttable) ऑब्जेक्ट्स का केवल-पढ़ने योग्य संग्रह दर्शाता है।

```csharp
public class DocumentTableCollection : IEnumerable
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [Count](../../groupdocs.assembly.data/documenttablecollection/count) { get; } | संग्रह में मौजूद कुल [`DocumentTable`](../documenttable) ऑब्जेक्ट्स की संख्या प्राप्त करता है। |
| [Item](../../groupdocs.assembly.data/documenttablecollection/item) { get; } | निर्दिष्ट अनुक्रमांक पर संग्रह से एक [`DocumentTable`](../documenttable) इंस्टेंस प्राप्त करता है। (2 इंडेक्सर) |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains)(DocumentTable) | यह दर्शाने वाला मान लौटाता है कि यह संग्रह निर्दिष्ट तालिका को शामिल करता है या नहीं। |
| [Contains](../../groupdocs.assembly.data/documenttablecollection/contains#contains_1)(string) | यह दर्शाने वाला मान लौटाता है कि यह संग्रह निर्दिष्ट नाम वाली तालिका को शामिल करता है या नहीं। |
| [GetEnumerator](../../groupdocs.assembly.data/documenttablecollection/getenumerator)() | इस संग्रह के [`DocumentTable`](../documenttable) ऑब्जेक्ट्स पर इटररेट करने के लिए एक एन्यूमरेटर लौटाता है। |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof)(DocumentTable) | इस संग्रह में निर्दिष्ट तालिका का अनुक्रमांक लौटाता है। |
| [IndexOf](../../groupdocs.assembly.data/documenttablecollection/indexof#indexof_1)(string) | इस संग्रह में निर्दिष्ट नाम वाली तालिका का अनुक्रमांक लौटाता है। |

### टिप्पणियाँ

संग्रह को स्वचालित रूप से दस्तावेज़ से संबंधित तालिकाओं को लोड करते समय भर दिया जाता है और इसे संशोधित नहीं किया जा सकता। हालांकि, संग्रह में शामिल [`DocumentTable`](../documenttable) ऑब्जेक्ट्स की गुणधर्मों को संशोधित किया जा सकता है।

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
