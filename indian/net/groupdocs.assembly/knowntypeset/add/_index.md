---
title: "जोड़ें"
second_title: "GroupDocs.Assembly .NET के लिए API रेफ़रेंस"
description: "निर्दिष्ट Type वस्तु को सेट में जोड़ता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.assembly/knowntypeset/add/
---
## KnownTypeSet.Add method

निर्दिष्ट Type वस्तु को सेट में जोड़ता है।

निम्नलिखित मामलों में ArgumentException फेंकता है:

- *type* is null.

- *type* represents a void type.

- *type* represents an invisible type, i.e. a non-public type or a public nested type which has a non-public outer type.

- *type* represents a generic type.

- *type* represents an array type.

- *type* has been added to the set already.

```csharp
public void Add(Type type)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रकार | प्रकार | जोड़ने के लिए एक Type ऑब्जेक्ट। |

### संबंधित देखें

* class [KnownTypeSet](../../knowntypeset)
* namespace [GroupDocs.Assembly](../../knowntypeset)
* assembly [GroupDocs.Assembly](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Assembly.dll के लिए उत्पन्न किया गया -->
