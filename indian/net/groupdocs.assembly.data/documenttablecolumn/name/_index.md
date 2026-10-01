---
title: "नाम"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "टेम्पलेट दस्तावेज़ में कॉलम डेटा तक पहुँचने के लिए उपयोग किए जाने वाले इस कॉलम का नाम प्राप्त करता है या सेट करता है, जिसे DocumentAssemblergroupdocs.assembly/documentassembler को पास किया जाता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.assembly.data/documenttablecolumn/name/
---
## DocumentTableColumn.Name property

टेम्पलेट दस्तावेज़ में कॉलम के डेटा तक पहुँचने के लिए उपयोग किए जाने वाले इस कॉलम का नाम प्राप्त करता है या सेट करता है, जिसे [`DocumentAssembler`](../../../groupdocs.assembly/documentassembler) को पास किया जाता है।

```csharp
public string Name { get; set; }
```

### टिप्पणियाँ

यदि कॉलम का नाम किसी दस्तावेज़ से पढ़ा जाता है (देखें [`FirstRowContainsColumnNames`](../../documenttableoptions/firstrowcontainscolumnnames)), तो नाम को स्वचालित रूप से सही किया जाता है ताकि वह मान्य हो। हालांकि, यदि इस गुण के माध्यम से कॉलम का नाम मैन्युअल रूप से सेट किया जाता है और वह अमान्य है, तो एक अपवाद फेंका जाता है।

यदि निम्न शर्तें पूरी होती हैं तो कॉलम का नाम मान्य माना जाता है:

* The name is not empty.
* The name's first character is a letter or underscore.
* The rest of the name's characters are letters, underscores, digits, or the following characters: '@', '#', '$'.
* The corresponding [`DocumentTable`](../../documenttable) object does not contain a [`DocumentTableColumn`](../../documenttablecolumn) instance with the same name.

### संबंधित देखें

* class [DocumentTableColumn](../../documenttablecolumn)
* namespace [GroupDocs.Assembly.Data](../../documenttablecolumn)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
