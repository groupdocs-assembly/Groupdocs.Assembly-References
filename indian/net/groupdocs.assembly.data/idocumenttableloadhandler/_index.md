---
title: "IDocumentTableLoadHandler"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "DocumentTable./documenttable ऑब्जेक्ट्स की डिफ़ॉल्ट लोडिंग को ओवरराइड करता है जबकि एक DocumentTableSet./documenttableset इंस्टेंस बनाया जा रहा है।"
type: docs
weight: 210
url: /hi/net/groupdocs.assembly.data/idocumenttableloadhandler/
---
## IDocumentTableLoadHandler interface

एक [`DocumentTableSet`](../documenttableset) इंस्टेंस बनाते समय [`DocumentTable`](../documenttable) ऑब्जेक्ट्स की डिफ़ॉल्ट लोडिंग को ओवरराइड करता है।

```csharp
public interface IDocumentTableLoadHandler
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Handle](../../groupdocs.assembly.data/idocumenttableloadhandler/handle)(DocumentTableLoadArgs) | एक [`DocumentTableSet`](../documenttableset) इंस्टेंस बनाते समय किसी विशेष [`DocumentTable`](../documenttable) ऑब्जेक्ट की डिफ़ॉल्ट लोडिंग को ओवरराइड करता है। |

### टिप्पणियाँ

यदि आप विशिष्ट [`DocumentTable`](../documenttable) ऑब्जेक्ट्स की लोडिंग को त्यागना चाहते हैं या लोड हो रहे दस्तावेज़ टेबल्स के लिए विशिष्ट [`DocumentTableOptions`](../documenttableoptions) प्रदान करना चाहते हैं तो इस इंटरफ़ेस को लागू करें।

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
