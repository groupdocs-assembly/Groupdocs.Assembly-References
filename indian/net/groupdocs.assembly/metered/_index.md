---
title: Metered
second_title: GroupDocs.Assembly .NET API संदर्भ के लिए
description: मटर्ड लइसेंसंग के सथ कम करने के तरके प्रदन करत है
type: docs
weight: 260
url: /hi/net/groupdocs.assembly/metered/
---
## Metered class

मीटर्ड लाइसेंसिंग के साथ काम करने के तरीके प्रदान करता है।

```csharp
public class Metered
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Metered](metered)() | इस वर्ग का एक नया उदाहरण बनाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [SetMeteredKey](../../groupdocs.assembly/metered/setmeteredkey)(string, string) | उपयुक्त सार्वजनिक और निजी मीटर्ड कुंजियों को निर्दिष्ट करके घटक के लिए मीटर्ड लाइसेंसिंग को सक्षम करता है। |
| static [GetConsumptionCredit](../../groupdocs.assembly/metered/getconsumptioncredit)() | क्रेडिट की वर्तमान में खपत संख्या लौटाता है। |
| static [GetConsumptionQuantity](../../groupdocs.assembly/metered/getconsumptionquantity)() | मेगाबाइट की वर्तमान में खपत संख्या लौटाता है। |

### उदाहरण

इस उदाहरण में, मीटर की गई सार्वजनिक और निजी कुंजियों को सेट करने का प्रयास किया गया है:

```csharp
[C#]

Metered metered = new Metered();
metered.SetMeteredKey("PublicKey", "PrivateKey");

[Visual Basic]

Dim metered As Metered = New Metered
metered.SetMeteredKey("PublicKey", "PrivateKey")
```

### यह सभी देखें

* नाम स्थान [GroupDocs.Assembly](../../groupdocs.assembly)
* सभा [GroupDocs.Assembly](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Assembly.dll -->