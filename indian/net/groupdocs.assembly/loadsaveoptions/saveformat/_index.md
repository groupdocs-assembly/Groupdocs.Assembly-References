---
title: "SaveFormat"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "एक फ़ाइल फ़ॉर्मेट प्राप्त करता है या सेट करता है जिससे असेंबल किया गया दस्तावेज़ सहेजा जाएगा। यदि निर्दिष्ट नहीं है तो डिफ़ॉल्ट मान लागू होता है।"
type: docs
weight: 40
url: /hi/net/groupdocs.assembly/loadsaveoptions/saveformat/
---
## LoadSaveOptions.SaveFormat property

एक फ़ाइल फ़ॉर्मेट प्राप्त करता है या सेट करता है जिससे असेंबल किया गया दस्तावेज़ सहेजा जाएगा। यदि निर्दिष्ट नहीं है तो डिफ़ॉल्ट मान लागू होता है।

```csharp
public FileFormat SaveFormat { get; set; }
```

### टिप्पणियाँ

जब इस प्रॉपर्टी का मान निर्दिष्ट नहीं किया जाता है, तो [`DocumentAssembler`](../../documentassembler) निम्नानुसार व्यवहार करता है:

- When you specify a file path to save an assembled document, the save file format is determined upon file extension from the path.

- When you specify a stream to save an assembled document, the save file format remains the same as the file format of a loaded template document.

ध्यान दें कि GroupDocs.Assembly का उपयोग करके किसी भी फ़ाइल फ़ॉर्मेट में असेंबल्ड दस्तावेज़ को सहेजना हमेशा संभव नहीं होता। उदाहरण के लिए, एक Word प्रोसेसिंग फ़ाइल फ़ॉर्मेट (जैसे DOCX) से लोड किए गए दस्तावेज़ को Spreadsheet फ़ाइल फ़ॉर्मेट (जैसे XLSX) में सहेजना असंभव है। GroupDocs.Assembly द्वारा समर्थित लोड और सेव फ़ाइल फ़ॉर्मेट के संभावित संयोजनों के बारे में अधिक जानकारी के लिए कृपया GroupDocs.Assembly ऑनलाइन दस्तावेज़ देखें।

### संबंधित देखें

* enum [FileFormat](../../fileformat)
* class [LoadSaveOptions](../../loadsaveoptions)
* namespace [GroupDocs.Assembly](../../loadsaveoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
