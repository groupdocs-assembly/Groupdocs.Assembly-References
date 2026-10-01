---
title: "JsonSimpleValueParseMode"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "JSON लोड करते समय JSON सरल मानों (null, boolean, number, integer और string) को पार्स करने के लिए एक मोड निर्दिष्ट करता है। ऐसा मोड datetime मानों के पार्सिंग को प्रभावित नहीं करता।"
type: docs
weight: 240
url: /hi/net/groupdocs.assembly.data/jsonsimplevalueparsemode/
---
## JsonSimpleValueParseMode enumeration

JSON लोड करते समय JSON सरल मानों (null, boolean, number, integer, और string) को पार्स करने के लिए एक मोड निर्दिष्ट करता है। ऐसा मोड दिनांक-समय मानों के पार्सिंग को प्रभावित नहीं करता।

```csharp
public enum JsonSimpleValueParseMode
```

### Values

| नाम | Value | विवरण |
| --- | --- | --- |
| Loose | `0` | एक मोड निर्दिष्ट करता है जहाँ JSON सरल मानों के प्रकार उनकी स्ट्रिंग प्रतिनिधित्व के पार्स होने पर निर्धारित होते हैं। उदाहरण के लिए, JSON स्निपेट '{ prop: \"123\" }' में 'prop' का प्रकार इस मोड में integer के रूप में निर्धारित होता है। |
| Strict | `1` | एक मोड निर्दिष्ट करता है जहाँ JSON सरल मानों के प्रकार सीधे JSON नोटेशन से निर्धारित होते हैं। उदाहरण के लिए, JSON स्निपेट '{ prop: \"123\" }' में 'prop' का प्रकार इस मोड में string के रूप में निर्धारित होता है। |

### संबंधित देखें

* namespace [GroupDocs.Assembly.Data](../../groupdocs.assembly.data)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
