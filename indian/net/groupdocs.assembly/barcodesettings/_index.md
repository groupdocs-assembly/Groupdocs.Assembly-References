---
title: "BarcodeSettings"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "दस्तावेज़ को असेंबल करते समय बारकोड जनरेशन को नियंत्रित करने वाले सेटिंग्स के एक समूह का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.assembly/barcodesettings/
---
## BarcodeSettings class

दस्तावेज़ को असेंबल करते समय बारकोड जनरेशन को नियंत्रित करने वाले सेटिंग्स के एक समूह का प्रतिनिधित्व करता है।

```csharp
public class BarcodeSettings
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [BaseXDimension](../../groupdocs.assembly/barcodesettings/basexdimension) { get; set; } | एक बेस X-डायमेंशन प्राप्त करता है या सेट करता है, अर्थात् बारकोड बार और स्पेस की इकाई की सबसे छोटी चौड़ाई। इसे [`GraphicsUnit`](./graphicsunit) में मापा जाता है। |
| [BaseYDimension](../../groupdocs.assembly/barcodesettings/baseydimension) { get; set; } | एक बेस Y-डायमेंशन प्राप्त करता है या सेट करता है, अर्थात् 2D बारकोड मॉड्यूल की इकाई की सबसे छोटी ऊँचाई। इसे [`GraphicsUnit`](./graphicsunit) में मापा जाता है। |
| [GraphicsUnit](../../groupdocs.assembly/barcodesettings/graphicsunit) { get; set; } | एक ग्राफ़िक्स यूनिट प्राप्त करता है या सेट करता है जिसका उपयोग [`BaseXDimension`](./basexdimension) और [`BaseYDimension`](./baseydimension) को मापने के लिए किया जाता है। डिफ़ॉल्ट मान मिलिमीटर है। |
| [Resolution](../../groupdocs.assembly/barcodesettings/resolution) { get; set; } | जनरेट किए जा रहे बारकोड इमेज की क्षैतिज और लंबवत रेज़ोल्यूशन प्राप्त करता है या सेट करता है। इसे डॉट्स प्रति इंच में मापा जाता है। डिफ़ॉल्ट मान 96 है। |
| [UseAutoCorrection](../../groupdocs.assembly/barcodesettings/useautocorrection) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि क्या एक अमान्य बारकोड मान को स्वचालित रूप से (यदि संभव हो) बारकोड के विनिर्देश के अनुरूप सुधारा जाना चाहिए या त्रुटि दर्शाने के लिए एक अपवाद फेंका जाना चाहिए। डिफ़ॉल्ट मान true है। |

### संबंधित देखें

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
