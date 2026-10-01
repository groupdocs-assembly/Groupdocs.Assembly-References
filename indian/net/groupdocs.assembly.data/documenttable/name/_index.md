---
title: "नाम"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "इस तालिका का नाम प्राप्त करता है या सेट करता है, जिसका उपयोग टेम्प्लेट दस्तावेज़ में तालिका के डेटा तक पहुँचने के लिए किया जाता है, जिसे DocumentAssemblergroupdocs.assembly/documentassembler को पास किया गया है।"
type: docs
weight: 40
url: /hi/net/groupdocs.assembly.data/documenttable/name/
---
## DocumentTable.Name property

इस तालिका का नाम प्राप्त करता है या सेट करता है, जिसका उपयोग टेम्प्लेट दस्तावेज़ में तालिका के डेटा तक पहुँचने के लिए किया जाता है, जिसे [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler) को पास किया गया है।

```csharp
public string Name { get; set; }
```

### टिप्पणियाँ

यदि तालिका का नाम किसी दस्तावेज़ से पढ़ा जाता है, तो नाम स्वचालित रूप से सही किया जाता है ताकि वह मान्य हो सके। हालांकि, यदि इस प्रॉपर्टी के माध्यम से तालिका का नाम मैन्युअल रूप से सेट किया जाता है और वह अमान्य है, तो एक अपवाद फेंका जाता है।

यदि निम्नलिखित शर्तें पूरी होती हैं, तो तालिका का नाम मान्य माना जाता है:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTableSet`](../../documenttableset) object does not contain a [`DocumentTable`](../../documenttable) instance with the same name.

### संबंधित देखें

* class [DocumentTable](../../documenttable)
* namespace [GroupDocs.Assembly.Data](../../documenttable)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
