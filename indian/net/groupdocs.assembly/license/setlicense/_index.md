---
title: "SetLicense"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "घटक को लाइसेंस देता है।"
type: docs
weight: 30
url: /hi/net/groupdocs.assembly/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

घटक को लाइसेंस देता है।

```csharp
public void SetLicense(string licenseName)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseName | String | यह पूर्ण या संक्षिप्त फ़ाइल नाम या एम्बेडेड रिसोर्स का नाम हो सकता है। मूल्यांकन मोड में स्विच करने के लिए खाली स्ट्रिंग का उपयोग करें। |

### टिप्पणियाँ

लाइसेंस को निम्नलिखित स्थानों में खोजने का प्रयास करता है:

1. स्पष्ट पथ।

2. वह फ़ोल्डर जिसमें GroupDocs घटक असेंबली शामिल है।

3. वह फ़ोल्डर जिसमें क्लाइंट की कॉलिंग असेंबली शामिल है।

4. वह फ़ोल्डर जिसमें एंट्री (स्टार्टअप) असेंबली शामिल है।

5. क्लाइंट की कॉलिंग असेंबली में एक एम्बेडेड रिसोर्स।

### संबंधित देखें

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

---

## SetLicense(Stream) {#setlicense}

घटक को लाइसेंस देता है।

```csharp
public void SetLicense(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | एक स्ट्रीम जिसमें लाइसेंस शामिल है। |

### टिप्पणियाँ

स्ट्रीम से लाइसेंस लोड करने के लिए इस मेथड का उपयोग करें।

### संबंधित देखें

* class [License](../../license)
* namespace [GroupDocs.Assembly](../../license)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
