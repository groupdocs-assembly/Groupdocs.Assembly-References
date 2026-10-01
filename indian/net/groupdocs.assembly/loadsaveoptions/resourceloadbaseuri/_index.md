---
title: "ResourceLoadBaseUri"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "एक बेस URI प्राप्त करता है या सेट करता है जो HTML टेम्पलेट दस्तावेज़ को लोड करते समय बाहरी संसाधन फ़ाइलों के सापेक्ष URI को पूर्ण (absolute) में बदलने के लिए उपयोग होता है, जिसे असेंबल किया जाएगा और nonHTML फ़ॉर्मेट में सहेजा जाएगा। डिफ़ॉल्ट मान एक खाली स्ट्रिंग है।"
type: docs
weight: 20
url: /hi/net/groupdocs.assembly/loadsaveoptions/resourceloadbaseuri/
---
## LoadSaveOptions.ResourceLoadBaseUri property

एक बेस URI प्राप्त करता है या सेट करता है जिससे बाहरी संसाधन फ़ाइलों के रिलेटिव URI को एब्सोल्यूट में बदल सकें, जबकि असेंबल किए जाने वाले HTML टेम्पलेट दस्तावेज़ को लोड किया जाता है और गैर-HTML फ़ॉर्मेट में सहेजा जाता है। डिफ़ॉल्ट मान एक खाली स्ट्रिंग है।

```csharp
public string ResourceLoadBaseUri { get; set; }
```

### टिप्पणियाँ

जब किसी फ़ाइल से HTML दस्तावेज़ लोड किया जाता है, तो उसकी सम्मिलित फ़ोल्डर डिफ़ॉल्ट रूप से बेस URI के रूप में उपयोग होता है, जो स्ट्रीम से HTML दस्तावेज़ लोड करने पर संभव नहीं है। इस प्रॉपर्टी को सेट करके स्ट्रीम से HTML दस्तावेज़ लोड करते समय बेस URI निर्दिष्ट किया जा सकता है या फ़ाइल से लोड करते समय डिफ़ॉल्ट बेस URI को ओवरराइड किया जा सकता है।

इस प्रॉपर्टी का मान निम्नलिखित मामलों में अनदेखा किया जाता है:

* An HTML document being loaded contains a BASE HTML element providing a base URI.
* An HTML document being loaded is to be assembled and saved to HTML (external resource files are not loaded and relative URIs are not changed then).

### संबंधित देखें

* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
