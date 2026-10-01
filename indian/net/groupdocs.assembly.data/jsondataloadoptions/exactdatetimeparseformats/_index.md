---
title: "ExactDateTimeParseFormats"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "JSON लोड करते समय JSON datetime मानों को पार्स करने के लिए सटीक फ़ॉर्मेट प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से यह null है।"
type: docs
weight: 30
url: /hi/net/groupdocs.assembly.data/jsondataloadoptions/exactdatetimeparseformats/
---
## JsonDataLoadOptions.ExactDateTimeParseFormats property

JSON लोड करते समय JSON तिथि-समय मानों को पार्स करने के लिए सटीक फ़ॉर्मेट प्राप्त करता है या सेट करता है। डिफ़ॉल्ट **null** है।

```csharp
public IEnumerable<string> ExactDateTimeParseFormats { get; set; }
```

### टिप्पणियाँ

Microsoft® JSON डेट‑टाइम फ़ॉर्मेट (उदाहरण के लिए, "/Date(1224043200000)/") का उपयोग करके एन्कोड की गई स्ट्रिंग्स हमेशा इस प्रॉपर्टी के मान की परवाह किए बिना डेट‑टाइम मानों के रूप में पहचानी जाती हैं। यह प्रॉपर्टी स्ट्रिंग्स से डेट‑टाइम मानों को पार्स करने के लिए उपयोग किए जाने वाले अतिरिक्त फ़ॉर्मेट को निम्नलिखित तरीके से परिभाषित करती है:

* When `ExactDateTimeParseFormats` is **null**, the ISO-8601 format and all date-time formats supported for the current, English USA, and English New Zealand cultures are used additionally in the mentioned order.
* When `ExactDateTimeParseFormats` contains strings, they are used as additional date-time formats utilizing the current culture.
* When `ExactDateTimeParseFormats` is empty, no additional date-time formats are used.

### संबंधित देखें

* class [JsonDataLoadOptions](../../jsondataloadoptions)
* namespace [GroupDocs.Assembly.Data](../../jsondataloadoptions)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
