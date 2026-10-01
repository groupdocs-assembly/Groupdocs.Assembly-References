---
title: "मीटरड"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "मीटर आधारित लाइसेंसिंग के साथ काम करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 90
url: /hi/net/groupdocs.assembly/metered/
---
## Metered class

मीटर आधारित लाइसेंसिंग के साथ काम करने के लिए मेथड्स प्रदान करता है।

```csharp
public class Metered
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Metered](metered)() | इस क्लास की नई इंस्टेंस बनाता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | उपयुक्त सार्वजनिक और निजी मीटरड कुंजियों को निर्दिष्ट करके घटक के लिए मीटरड लाइसेंसिंग सक्षम करता है। |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | वर्तमान में उपयोग किए गए क्रेडिट्स की संख्या लौटाता है। |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | वर्तमान में उपयोग किए गए मेगाबाइट्स की संख्या लौटाता है। |

### उदाहरण

इस उदाहरण में, मीटरड सार्वजनिक और निजी कुंजियों को सेट करने का प्रयास किया गया है:

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### संबंधित देखें

* namespace [GroupDocs.Assembly](../../groupdocs.assembly)
* assembly [GroupDocs.Assembly](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
