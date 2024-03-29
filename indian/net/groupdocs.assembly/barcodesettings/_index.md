---
title: BarcodeSettings
second_title: GroupDocs.Assembly .NET API संदर्भ के लिए
description: दस्तवेज़ क असेंबल करते समय बरकड जनरेशन क नयंत्रत करने वल सेटंग्स के एक सेट क प्रतनधत्व करत है
type: docs
weight: 10
url: /hi/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

दस्तावेज़ को असेंबल करते समय बारकोड जनरेशन को नियंत्रित करने वाली सेटिंग्स के एक सेट का प्रतिनिधित्व करता है।

```csharp
public class BarcodeSettings
```

## गुण

| नाम | विवरण |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | आधार x-आयाम प्राप्त करता है या सेट करता है, यानी बारकोड बार और रिक्त स्थान की इकाई की सबसे छोटी चौड़ाई। में मापी गई[`GraphicsUnit`](./graphicsunit) . |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | एक आधार y-आयाम प्राप्त करता है या सेट करता है, अर्थात, 2D बारकोड मॉड्यूल की इकाई की सबसे छोटी ऊंचाई। में मापी गई[`GraphicsUnit`](./graphicsunit) . |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | मापने के लिए उपयोग की जाने वाली ग्राफ़िक्स इकाई प्राप्त या सेट करता है[`BaseXDimension`](./basexdimension) और[`BaseYDimension`](./baseydimension) . डिफ़ॉल्ट मान हैMillimeter . |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | उत्पन्न होने वाली बारकोड छवि के क्षैतिज और लंबवत रिज़ॉल्यूशन को प्राप्त या सेट करता है। डॉट्स प्रति इंच में मापा गया। डिफ़ॉल्ट मान 96. है |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | एक मान प्राप्त या सेट करता है जो इंगित करता है कि क्या अमान्य बारकोड मान को स्वचालित रूप से ठीक किया जाना चाहिए (यदि संभव हो) बारकोड के विनिर्देश को फिट करने के लिए या त्रुटि को इंगित करने के लिए अपवाद फेंक दिया जाना चाहिए। डिफ़ॉल्ट मान सत्य है। |

### यह सभी देखें

* नाम स्थान [GroupDocs.Assembly](../../groupdocs.assembly)
* सभा [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->
