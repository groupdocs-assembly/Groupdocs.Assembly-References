---
title: "BaseYDimension"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "एक बेस y‑डायमेंशन सेट या प्राप्त करता है जो 2D बारकोड मॉड्यूल की इकाई की सबसे छोटी ऊँचाई है। माप इकाई GraphicsUnitgroupdocs.assembly/barcodesettings/graphicsunit में है।"
type: docs
weight: 20
url: /hi/net/groupdocs.assembly/barcodesettings/baseydimension/
---
## BarcodeSettings.BaseYDimension property

एक बेस y‑डायमेंशन सेट या प्राप्त करता है, अर्थात 2D बारकोड मॉड्यूल की इकाई की सबसे छोटी ऊँचाई। माप इकाई [`GraphicsUnit`](../graphicsunit) में है।

```csharp
public float BaseYDimension { get; set; }
```

### टिप्पणियाँ

कुछ प्रकार के बारकोड (जैसे डेटा मैट्रिक्स) y‑डायमेंशन को अनदेखा कर सकते हैं और चौड़ाई तथा ऊँचाई दोनों इकाइयों के लिए x‑डायमेंशन का उपयोग कर सकते हैं।

जब टेम्प्लेट के माध्यम से बारकोड स्केलिंग लागू की जाती है, तो वास्तविक y‑डायमेंशन बेस y‑डायमेंशन और स्केलिंग फैक्टर के आधार पर गणना की जाती है।

### संबंधित देखें

* class [BarcodeSettings](../../barcodesettings)
* namespace [GroupDocs.Assembly](../../barcodesettings)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
