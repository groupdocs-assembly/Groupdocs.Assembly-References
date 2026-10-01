---
title: "UseReflectionOptimization"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "कस्टम टाइप सदस्यों के रिफ्लेक्शन API के माध्यम से किए गए कॉल को डायनामिक क्लास जेनरेशन द्वारा अनुकूलित किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान true है।"
type: docs
weight: 60
url: /hi/net/groupdocs.assembly/documentassembler/usereflectionoptimization/
---
## DocumentAssembler.UseReflectionOptimization property

कस्टम टाइप सदस्यों के रिफ्लेक्शन API के माध्यम से किए गए कॉल को डायनामिक क्लास जेनरेशन द्वारा अनुकूलित किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान true है।

```csharp
public static bool UseReflectionOptimization { get; set; }
```

### टिप्पणियाँ

ऐसे कुछ परिदृश्य हैं जहाँ इस अनुकूलन को निष्क्रिय करना अधिक उपयुक्त होता है। उदाहरण के लिए, यदि आप लगातार छोटे डेटा आइटम्स के संग्रह के साथ काम कर रहे हैं, तो डायनेमिक क्लास जेनरेशन का ओवरहेड सीधे रिफ्लेक्शन API कॉल्स के ओवरहेड की तुलना में अधिक स्पष्ट हो सकता है।

### संबंधित देखें

* class [DocumentAssembler](../../documentassembler)
* namespace [GroupDocs.Assembly](../../documentassembler)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
